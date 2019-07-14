# Hear2Text-getting-started

Empowering connections for people with auditory impairments

## Running Locally

Make sure you have [Node.js](http://nodejs.org/) and the [Heroku CLI](https://cli.heroku.com/) installed.

```sh
$ git clone https://github.com/ilias-karimalis/angelhack2019
$ cd angelhack2019
$ npm install
$ npm start
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Working with Google Cloud Speech To Text
$ you'll need to generate a projectId, and Keyfile
$ replace those variables in index.js

## Working with sound recording
$ MAC - brew install sox
$ PC 
$ Go to My Computer → Properties → Advanced System Settings → Environment Variables → System variables.
$ Select Path.
$ Click Edit → New :
$ Add this: C:\Program Files (x86)\sox-<CHECK YOUR VERSION NUMBER>\
$ As indicated in the example path, make sure to check what version of Sox you have installed by actually navigating to your $ Program Files (x86) folder and looking for a folder that starts with sox, for example sox-14-4-2.
$ Restart your terminal.
