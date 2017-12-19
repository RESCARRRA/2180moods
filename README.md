# 2180 Mood-in-Pixels

This application will track your daily mood with one click. It has been developed to allow users a overview of their weekly, monthly and yearly state of mind.
Emotional states are represented by colour in this app. Each day users will log the choice that best represents their mood, which is then stored to a server. All entries are available for future review in the form of a personalized, unique spectrum, including both date and location of use.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

You will need

```
node.js
MySQL
```

### Installing

Fork, clone, or download the code base from GitHub. Then

```
npm install
```

to get the modules you need. 
Then create SQL database using 

```
schema.sql
```

## Running the tests

We used Nightmare and Mocha to create tests. To run the tests enter
```
npm test 
```
on the command line. 
Once running the test will create a new user and log them into the site, creating a screen capture at the moment of on-click event.

## Deployment

Deployment is through Heroku using JAWs for SQL data base requirements.

## Built With

* [Sequelize](http://docs.sequelizejs.com/) 
* [Passport](http://www.passportjs.org/) 
* [modernizr](https://modernizr.com/) 
* [Wow](http://mynameismatthieu.com/WOW/) 
* [Path](https://nodejs.org/api/path.html) 
* [Bootstrap](https://getbootstrap.com/) 
* [Google Fonts](https://fonts.google.com/) 
* [Nightmare](http://www.nightmarejs.org/) 


## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Ryn Escarra-Cypher** - [rescarra](https://github.com/rescarra)
* **Gintas Vasiliauskas** - [GintasVasiliauskas](https://github.com/GintasVasiliauskas)
* **Enrique Rojas** - [ero646](https://github.com/ero646)
* **Laura Wentzell-Ahmad** - [laah](https://github.com/laah)
