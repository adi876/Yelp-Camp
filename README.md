# Yelp-Camp
YelpCamp is a campground reviewing website. Users can create their own campgrounds or review others' campgrounds.
YelpCamp is created using Node.js, Express, and MongoDB.



## Features
* Authentication
  * User login with username and password
  * Admin sign-up with admin code
* Authorization
  * User cannot manage posts without being authenticated
  * User cannot edit or delete posts and comments created by other users
  * Admin can manage all posts and comments
* Manage campground posts
  * User can create, edit and delete posts and comments
  * User can search existing campgrounds by name
* Flash messages responding to users' interaction with the app
* Responsive web design

## Getting Started
### Clone or download this repository
```
git clone https://github.com/adi876/Yelp-Camp.git
```
### Get mongoDB
```
Go to https://www.mongodb.com/
```
### Install dependencies
```
npm install
```
or
```
yarn install
```
### Running locally
```
Run mongod in another terminal and node app.js in the terminal with the project

Then go to localhost:3000
```
## Built With
### Front-end
* [ejs](https://ejs.co/)
* [Bootstrap](https://getbootstrap.com/docs/4.6/getting-started/introduction/)
### Back-end
* [Nodejs](https://nodejs.org/en/)
* [Express](https://expressjs.com/)
* [mongoDB](https://www.mongodb.com/)
* [mongoose](https://mongoosejs.com/)
* [Passport](http://www.passportjs.org/)
* [passport-local](https://github.com/jaredhanson/passport-local#passport-local)
* [passport-local-mongoose](https://www.npmjs.com/package/passport-local-mongoose)
* [express-session](https://github.com/expressjs/session#express-session)
* [method-override](https://github.com/expressjs/method-override#method-override)
* [Moment](https://momentjs.com/)
* [connect-flash](https://github.com/jaredhanson/connect-flash#connect-flash)

## Platforms
* [Heroku](https://id.heroku.com/login)

## Authors
* [Aditya Patni](https://github.com/adi876)

## Acknowledgments
* Colt Steele's Bootcamp course
