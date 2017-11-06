# Design Choices & Changes
* ## Messaging/Real-Time Connectivity
    * WebSocket Server & Client
    * Defined Messaging Prototocol
    * Assumed Server driven experience
    * Uses 'Observer Pattern'/Node Events library.

* ## Servers, PaaS / Saas:
    * Informated by client cost.
    * Database
        * Compose.io
    * Node Process
        * http://modulus.io/ (Bought out? became Xervo)
        * http://xervo.io/ (Stopped)
        * Heroku (PaaS)
            * SendGrid
            * PaperTrail / Logging

* ## Security
    * Password Hash,
    * JWT (JSON Web Tokens)

* ## Major Changes
    * Separation from Space Escape
        * Expanded Spec
    * Deepstream.io
    * Modulous > Xervo > Heroku