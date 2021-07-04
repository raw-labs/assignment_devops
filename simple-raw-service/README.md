# Simple RAW Web Service
![RAW Cube](https://raw-labs.com/wp-content/themes/raw-labs/img/cube.svg)

This simple RAW Labs service counts successful VS failed invocations.

To run this app all you need to do is:
```
npm install
npm start
```
Then open your browser and go to `http://localhost:3000`. Available operations include the following:
* / Successful invocation
* fail/ Unsuccessful invocation
* metrics/ Summary of successful VS failed invocations

Building docker container for this app is easy, run this following command and you're done:
```
docker build --tag raw_simple_ws:<version> .
```
