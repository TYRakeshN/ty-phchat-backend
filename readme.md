# About

This is a basic application to domonstarte the chatting.

## Installation

Clone the repository and use the following command to install the dependencies.

```bash
npm install
```

## Usage

```bash
npm start
```
# Get started 

## Register User
```  
https://ty-chat-app.herokuapp.com/register 
method: post
```
## User Login
```
https://ty-chat-app.herokuapp.com/users/login
method: post
```
## Get Users
```
https://ty-chat-app.herokuapp.com/users
method: get
headers: authorization => Bearer token
```
## Get Messages
```
https://ty-chat-app.herokuapp.com/messages?sender=senderID&receiver=receiverID
method: get
headers: authorization => Bearer token
```
## Send Message
```
https://ty-chat-app.herokuapp.com/messages
method: post
headers: authorization => Bearer token
```
