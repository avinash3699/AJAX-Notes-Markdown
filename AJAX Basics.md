# AJAX

## Basics


*[AJAX - Asynchronous JavaScript And XML.](https://developer.mozilla.org/en-US/docs/Web/Guide/AJAX)*

Although X in Ajax stands for XML, JSON is preferred over XML nowadays because of its many advantages such as being a part of JavaScript, thus being lighter in size. Both JSON and XML are used for packaging information in the Ajax model.

AJAX is *not a programming language* but a *technology* that just uses a combination of:
1. A browser built-in XMLHttpRequest object (to request data from a web server)
2. JavaScript and HTML DOM (to display or use the data)

AJAX allows web pages to be updated *asynchronously* by exchanging data with a web server behind the scenes. This means that it is possible to update parts of a web page, without reloading the whole page.

___

## Architecture
![Architecture](https://static.javatpoint.com/images/ajax/howajaxworks.png)

1. User sends a request from the UI and a javascript call goes to XMLHttpRequest object.
2. HTTP Request is sent to the server by XMLHttpRequest object.
3. Server interacts with the database using JSP, PHP, Servlet, ASP.net etc.
4. Data is retrieved.
5. Server sends XML data or JSON data to the XMLHttpRequest callback function.
6. HTML and CSS data is displayed on the browser.

___ 

## Some Famous Applications using AJAX

1. Google Maps
2. Gmail
3. Youtube
4. Google Suggest

___

## Practical Uses For AJAX

1. Login Forms
2. Auto-Complete
3. Voting and Rating
4. Updating With User Content
5. Form Submission & Validation
6. Chat Rooms And Instant Messaging
7. Slicker UIs
8. Building Tabbed Content

___