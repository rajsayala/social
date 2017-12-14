# 🐣 Gatsby Firebase Authentication

Your minimal yet extensive authentication starter project in Gatsby.js with Firebase and plain React.

* Powered by [Gatsby](https://github.com/gatsbyjs/gatsby)
* [Live](https://react-firebase-authentication.wieruch.com/)
* Found in [Taming the State in React](https://roadtoreact.com/course-details?courseId=TAMING_THE_STATE)

## Features

* uses:
  * only React (Gatsby.js)
  * firebase 4.8.0
* features:
  * Sign In
  * Sign Up
  * Sign Out
  * Password Forget
  * Password Change
  * Protected Routes with Authorization
  * Database: Users

## Setup

* `git clone git@github.com:rwieruch/gatsby-firebase-authentication.git`
* `cd gatsby-firebase-authentication`
* `npm install`
* `gatsby develop`
* visit http://localhost:8000/
* Use your own Firebase Credentials

### Use your own Firebase Credentials

* visit https://firebase.google.com/ and create a Firebase App
* copy and paste your Credentials from your Firebase App into src/firebase/firebase.js
* activate Email/Password Sign-In Method in your Firebase App

## Setup via Gatsby CLI

* `gatsby new gatsby-firebase-authentication git@github.com:rwieruch/gatsby-firebase-authentication.git`
* `cd gatsby-firebase-authentication`
* `npm install`
* `gatsby develop`
* visit http://localhost:8000/
* Use your own Firebase Credentials