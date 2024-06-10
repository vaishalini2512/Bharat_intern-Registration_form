# Registration Form using HTML, CSS, Node.js, and MongoDB

This project is a simple registration form built with HTML, CSS, Node.js, and MongoDB. It demonstrates how to create a basic user registration system with form handling and data storage in a MongoDB database.

## Project Structure
Registration-form/
│
├── node_modules/
├── public/
│ ├── css/
│ │ └── styles.css
│ ├── js/
│ └── index.html
├── models/
│ └── User.js
├── app.js
├── package.json
└── package-lock.json

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js installed on your machine
- MongoDB installed and running

## Installation

1. **Clone the repository:**

    ```sh
    git clone https://github.com/vaishalini2512/Bharat_intern-Registration_form
    cd registration-form
    ```

2. **Install the dependencies:**

    ```sh
    npm install
    ```

## Running the Application

1. **Start the MongoDB server:**

    If MongoDB is installed locally, you can start it with:

    ```sh
    mongod
    ```

2. **Start the Node.js server:**

    ```sh
    node app.js
    ```

    You should see the following output indicating the server is running:

    ```sh
    Server is running on http://localhost:3000
    ```

3. **Open a web browser and navigate to:**

    ```
    http://localhost:3000
    ```

    You should see the registration form.

## Usage

1. **Fill out the registration form:**

    Enter a username, email, and password, then click the "Register" button.

2. **Form Submission:**

    The form data is sent to the server and saved in the MongoDB database. If the registration is successful, you will see a "Registration successful" message. If there is an error (e.g., a duplicate username or email), an error message will be displayed.

## Project Details

### HTML

The `public/index.html` file contains the registration form with fields for Username, Email, and Password.

### CSS

The `public/css/styles.css` file contains basic styles for the registration form.

### Node.js and Express

The `app.js` file sets up an Express server, connects to MongoDB, and handles form submissions.

### MongoDB and Mongoose

The `models/User.js` file defines a Mongoose model for storing user data in the MongoDB database.

## Troubleshooting

- Ensure MongoDB is running and accessible.
- Check the connection string in `mongoose.connect` in `app.js`.
- Check the server logs in your terminal for any error messages.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open-source and available under the [MIT License](LICENSE).

