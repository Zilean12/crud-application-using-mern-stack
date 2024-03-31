# User Management System (CRUD App) 🚀

## Description

Welcome to the User Management System! This is a dynamic web application designed to empower users to efficiently manage their skills and addresses. Crafted with React and powered by Axios for seamless HTTP requests to a robust backend server.

## Installation

Getting started is a breeze! Simply follow these steps:

1. **Clone the repository:** `git clone https://github.com/Zilean12/crud-application-using-mern-stack.git`
2. **Navigate to the project directory:** `cd repository`
3. **Install dependencies:** `npm install`
4. **To start the application for client:**
   Navigate to the client directory `cd client` and start the application with `npm start`
5. **To start the application for server:**
   Navigate to the server directory`cd server` and start the application with `npm start`
6. **Configure your MongoDB connection:**
   Update the `.env` file with your MongoDB connection string. You can use a local MongoDB server or a MongoDB Atlas cluster.

## Usage

Once installed, unleash the power of the User Management System with a single command: 


## Features

Experience a plethora of functionalities:

- Effortlessly add, update, and delete skills.
- Seamlessly update addresses, hobbies, skills, and phone numbers.

## Database Relationships

Unlock the intricacies of our MongoDB database relationships:

### One-to-One

Each user is intricately connected with a detail record. In MongoDB, this synergy is achieved through embedding the detail document within the user document.

### One-to-Many

Users boast multiple phone numbers, fostering a one-to-many relationship. MongoDB aptly handles this by embedding an array of phone number documents within the user document.

### Many-to-Many

Dive into the rich tapestry of user hobbies and skills! Users can indulge in multiple hobbies and skills, each associated with multiple users. MongoDB's array of references elegantly captures this many-to-many relationship.



## Usage

Once installed, unleash the power of the User Management System with a single command: 


## Features

Experience a plethora of functionalities:

- Effortlessly add, update, and delete skills.
- Seamlessly update addresses, hobbies, skills, and phone numbers.

## Database Relationships

Unlock the intricacies of our MongoDB database relationships:

## One-to-One

Each user in the system has a detail record associated with them. This is a one-to-one relationship. In MongoDB, this is typically modeled by embedding the detail document inside the user document.

## One-to-Many

Each user can have multiple phone numbers. This is a one-to-many relationship. In MongoDB, this is typically modeled by embedding an array of phone number documents inside the user document.

## Many-to-Many

Users can have multiple hobbies or skills, and each hobby or skill can be associated with multiple users. This is a many-to-many relationship. In MongoDB, this is typically modeled by using an array of references to the related documents. For example, each user document could have an array of references to the hobby documents that are associated with that user.

