# React App Boilerplate Code Version 2

This is boilerplate for building a full stack application using the MERN Stack. Please feel free to use it as starter code for your projects.

## Technology Used

Here is a list of all Technology ready for you to use in this boilerplate.

* Node
* Express.js
* Firebase Authentication / Real-Time Database
* React / React Router / Redux
* Webpack
* Jest / Enzyme for Unit Testing
* Heroku Ready

## Getting Started

To start you will want to create two files.
` .env.development & .env.test `

each setup with the firebase env key values to your firebase app config settings:

```
FIREBASE_API_KEY=<firebase_api_key>
FIREBASE_AUTH_DOMAIN=<firebase_auth_domain>
FIREBASE_DATABASE_URL=<firebase_database_url>
FIREBASE_PROJECT_ID=<firebase_project_id>
FIREBASE_STORAGE_BUCKET=<firebase_storage_bucket>
FIREBASE_MESSAGING_SENDER_ID=<firebase_messaging_sender_id>
```

Afterwards run `yarn install` to install the dependencies.

## Running the Dev Server

Once everything has been installed and your .env files have been setup you can run 
`yarn run dev-server` to start the development server. This will run both express server and serve the react server for you with webpack.

## Running the Test Server

To start the test server with Jest simply run `yarn run test --watch` and the test server will start.

## Deployment

To deploy make sure to have a heroku account and run `heroku login` to setup heroku on your system.
Afterwards run `heroku create` to setup a new heroku app for your project.
Last after you have setup your git commit and are ready to push simply push to your heroku master branch and the application will build on heroku.

