# Social Network API

## Description

Social Network API built using Mongoose and Mongo DB

## Table of Contents

- [Purpose](#purpose)
- [Installation](#installation)
- [Steps](#steps)
- [Credits](#credits)

## Purpose

This project is for anyone who wants a back-end for their social network site

## Installation

To install: clone this project on to your local machine.

## Steps

### Step 1:
run `npm install` and install all the dependencies

### Step 2: 
run `npm start` to start the server

### Step 3: 
use Insomnia core to create, find, update, and delete users and thoughts, and add and delete reactions and friends

### Endpoints to use:
* http://localhost:3001/api/users (find all users and create a new one)
  * Use JSON: { "username": "your username", "email": "your email" }

* http://localhost:3001/api/users/:id (use to find, update or delete a particular user)

* http://localhost:3001/api/user/:userId/friends/:friendsId (to add and remove a friend)

* http://localhost:3001/api/thoughts (find all thoughts and create a new one)
  * Use JSON: { "thoughtText": "your thought", "username": "username of someone creating the thought" }

* http://localhost:3001/api/thoughts/:id (use to find, update, or ddelete the thought)

* http://localhost:3001/api/thougts/:thoughtsId/reactions (use to add a reaction to the thought)
  * Use JSON: { "reactionBody": "reaction text", "username": "username of someone creating the reaction" }

* http://localhost:3001/api/thoughts/:thoughtsId/reactions/:reactionsId (use to delete a reaction from a thought)

### Example Screenshot:

![Example](/images/Screenshot 2021-03-07 153418.png)

## Credits

Created by: [irina256](https://github.com/irina256)
