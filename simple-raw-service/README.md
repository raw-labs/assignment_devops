# Simple RAW Web Service
![RAW Cube](https://raw-labs.com/wp-content/themes/raw-labs/img/cube.svg)

This simple RAWL WS counts successful VS failed invocations.

To run this app all you need to do is:
```
npm install
npm start
```
Then open your browser and go to `http://localhost:3000`. Available operations include the following:
* http://localhost:3000
  * Successful invocation
* http://localhost:3000/fail
  * Unsuccessful invocation
* http://localhost:3000/metrics
  * Summary of successful VS failed invocations

Building docker container for this app is easy, run this following command and you're done:
```
docker build --tag raw_simple_ws:<version> .
```
