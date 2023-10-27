# TaskManager
A simple task manager that allows for stable adding, completing, and deleting tasks. Add tasks with button on buttom right. 
Uses mongoDB and Node.js to handle response/requests between REST and the client. React handles user interface and functionality.

[Preview](https://github.com/johnny-t06/TaskManager/assets/115383099/65bfd5b1-8c19-45e7-81c9-d41ecee46c84)



## Getting Started
This program relies on a mongoose connection to a mongoDB server. Change mongoose connection in /api/server.js to preferred server

### Prerequisites
* [mongoDB](https://www.mongodb.com/docs/manual/installation/) - Shell and Compass GUI recommeneded
* [Node.js](https://nodejs.org/en/download)


### Installing
Place both api and client into the same folder.

To install the necessary packages and dependecies.

In /api/ and /client/
```
npm i
```

### Running the server
In two terminals, one in /api/ and one in /client/

Run:

```
npm start
```

Visit http://localhost:3000/ in a browser




