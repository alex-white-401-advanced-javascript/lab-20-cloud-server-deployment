![CF](http://i.imgur.com/7v5ASc8.png) Lab 20
=================================================

## Cloud Server Deployment

### Author: Alexander White

### Links and Resources
Four repositories were required for this lab assignment. The submission pull request, Travis.CI build, and actual code repository for each are listed below.
#### 1. Message Queue Server 
   * [PR](https://github.com/alex-white-401-advanced-javascript/log-19-api-server/pull/2)
   * [![Build Status](https://travis-ci.com/alex-white-401-advanced-javascript/log-19-server.svg?branch=master)](https://travis-ci.com/alex-white-401-advanced-javascript/log-19-server)
   * [Azure](https://polar-sands-74657.herokuapp.com)
#### 2. Message Queue Logger 
   * [PR](https://github.com/alex-white-401-advanced-javascript/lab-19-logger/pull/1)
   * [![Build Status](https://travis-ci.com/alex-white-401-advanced-javascript/lab-19-logger.svg?branch=submission)](https://travis-ci.com/alex-white-401-advanced-javascript/lab-19-logger)
   * [AWS](https://morning-river-32655.herokuapp.com)
#### 4. API Server
   * [PR](https://github.com/alex-white-401-advanced-javascript/log-19-api-server/pull/2)
   * [![Build Status](https://travis-ci.com/alex-white-401-advanced-javascript/log-19-api-server.svg?branch=resub)](https://travis-ci.com/alex-white-401-advanced-javascript/log-19-api-server)
   * [Heroku](https://safe-lake-94306.herokuapp.com)


### Modules
#### `modulename.js`
##### Exported Values and Methods

###### `foo(thing) -> string`
<!-- If you finished everything, you should be able to copy/paste the lab requirements and put them in present tense. -->
Usage Notes or examples

###### `bar(array) -> array`
Usage Notes or examples

### Setup
#### `.env` requirements
* `npm i`
* `PORT` - assign a port number
* `MONGODB_URI` - URL to the running mongo instance/db


#### Running the app
* `npm start`
* Endpoint: `/`
* Endpoint: `/foo/bar/`
  * Returns a JSON object with abc in it.
* Endpoint: `/bing/zing/`
  * Returns a JSON object with xyz in it.
  
#### Tests
* How do you run tests?
  * `npm run test`
  * `npm run lint`
* What assertions were made?
* What assertions need to be / should be made?

#### UML
Link to an image of the UML for your application and response to events
