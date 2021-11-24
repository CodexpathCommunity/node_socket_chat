# PRO_CHAT_API

[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/CodexpathCommunity/Scalable_Modern_React_Architecture)

A professional chat api solution with Nodejs, Socket.io and MongoDB

## Prerequisites

Set up Mongodb on your machine [Installation guide written here](https://github.com/adeelibr/node-playground/blob/master/chapter-1-chat/guidelines/installing-mongo.md)
Install Node/NPM on your machine [Installation link here](https://nodejs.org/en/download/) (I am using Node version v12.18.0)

### To use this api code base you should understand the following

- [Create an express server](https://www.youtube.com/watch?v=t7-yuYFVG1Y&list=PLH6pGK5zEj9mO-yS9FjQ6xhJXUagoEgOh)
- [How to do API validations](https://www.youtube.com/watch?v=t-KGXLM0YlE&list=PLH6pGK5zEj9mO-yS9FjQ6xhJXUagoEgOh&index=3&t=2s)
- [MiddleWares](https://www.freecodecamp.org/news/introduction-to-mongoose-for-mongodb-d2a7aa593c57/)
- [JWT (JSON web tokens) authentication (decode/encode) - Login middleware](https://jwt.io/introduction)
- [Web socket class that handles events when a user disconnects, adds its identity, joins a chat room, wants to mute a chat room](https://socket.io/docs/v4/)
- [ mongoose operations for chat room & chat message database model](https://www.freecodecamp.org/news/introduction-to-mongoose-for-mongodb-d2a7aa593c57/)

### Api Endpoints

Initiate a chat between users
Create a message in chat room
See conversation for a chat room by its id
Mark an entire conversation as read (similar to Whatsapp)
Get recent conversation from all chats (similar to Facebook messenger)
