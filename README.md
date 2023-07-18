<h1 align=center>MERN Stack CRUD App</h1>
A simple yet powerful CRUD (Create, Read, Update, Delete) application built using the MERN (MongoDB, Express, React, Node.js) stack. This application allows you to manage users, create new users, edit their information, and delete them. It's a perfect starting point for understanding the basics of MERN stack development and building scalable applications.

## Features

- Create new users with their details
- View a list of all existing users
- Edit user information easily
- Delete users from the system
- Interactive and user-friendly interface

## Tech Stack

This project utilizes the following technologies and libraries:

- Frontend: React.js for building the user interface.
- Backend: Node.js and Express.js for handling server-side logic.
- Database: MongoDB for data storage.
- Mongoose: An elegant MongoDB object modeling library for Node.js.
- Axios: A promise-based HTTP client for making API requests.
- Cors: Middleware for enabling cross-origin resource sharing.
- Devmon: A development monitoring tool for Node.js.


## Installation

To run this application locally, follow these steps:

1. Clone the repository: `git clone https://github.com/Aminizle/Crud-app.git`
2. Change into the project directory: `cd mern-stack-crud-app`
3. Install the dependencies for the server: `npm install`
4. Change into the client directory: `cd client`
5. Install the dependencies for the client: `npm install`
6. Go back to the root directory: `cd ..`
7. Run the server and client concurrently: `npm run dev`

Your MERN Stack CRUD App will now be running locally at `http://localhost:3000/`.

## Usage

Once the application is up and running, follow these steps:

1. Open your web browser and go to `http://localhost:3000/`
2. You will see a list of existing users.
3. To add a new user, click on the "Add User" button and fill in the required details.
4. To edit a user, click on the "Edit" button next to the user's name and make the necessary changes.
5. To delete a user, click on the "Delete" button next to the user's name.

## API Endpoints

### Get All Users

- `GET /api/users`: Retrieves all users from the database.

### Add a New User

- `POST /api/users`: Creates a new user in the database. The user data should be sent in the request body.

### Get a Specific User

- `GET /api/users/:id`: Retrieves a specific user by ID from the database.

### Update a User

- `PUT /api/users/:id`: Updates an existing user's information in the database. The updated user data should be sent in the request body.

### Delete a User

- `DELETE /api/users/:id`: Removes a user from the database using their ID.

Feel free to use these API endpoints to interact with the MERN Stack CRUD App and perform various operations on user data. If you have implemented custom API endpoints, they will be available alongside the standard CRUD operations.

## Contributing

Contributions to the MERN Stack CRUD App are always welcome. If you want to contribute, follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b my-feature-branch`
3. Make your changes and commit them: `git commit -m 'Add some feature'`
4. Push your changes to your forked repository: `git push origin my-feature-branch`
5. Submit a pull request, explaining the changes you made and why they should be merged.

## License

This project is licensed under the [MIT License](LICENSE).

---

<p align="center">Made with ❤ by Ameen</p>

---
