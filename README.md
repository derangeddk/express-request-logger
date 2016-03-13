express-request-logger
======================

This is the request logger used by deranged in a bunch of projects that use express.
It is a piece of middleware that can be quickly dropped in:

```js
var requestLogging = require("deranged-express-request-logger");

app.use(requestLogging);
```

It logs the contents of incoming requests and the resulting response.

Right now it uses console.log, but this should be made modifiable in the future.
