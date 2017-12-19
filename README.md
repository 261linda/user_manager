# web
microsoft- andela advanced web assessment
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)



This repository contains a simple demo API built with NodeJS.
The API is used to manage users in a MongoDB database.

### Development
This application was developed using [ExpressJS](http://expressjs.com/). MongoDB was used for persisting data with [Mongoose](https://mongoosejs.com/) as [ORM](https://en.wikipedia.org/wiki/Object-relational_mapping).

### Installation
* Start up your terminal (or Command Prompt on Windows OS).
* Ensure that you've `node` installed on your PC.
* Clone the repository by entering the command `git clone https://github.com/261Llinda/web.git` in the terminal.
* Navigate to the project folder using `cd UserManager` on your terminal (or command prompt)
* After cloning, install the application's dependencies with the command `npm install`.
* Create a `.env` file in your root directory as described in `.env.sample` file. Variables such as DB_URL (which must be a mongoDB URL) and PORT are defined in the .env file and it is essential you create this file before running the application.
```
PORT=3000
DB_URL='mongodb://localhost:27017/loginapp'
```
* After this, you can then start the server with the command: `npm start`.



### Author
**Oluchi orji

