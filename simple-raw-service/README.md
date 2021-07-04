# Simple RAW Web Service
![RAW Kubernetes](https://raw-labs.com/wp-content/themes/raw-labs/img/security.svg)

This simple RAW Labs service counts successful VS failed invocations.

To run this app all you need to do is:
```
npm install
npm start
```
Then open your browser and go to `http://localhost:3000`. Available operations include the following:
<table style="font-family: Arial, Helvetica, sans-serif;border-collapse: collapse;width: 100%; color: white">
<thead style="border: 1px solid #ddd;padding: 8px;padding-top: 12px;padding-bottom: 12px; text-align: left; background-color: #f35656;color: white;"><tr style="color: white; font-weight: bold"><td>Operation</td><td>Description</td></tr></thead>
<tbody>
<tr><td style="font-style: italic">/</td><td>Successful invocation</td></tr>
<tr><td style="font-style: italic">/fail/</td><td>Unsuccessful invocation</td></tr>
<tr><td style="font-style: italic">/metrics/</td><td>Summary of successful VS failed invocations</td></tr>
</tbody>
</table>


Building docker container for this app is easy, run this following command and you're done:
```
docker build --tag raw_simple_ws:<version> .
```
