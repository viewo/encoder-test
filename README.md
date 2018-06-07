# README #

* encoder-test can take an input video from the client's file system, transcode it in the cloud, and upload to cloud storage.
* Version 1.0

## How do I get set up? ##

* Install node.js, and npm.js: [Node](https://nodejs.org/en/) or from homebrew on mac: [Homebrew](http://brew.sh/)
* Install bower and run yarn or npm install
* $ npm install -g bower
* $ npm install
* $ bower install
* Update **/src/config/config.ts with your aws access key and secret key for S3 uploading. Along with your bento4/bin path and path to your local media file**
* Update the *bucketName* value in **/src/config/config.ts** with your s3 bucket name
* Turn local cleanup on/off with the cleanup value in **/src/config/config.ts**
* To get signed URLs from bucket storage, use the signedUrls value in **/src/config/config.ts**
* $ npm run clean
* $ npm run compile
* You can watch for changes in your code with $ npm run watch

## How do I run the app? ##

### On mac ###
* Run with $ npm run nodemon
* Or with $ npm start

### On windows ###
* Same as mac, or...
* Run the app with node .dist/bin/www.js

### Go to http://localhost:3000 in a browser. ###
