# Chosen Language/Frameworks
* ## Backend
    * NodeJS
    * WebSockets Server (WS)
        * Later changed to Deepstream.io
    * Database (RethinkDB)
    * Process Manager
        * Later replaced with Heroku's own services
    * ExpressJS HTTP Server

* ## Middleware
    * Initially Bespoke WebSocket Communication
    * Data retrieval via WS (Not RESTful)
        * Decision dictated by shared development

* ## Frontend (Website)
    * ExpressJS
    * Deepstream

* ## Frontend (Application)
    * Aurelia.io
    * Aurelia-Materialize-Bridge
    * Materialize.css
    * WebSocket Server Client
        * Later on Deepstream.io Client
    * Plus other relevant modules

* ## Testing Frameworks
    * Aurelia-Testing
        * Component Testing
        * Integrates with testing frameworks below.
    * https://jasmine.github.io/
        * Unit
        * Integration
        * Primarily Backend
    * Protractor/Karma (e2e, frontend)

* ## Wrapper
    * Cordova (via Adobe PhoneGap)

* ## Package Managment
    * NPM (Node Package Manager)
    * Gulp (Task Runner)
    * Aurelia CLI