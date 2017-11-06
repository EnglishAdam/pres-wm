---
layout: page
title: 05. Language and Framework
permalink: /lang_con/
---
# Language Considerations & Choices
#### Base Decisions
* Hybrid App
    * Cross platform
    * My capabilities
* JavaScript
    * Single Page Applications
    * Mobile development
    * Large access to library's soultions
* HTML
* CSS

#### Tech Comparison Overview
* Informed by Space Escape
    * Meteor (https://www.meteor.com/)
    * Arduino prototyping
    * MongoDB (https://www.mongodb.com/)

#### Comparison table
* __See Email__

#### Comparison Hybrid App Framework
* https://framework7.io/
* http://ionicframework.com/
* https://famous.co/

***

# Chosen Language/Frameworks
#### Backend
* NodeJS (https://nodejs.org/en/)
* WebSockets Server (WS)
    * Later changed to Deepstream.io
* RethinkDB Database (https://rethinkdb.com/)
    * Thinky (http://justonepixel.com/thinky/)
* Process Manager
    * Later replaced with Heroku's own services (https://www.heroku.com/)
* ExpressJS HTTP Server (https://expressjs.com/)

#### Middleware
* Initially Bespoke WebSocket Communication
* Data retrieval via WS (Not RESTful)
    * Decision dictated by shared development

#### Frontend (Website)
* ExpressJS (https://expressjs.com/)
* Deepstream (https://deepstream.io/)

#### Frontend (Application)
* Aurelia.io (http://aurelia.io/)
* Aurelia-Materialize-Bridge (https://aurelia-ui-toolkits.github.io/demo-materialize/)
* Materialize.css (http://materializecss.com/)
* WebSocket Server Client
    * Later on Deepstream.io Client
* Plus other relevant modules

#### Testing Frameworks
* Aurelia-Testing
    * Component Testing
    * Integrates with testing frameworks below.
* https://jasmine.github.io/
    * Unit
    * Integration
    * Primarily Backend
* Protractor/Karma (e2e, frontend)

#### Wrapper
* Cordova (via Adobe PhoneGap, https://phonegap.com/)

#### Package Managment
* NPM (Node Package Manager, http://npmjs.com/)
* Gulp (Task Runner, https://gulpjs.com/)
* Aurelia CLI