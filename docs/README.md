# Udagram

## main end point 


<http://deployment-project-bucket.s3-website-us-east-1.amazonaws.com>


## Dependencies

- Node v14.15.1 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 6.14.8 (LTS) or more recent, Yarn can work but was not tested for this project

- AWS CLI v2, v1 can work but was not tested for this project

- AWS EB CLI

- AWS RDS database running Postgres.

- AWS S3 bucket for Frontend.

- AWS Elastic Beanstalk for Backend.

## Backend Packages

- types/bcryptjs
- types/jsonwebtoken
- bcryptjs
- body-parser
- cors
- dotenv
- email-validator
- express
- jsonwebtoken
- pg
- reflect-metadata
- sequelize
- sequelize-typescript

## Frontend Packages

- angular/common
- angular/core
- angular/forms
- angular/http
- angular/platform-browser
- angular/platform-browser-dynamic
- angular/router
- ionic-native/core
- ionic-native/splash-screen
- ionic-native/status-bar
- ionic/angular
- core-js
- rxjs
- zone.js

## Environment variables

- POSTGRES_USERNAME=postgres
- POSTGRES_PASSWORD=myPassword
- POSTGRES_HOST=postgres.cc9v61kkjvuh.us-east-1.rds.amazonaws.com
- POSTGRES_DB=postgres
- AWS_BUCKET=arn:aws:s3:::deployment-project-bucket
- AWS_REGION=us-east-1
- AWS_PROFILE=default
- JWT_SECRET=mysecretstring
- URL=`<http://deployment-project-dev.eba-upnmgpzr.us-east-1.elasticbeanstalk.com/>`
- PORT=3000
- DB_PORT=5432
- AWS_ACCESS_KEY_ID=AKIAQUOG36D34RZGWZEA
- AWS_SECRET_ACCESS_KEY=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
- AWS_DEFAULT_REGION=us-east-1

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework
