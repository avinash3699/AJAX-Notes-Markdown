# AJAX Request

The XMLHttpRequest object is used to exchange data with a server.

## Send a Request To a Server

The [open()](https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/open) and [send()](https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/send) methods of the XMLHttpRequest object are used to send a request to a server

```
->open()

open() is used to initialize a newly-created request, or re-initialize an existing one.

Syntax

open(method, url)
open(method, url, async)
open(method, url, async, user)
open(method, url, async, user, password)

method and url are the required parameters. Others are optional. 
```

```
->send()

send() is used to send the request to the server.

Syntax

send()
send(body)

body is a optional parameter which is set to a default of 'null'
```

```javascript
//get request
var XMLHttpRequestObject = new XMLHttpRequest();

XMLHttpRequestObject.open("GET", "demo.php", true);
XMLHttpRequestObject.send();
```

```javascript
//post request
var XMLHttpRequestObject = new XMLHttpRequest();

XMLHttpRequestObject.open("POST", "demo.php", true);
XMLHttpRequestObject.send();
```

Note: Calling the open() method for an already active request (one for which open() has already been called) is the equivalent of calling abort().