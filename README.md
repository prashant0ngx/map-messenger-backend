# Map -Messenger - Backend Server.

Real-time live location tracking app in Flutter - Backend server

## Features and functionalities

- Real-time live location changing server side functionalities:
- - User location's coordinates changing in real-time and emit to other users within the room
- - Join and leave movement room
- - Notify other users when user join or left movement room
- - Retrieve current users within movement room
- Chat messages (send or receive text message by your colleague in real-time)
- Register user
- Login user
- Verifying account by email
- Send or resend OTP by email
- Expiring tokens after two hours
- Creating profile
- Create, delete or leave movement
- Generating, clearing or receiving notifications
- Accept or decline joining movement request

## Api & Demo
- API url: [https://map-messenger.onrender.com/](https://map-messenger.onrender.com/)




## API Documentation

You can find api documentation made with swagger here:

```bash
https://map-messenger.onrender.com/api/v1/docs/
```

## Run locally

- Clone this repository

```
- Create `.env` file in the root folder and fill out all variables specified in `.env.example` file
- Run `npm install` to get all project dependencies
- Run the following command in your terminal to launch localhost server

```bash
npm start
```
- - Or 
```bash 
npm run dev
``` 
- - to launch localhost developement server on 3000 or the specified port
- There you go, now you should be able to test the app by typing `https://localhost:[YOUT_PORT]/api/v1/` in your browser or other apps that can help you to make restful api requests like Postman, Thunder client, SOAP or etc.
## Pre-requisites

- You should have the following to run this project locally:
- - Node JS
- - TypeScript
- - MongoDB
- - S3 Bucket
- - Email Service Provider (Ex: gmail, in order to be able to send emails using nodemailer).

### Technologies

- Socket.io
- TypeScript/Node JS/Express
- MongoDB
- Agenda
- AWS S3 Bucket
- Nodemailer
- Swagger

### Known issue


