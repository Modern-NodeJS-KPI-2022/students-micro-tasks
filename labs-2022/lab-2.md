# Lab 2

## Goals
- Make an acquaintance with native http api in NodeJS
- find difference between commonjs/esm
- find out what is that strange thing called `URL`

## Task
Build small http server with router without using any framework. Use ESM modules for project.
Server should include simple router, write it yourself. Please add 3-6 routes.

### Requirements
- change default loader to ECMAScript module loader.
- support different HTTP Methods (POST, GET, OPTIONS) for one route
- support 2+ different content types (json, xml, formdata, urlencode)
- follow specification for JSON: https://jsonapi.org/
- handle graceful shutdown
## Questions
- why we have separate http and https?
- Is it good idea to parse urls with REGEX?
## Links
- https://nodejs.org/api/packages.html#determining-module-system
- https://nodejs.org/api/http.html#class-httpserver
- https://nodejs.org/api/https.html#class-httpserver
- https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods
- https://nodejs.org/api/url.html
- https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Content-Type
- https://developer.mozilla.org/en-US/docs/Web/API/FormData
- graceful shutdown: https://www.youtube.com/watch?v=ZstnowFeCe0
- Bonus: 
  - https://en.wikipedia.org/wiki/HATEOAS
  - https://jsonapi.org/
