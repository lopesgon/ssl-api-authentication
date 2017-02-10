# ssl-api-authentication
This project is a SSL/TLS API Authentication using Node.js and Mongodb.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

Note: I am not an expert in web security (trying to get a feet in) and all project has been done following tutorials and combining technologies. 

If you want more details about sources in the bottom of the readme file. If you want to have a better understanding of the dependencies or methods used, refer to the documentation available on dependencies websites.

### Prerequisites

* Node.js & npm package manager have to be installed.
* Mongodb has to be installed.

Not required but usefull:

* [Postman](https://chrome.google.com/webstore/detail/postman/fhbjgbiflinjbdggehcddcbncdddomop) - For testing the connexion.
* [Robomongo](https://robomongo.org) - It helps to navigate through Mongodb database (instead of using terminal).

### Installing

Once the prerequisites done, you have copy the repository in your local machine and run the commands:

```
git clone git@github.com:lopesgon/ssl-api-authentication.git projet
cd projet
npm install
```

Once npm has created node_modules directory and finished installing the dependencies, go to ```cd ./bin``` folder and run ```node www```.

You can now access to the server via https://127.0.0.1:3000 with SSL/TLS protocol and authenticate users securely.

## Built With

* [Mongoosejs](http://mongoosejs.com) - mongodb object modeling for Node.js.
* [Passportjs](http://passportjs.org) - Authentication for Node.js.
* [Passport-jwt](https://github.com/themikenicholson/passport-jwt) - A Passport strategy for authenticating with a JSON Web Token.
* [JSON Web Token (JWT)](https://jwt.io) - Representing claims securely between two parties.

## Authors

* **Frederic Lopes**

## Acknowledgments

Hereafter the different sources used to develop the API:
* [devdactic](http://devdactic.com/restful-api-user-authentication-1/) - for the authentication code.
* [sitepoint](https://www.sitepoint.com/how-to-use-ssltls-with-node-js/) - for a HTTPS implementation.
