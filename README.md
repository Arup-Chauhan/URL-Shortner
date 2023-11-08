


# URL Shortener

A simple URL shortener web application built with Node.js, Express, EJS, and MongoDB.

## Project Structure

- `server.js`: Main server file for the Express application and route definitions.
- `Entities/shortUrl.js`: Mongoose schema for the short URL data model.
- `Layout/index.ejs`: EJS template for rendering the front-end view.
- `package.json`: Project metadata and dependencies.

- NOTE: For a non bootstrap version of the index file, an alternative file `index_without_bootstrap.ejs` is provided.

## Prerequisites

Before running the application, ensure you have the following installed:

- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)

## Installation

1. Clone this repository to your local machine.

2. Navigate to the project directory:

   ```bash
   cd URL-shortener
   ```

3. Install the required npm packages:

   ```bash
   npm install
   ```

## Configuration

- Open the `server.js` file and adjust the MongoDB connection URL (`mongodb://localhost/urlShortener`) to match your MongoDB setup.

## Running the Application

1. Start the server:

   ```bash
   npm run StartDev
   ```

   The application will run on `http://localhost:5000` (or the port you specify in `process.env.PORT`).

2. Access the URL shortener in your web browser:

   [http://localhost:5000/](http://localhost:5000/)

## Usage

- Visit the homepage to shorten URLs and view a list of shortened links.
