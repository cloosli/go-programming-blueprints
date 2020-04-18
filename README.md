# Go Programming Blueprints Second Edition

## What this book covers

### Chapter 1
Chat Application with Web Sockets, shows how to build a complete web application that allows multiple people to have a real-time conversation right in their web browser. We will see how the NET/HTTP package let us serve HTML pages as well as connect to the client's browser with web sockets.

### Chapter 2
Adding User Accounts, shows how to add OAuth to our chat application so that we can keep track of who is saying what, but let them log in using Google, Facebook, or GitHub.

### Chapter 3
Three Ways to Implement Profile Pictures, explains how to add profile pictures to the chat application taken from either the authentication service, the Gravitar.com web service, or by allowing users to upload their own picture from their hard drive.

### Chapter 4
Command-Line Tools to Find Domain Names, explores how easy building command-line tools is in Go and puts those skills to use to tackle the problem of finding the perfect domain name for our chat application. It also explores how easy Go makes it to utilize the standard-in and standard-out pipes to produce some pretty powerful composable tools.

### Chapter 5
Building Distributed Systems and Working with Flexible Data, explains how to prepare for the future of democracy by building a highly-scalable Twitter polling and vote counting engine powered by NSQ and MongoDB.

### Chapter 6
Exposing Data and Functionality through a RESTful Data Web Service API, looks at how to expose the ### capabilities w built in Chapter 5, Building Distributed Systems and Working with Flexible Data, through a JSON web service, specifically how the wrapping http.HandlerFunc functions give us a powerful pipeline pattern.

### Chapter 7
Random Recommendations Web Service, shows how to consume the Google Places API to generate a location-based random recommendations API that represents a fun way to explore any area. It also explores why it's important to keep internal data structures private, controlling the public view into the same data, as well as how to implement enumerators in Go.

### Chapter 8
Filesystem Backup, helps to build a simple but powerful filesystem backup tool for our code projects and explore interacting with the filesystem using the OS  package from the Go standard library. It also looks at how Go's interfaces allow simple abstractions to yield powerful results.

### Chapter 9
Building a Q&A Application for Google App Engine, shows how to build applications that can be deployed to Google's infrastructure and run at high scale with little to no operational duties for us. The project we build utilizes some of the cloud services available on Google App Engine, including the Google Cloud Datastore—a highly available and extremely fast schema-less data storage option.

### Chapter 10
Micro-services in Go with the Go Kit Framework, explores a modern software architecture paradigm whereby large monolithic applications are broken down into discrete services with a singular focus. The services run independently of each other, allowing them to be individually scaled to meet demand. Go Kit is a software framework that addresses some of the challenges of a microservice architecture while remaining agnostic to the implementation details.

### Chapter 11
Deploying Go Applications Using Docker, looks at how simple it is to build Docker images to package and deploy the application we built in Chapter 9, Building a Q&A Application for Google App Engine. We will write a Dockerfile that describes the image, and use the Docker tools to build the image, which we will then deploy to the Digital Ocean cloud.
