# MERN Calendar

Calendar web application for adding, editing, deleting or listing other people's events. Developed using the MERN stack.

*API, CRUD, Auth system, JWT, Redux, Calendar.*

## Features
* User login and registration using JWT.
* Viewing calender in Month, Week, Day format.
* Adding and deleting events.
* Daily agenda highlighting meetings / events.

## Problem Statement

Build a Calendar web application with the help of MERN stack. To explore different modules and libraries for building a full stack website. To implement CRUD operation, Multer functions, database connection and other features.

## Motivation 

To explore features of MERN stack, such as

* Learning React
* Using React to build a project
* Developing a shared calender system so that employees in a company understand schedule of other employees
* Managing and updating multiple mongoDB databases

## Libraries used in Backend

* Bcrypt (for encrypting the passwords of users)
* Dotenv (for storing the connection url and other private credentials and global variables)
* Express (For routing)
* Mongoose (For database connection)
* Multer (for file upload)
* Path (For routing or redirecting)

## Libraries used in Frontend

* React
* Redux

## Starting 
  
### Pre-requirements

* [npm](https://www.npmjs.com/)
* [Mongo database](https://www.mongodb.com/)

### Installation 

Local installation:

$ cd mern-calendar

**Server setup:**
```
# Change directory to the server path
$ cd server

# Install dependencies
$ npm install

# set up you .env file
```

server **.env** file setup:

```shell
PORT=5000
MONGODB_CNN=mongodb://localhost/<database name>
JWT_SECRET_KEY=RANDOMKEY
```

**Client setup:**
```bash
# Go back to the project path
$ cd ..

# Change directory to the client path
$ cd client

# Install dependencies
$ npm install

# set up you .env file
```

client **.env** file setup:

```shell
REACT_APP_API_URL="http://localhost:5000/api"
```

## Deployment 

```bash
# Open terminal in project path and run
$ cd server
$ npm start


# Open another terminal in project path and run
$ cd client
$ npm start
```
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## Built with 

* [React](https://es.reactjs.org/) - Frontend framework
* [React Redux](https://react-redux.js.org/) - State management
* [Node.js](https://nodejs.org/) - Javascript runtime environment
* [Express.js](https://expressjs.com/) - Backend framework
* [MongoDB](https://www.mongodb.com/) - NoSQL database

## Future Scope

* Twilio service to incorporate OTP based authentication for login and registration services.
* Sending email alerts for events to user.
* Highlight urgent events in the calendar.
* Adding a 'Host Meeting' button to our event section allowing us to directly host meetings through this application.
* Add a yearly calendar.
* Hosting the application.

# Website Screenshots:
![image](https://user-images.githubusercontent.com/84176158/206458280-5a513759-85bf-4f4b-b101-a621cb6b78c7.png)
![1](https://user-images.githubusercontent.com/84176158/206458242-19534931-4cf7-4406-acf6-d2d06f77a3a3.png)
![2](https://user-images.githubusercontent.com/84176158/206458251-102de034-6825-4316-a51a-960ed7521e7c.png)
![3](https://user-images.githubusercontent.com/84176158/206458462-5c481944-bf75-49d2-a7f8-65e4fc8a4d05.png)
![4](https://user-images.githubusercontent.com/84176158/206458466-1b509429-5c71-46ec-a796-d3a059fb278f.png)
![5](https://user-images.githubusercontent.com/84176158/206458329-b24330af-d175-42d0-8db7-ece4db8d24ba.png)

---


