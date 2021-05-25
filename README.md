Difference between HTTP and XMLHTTP requests

HttpRequest is a server side object that represents a request to the server.

XMLHttpRequest in a standard javascript object that allows you to make HTTP Requests from the
browser in javascript.

In summary - one works in the browser, the other in the web server. They also have completely
different roles. XMLHttpRequest is for fetching web resources within the browser. HttpRequest

represents an incoming request.

The XMLHttpRequest object can be used to request data from a web server.
● Update a web page without reloading the page
● Request data from a server - after the page has loaded
● Receive data from a server - after the page has loaded
● Send data to a server - in the background

Difference between type “SUBMIT” vs type “BUTTON”

<input type="button"> can be used anywhere, not just within form and they do not submit form if
they are in one. Much better suited with Javascript.

<input type="submit"> should be used in forms only and they will send a request (either GET or
POST) to specified URL. They should not be put in any HTML place
