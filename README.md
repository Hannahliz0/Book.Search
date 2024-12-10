# Book Search Engine

## Description
The Book Search Engine is a web application that allows users to search for books using the Google Books API and manage their saved book lists. This project refactors an existing RESTful API implementation to use a GraphQL API powered by Apollo Server. Built with the MERN stack (MongoDB, Express.js, React, Node.js), the app enables users to search for books, create accounts, log in, save their favorite books, and manage saved books seamlessly.

## Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Contributors](#contributors)
* [Tests](#tests)
* [Questions](#questions)

## Installation
1. Clone the repository.
2. Navigate to the project directory.
3. Install the required dependencies
4. Set up the environment variables for MongoDB Atlas and other configurations.
5. Run the application in development mode.

## Usage
Once the application is running, access it through your web browser. The following features are available:

1. Search for Books:
    - Enter a search term in the input field and click the submit button.
    - View search results, including a book’s title, author, description, image, and a link to the book on the Google Books site.

2. User Authentication:
    - Use the Login/Signup modal to create an account or log in.
    - Toggle between Login and Signup modes.

3. Save Books:
    - Logged-in users can save books to their account.
    - Saved books include their title, author, description, image, and a link to the book.

4. View Saved Books:
    - Access your saved books through the corresponding menu option.
    - Remove books from your list if desired.

5. Logout:
    - Log out to return to the default view with Search for Books and Login/Signup options.

 ## Contributing
 - Hannah Schmidt, Student
 - Sabrin Othman, Student   

 ## Test


1. Search for Books:
    - Enter a search term and verify search results.
    - Confirm that book details (title, author, description, etc.) match expectations.

2. User Authentication:
    - Test account creation with valid credentials.
    - Verify successful login with existing accounts.
    - Ensure invalid credentials display appropriate error messages.

3. Saving and Viewing Books:
    - Save a book and verify its appearance in the saved books list.
    - Confirm saved book details are accurate.
    - Remove a book from the saved list and ensure it is deleted.

4. Logout Functionality:
    - Test that logout works and resets the UI to its default state.

## Questions
If you have any questions, please contact me at hnbright57@gmail.com, find me on GitHub at hannahliz0, or visit my GitHub profile at https://github.com/Hannahliz0.