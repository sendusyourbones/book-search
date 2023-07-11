# Book Search Engine

## Description

This site enables users to search for books to see their titles, descriptions, authors, and images, as well as links to navigate to entries for the books on Google Books. Users are not required to have an account in order to search for books and view results, but they have the ability to create an account if they want to save any books to a personal collection of books they are interested in. 

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

This application requires a number of packages (see [Credits](#credits) below for more information). To install these packages, clone the repo, `cd` into it, then run the command `npm i`.

## Usage

View the [deployed application](https://radiant-mountain-18171-86736d015c42.herokuapp.com/) here.

Instructions for using the application:
- If you do not have an account and wish to save books, first create an account:
    - Click "Login/Sign Up" at the top-right corner
    - Click the "Sign Up" tab in the modal that appears
    - Enter a username, email, and password and then click "Submit"
- If you have an account and wish to log in, click "Login/Sign Up" and enter your login credentials
- The Home page contains a search bar to look up books. Enter your search term and click "Submit Search". Note you do not have to be logged in to search but you do have to be logged in to save books.
    - Click on "View book on Google Books" to navigate to the Google Books webpage for the book.
    - If you are logged in, click "Save this Book!" to save the book to your account.
- If you are logged in, click "See Your Books" in the navigation menu to view your saved books.
    - Click "Delete this Book!" to remove a book from your saved books.
- You will be automatically logged out after a period of inactivity, or you can click "Logout" in the top-right corner to log out

![Screenshot of application showing search bar and search results](./screenshot.jpg)

## Credits

Starter code was provided by the UC Berkeley Coding Boot Camp (see first commit to view this starter code).

The following packages are used in this application:
- Back-end:
    - [express](https://www.npmjs.com/package/express) to handle API routing
    - [bcrypt](https://www.npmjs.com/package/bcrypt) to hash and verify user passwords
    - [apollo-server-express](https://www.npmjs.com/package/apollo-server-express) to integrate Express with Apollo Server
    - [graphql](https://graphql.org/) to handle APIs and querying
    - [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken) to manage JSON Web Tokens
    - [mongoose](https://www.npmjs.com/package/mongoose) to interact with the MongoDB database
- Front-end:
    - [@apollo/client](https://www.apollographql.com/docs/react/) to manage data with GraphQL
    - [bootstrap](https://getbootstrap.com/) for styling
    - [graphql](https://graphql.org/) to handle APIs and querying
    - [jwt-decode](https://www.npmjs.com/package/jwt-decode) to decode JSON Web Tokens
    - [react](https://react.dev/) / [react-bootstrap](https://react-bootstrap.netlify.app/) / [react-router-dom](https://www.npmjs.com/package/react-router-dom) / [react-scripts](https://www.npmjs.com/package/react-scripts) to handle all things React

## License

MIT License