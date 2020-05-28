# CORS Proxy

This simple Node.js-based proxy allows your JavaScript application to call services that are hosted on a different domain and that don't support [CORS](http://en.wikipedia.org/wiki/Cross-origin_resource_sharing). 

Because the proxy is itself CORS-enabled, your application and the proxy don't have to be hosted on the same 
domain.

This proxy was tested with the Salesforce.com REST API, but it should work with other services as well.

## Installation

There are different options to get your own instance of the CORS proxy up and running:

```bash
yarn install
node server.js -website="http://google.com"
```
Just replace the http://google.com with what ever you want to proxy
