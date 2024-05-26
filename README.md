# PicHive

Pic Hive is a web application that allows users to register, login, create posts with images, and view a feed of all posts. It uses Express.js for the server, MongoDB for the database, Passport.js for authentication, and Multer for file uploads.

## Features

- User registration and login
- User profile management
- Create, view, and manage posts
- Image upload functionality

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose
- Passport.js
- Multer
- EJS (Embedded JavaScript templating)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/PicHive.git
    cd PicHive
    ```

2. Install the dependencies:
    ```bash
    npm install
    ```

3. Set up the environment variables:
    - Create a `.env` file in the root directory
    - Add the following environment variables:
        ```plaintext
        PORT=3000
        MONGODB_URI=your_mongodb_connection_string
        ```

4. Run the application:
    ```bash
    npm start
    ```

5. Open your browser and go to `http://localhost:3000`.

## Usage

1. **Register** a new account.
2. **Login** with your credentials.
3. **Create** a new post by uploading an image and adding a title and description.
4. View your profile to see all your posts.
5. View the feed to see all posts by all users.

## Project Structure

- `index.js`: Main server file, defines routes and middleware.
- `multer.js`: Configuration for Multer, handles file uploads.
- `users.js`: Mongoose schema and model for users.
- `post.js`: Mongoose schema and model for posts.
- `public/`: Directory for static files (e.g., uploaded images).
- `views/`: Directory for EJS templates.

## License

This project is licensed under the GNU General Public License v3.0. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Express.js](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [Passport.js](http://www.passportjs.org/)
- [Multer](https://github.com/expressjs/multer)
- [EJS](https://ejs.co/)

---


## Contributing

Contributions are welcome! Please open an issue or submit a pull request.
