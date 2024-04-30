# Blog API Application

This is a simple Express.js application for managing blog posts. It consists of a client-server architecture where the server provides API endpoints for creating, reading, updating, and deleting blog posts. The client, built using Express.js and EJS, interacts with these endpoints to render the user interface and handle user actions.

## Prerequisites

Before running the application, make sure you have the following installed:

- Node.js
- npm (Node Package Manager)

## Installation

1. Clone this repository to your local machine:

```bash
git clone https://github.com/akinmertbur/Blog-API-Project.git
```

2. Navigate to the project directory:

```bash
cd Blog-API-Project
```

3. Install dependencies:

```bash
npm install
```

## Usage

1. Start the server:

```bash
npm start
```

2. Open your web browser and navigate to http://localhost:3000 to view the blog.

3. You can create new posts, edit existing posts, and delete posts using the provided interface.

## API Endpoints

* `GET /posts`: Get all posts.
* `GET /posts/:id`: Get a specific post by ID.
* `POST /posts`: Create a new post.
* `PATCH /posts/:id`: Update a post.
* `DELETE /posts/:id`: Delete a post.

## Folder Structure
* `public/`: Static assets (CSS, client-side JavaScript).
* `views/`: EJS templates for rendering HTML pages.
* `server.js`: Express server setup and routes.
* `index.js`: API endpoints and in-memory data store.

## Technologies Used
* Express.js: Web framework for Node.js.
* EJS: Embedded JavaScript templating.
* Axios: Promise-based HTTP client for making requests.
* Body-parser: Middleware for parsing incoming request bodies.

## License
This project is licensed under the `MIT License`.
