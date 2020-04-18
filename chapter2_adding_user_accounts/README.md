# Chapter 2.  Adding User Accounts

“The chat application we built in the previous chapter focused on high performance transmission of messages from the clients to the server and back again. However, the way things stand, our users have no way of knowing who they would be talking to. One solution to this problem is building some kind of sign-up and login functionality and letting our users create accounts and authenticate themselves before they can open the chat page.”

Excerpt From: “Go Programming Blueprints Second Edition”.

## Getting Started

Adding missing modules
```go mod tidy```

Build server
```go build -o chat````

Run server
```./chat````

## Dependencies
- github.com/gorilla/websocket
