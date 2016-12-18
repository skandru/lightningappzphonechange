# Heroku Connect Sample - Phone Change

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/jamesward/heroku-connect-phone-change)

# Local Dev

    PGSSLMODE=require DATABASE_URL=postgres://foo:bar@asdf.com:5432/1234 npm start
	
If you are using a Windows machine
To set the DATABASE_URL environment variable to the Heroku Postgres database and start the local Node.js app, run the following from the command line:
SET DATABASE_URL=`heroku config:get DATABASE_URL`
SET PGSSLMODE=require
npm start 
