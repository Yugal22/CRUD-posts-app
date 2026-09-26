
# CRUD Posts App

A full-stack web application for creating, viewing, editing, and deleting posts — built as a hands-on project to practice CRUD operations with Node.js and Express.

🔗 **Live demo:** -  https://crud-posts-app-eqvs.onrender.com/posts

## Features

- 📝 Create new posts with a username and content
- 📋 View all posts on a single feed-style page
- 🔍 View a single post in detail
- ✏️ Edit existing posts
- 🗑️ Delete posts
- 🎨 Clean, responsive UI styled with custom CSS

## Tech Stack

- **Backend:** Node.js, Express.js
- **Templating:** EJS
- **Other tools:** `method-override` (for PUT/DELETE support in HTML forms), `uuid` (for unique post IDs)
- **Frontend:** HTML, CSS

## Routes

| Method | Route             | Description              |
|--------|-------------------|--------------------------|
| GET    | `/posts`          | View all posts           |
| GET    | `/posts/new`      | Form to create a new post|
| POST   | `/posts`          | Create a new post        |
| GET    | `/posts/:id`      | View a single post       |
| GET    | `/posts/:id/edit` | Form to edit a post      |
| PATCH  | `/posts/:id`      | Update a post            |
| DELETE | `/posts/:id`      | Delete a post            |

## Notes

This project stores posts in memory (not a database), so data resets whenever the server restarts. It was built primarily as a learning exercise to practice full CRUD functionality, Express routing, and EJS templating.
