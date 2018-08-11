# Server

## Local Environment
```
cd server;
npm install;
npm run dev;
```

Local server runs on `localhost:5000`

## Heroku Deployment
```
git push heroku master;
```

## Google API Project Console
https://console.developers.google.com/apis/credentials?project=emaily-dev-212610

## Libraries
- [passport](http://www.passportjs.org/)
    - Auth
- [passport-google-oauth2](https://github.com/jaredhanson/passport-google-oauth2)
    - Auth Strategy
- [nodemon](https://github.com/remy/nodemon)
    - Watch node code for restarting server
- [express](https://expressjs.com/)
    - Server framework
- [mongoose](http://mongoosejs.com/)
    - MongoDB object modelling library to create schemas and query building logic into node.
    - Database can be accessed from https://mlab.com/databases/
- [cookie-session](https://github.com/expressjs/cookie-session)
    - Simple cookie-based session middleware for express
    - The session is limited to 4kb
    - The cookie encrypts the data sent to the browser
    - The cookie when received, deserializes the cookie data and stores the data to the express session object (`req.session`)
- [concurrently](https://github.com/kimmobrunfeldt/concurrently)
    - Allows multiple scripts to be executed 