# Introduction
This is a small chat application using Web Sockets in Node.js. Every time a user submits the message in the form, it will get sent through a web socket connection to all connected clients. All of the chat messages will get appended to ul#chat.

## Running the App
Run the backend in terminal with the command node server.js. Next, open up two browser tabs with index.html with the Chrome Console open. You should see the chat application working!

## Dependencies
- ws