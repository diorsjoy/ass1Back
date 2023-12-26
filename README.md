
# Login and SignUp System with User Authentication

This project is a straightforward implementation of a user authentication system using Node.js, Express.js, and MongoDB. It provides features such as user registration, login, password hashing using bcrypt, and storage of user data in a MongoDB database.

## Prerequisites

Before you begin, make sure you have the following installed on your machine:

- Node.js
- npm (Node Package Manager)
- MongoDB

## Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/diorsjoy/ass1Back.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd login-signup-system
   ```

3. **Install dependencies:**

   ```bash
   npm install
   ```

4. **Set up your MongoDB database:**

   - Create a MongoDB database.
   - Update the `config.js` file in the `src` directory with your database URL.

5. **Run the application:**

   ```bash
   nodemon src/index.js
   ```

   The server will start on [http://localhost:3000](http://localhost:5000) by default.
   If you want to use a different port, simply include it in the command:

 ```bash
   nodemon src/index.js --port=YOUR_DESIRED_PORT
 
## Project Structure

- `src/index.js`: Main server file.
- `src/config.js`: Manages the configuration settings for MongoDB connection.
- `views`: Contains EJS templates for rendering HTML.
- `public`: Static assets (CSS, images, etc.).

## Dependencies

- [Express](https://expressjs.com/): Fast, unopinionated, minimalist web framework for Node.js.
- [Mongoose](https://mongoosejs.com/): Elegant MongoDB object modeling for Node.js.
- [bcrypt](https://www.npmjs.com/package/bcrypt): A library to help you hash passwords.
- [EJS](https://ejs.co/): Embedded JavaScript templating.

## Contributing

If you'd like to contribute to this project, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

Feel free to adjust any part of it according to your preferences!
