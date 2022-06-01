# AJAX - The XMLHttpRequest Object

[XMLHttpRequest objects](https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest) are used to interact with servers. You can retrieve data from a URL without having to do a full page refresh. This enables a Web page to update just part of a page without disrupting what the user is doing.

All modern browsers support the XMLHttpRequest object.

___

## Create an XMLHttpRequest Object

```
Syntax/Constructor

variable = new XMLHttpRequest();
```
```javascript
var XMLHttpRequestObject = new XMLHttpRequest();
```

Refer [XMLHttpRequest Methods](https://www.tutorialspoint.com/ajax/what_is_xmlhttprequest.htm) for *XMLHttpRequest Methods and XMLHttpRequest Properties*

___

### Access Across Domains

For security reasons, modern browsers do not allow access across domains.

This means that both the web page and the XML file it tries to load, must be located on the same server.