# JS_01
How Web works
The client requests a service
we open a browser (client)
we hit a url for example: www.google.com (Uniform Resource Location)
the client sends a message to the server asks for a resource
Resources can be - web pages, images, video files, fonts, stylesheets
This message is formatted based on a protocol called HTTP
In other words, HTTP (Hypertext transfer protocol) is a standard structure (or protocol) that clients and servers use to communicate over internet.
With an HTTP request, the client communicates to the server, what it is looking for
The server provides the service
The server listens to the message
It figures out what the client is asking
It sends a message back to the client
This message is called an HTTP response
The client gets back a message
for example, the response can be an html page
<!DOCTYPE html>
<html>
...
	<link rel="stylesheet" href="styles.css">
...
  <img class="footer-sub__logo" src="<https://unsplash.com/assets/core/logo-black-df2168ed0c378fa5506b1816e75eb379d06cfcd0af01e07a2eb813ae9b5d7405.svg>">
...
</html>
- browser constructs a DOM in case its an HTML document (Document Object Model)
- browser discovers references to other resources in the html document like images, stylesheets, font etc.
- For each resource the browser sends separate HTTP requests to same or other servers to fetch that resource
- These requests can be parallel
- Once the browser has all the necessary resources, it renders the HTML document (or displays it)
Javascript is one of the most popular and widely used programming languages. 
A program is something like the language of a computer which a computer understands. There are many different programming languages like C, Java, Python, Javascript, etc. Through Program, we can tell computers which task we want to perform. In our daily life, we use applications to perform some tasks like VLC for watching videos, Excel Sheet for documents, Skype for video calling, etc.

Every application in its core is a computer program, which is giving a nice beautiful interface through which we are communicating with the computers.
