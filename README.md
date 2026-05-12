# node-course

Node.js tutorial project (Net Ninja) containing two small examples:

- a basic HTTP server (`server.js`)
- an Express + EJS blog app using MongoDB and Mongoose (`app.js`)

## Features

- Minimal HTTP server demonstrating Node's built-in `http` and `fs` modules
- Blog app with routes, controllers, Mongoose models, and EJS views

## Prerequisites

- Node.js (recommended: current LTS)
- npm (comes with Node)
- MongoDB (local or Atlas) for the blog app

## Installation

1. Clone the repo and change into the project folder:

	 git clone <repo-url>
	 cd node-course

2. Install dependencies:

	 npm install

## Configuration

- The blog app in `app.js` connects to MongoDB. This repository includes a hard-coded connection string in `app.js` for tutorial/demo purposes.

## Running

- Basic HTTP example (serves plain HTML files):

	npm start

	This runs `server.js` and listens on port 3000.

- Express blog app with MongoDB:

	node app.js

	The app listens on port 3000 after a successful MongoDB connection.

	(Tip: use `npx nodemon app.js` for auto-restart during development.)

## Project Structure

- `server.js` — simple Node HTTP server example
- `app.js` — Express + Mongoose blog app entry
- `routes/` — Express route definitions (`blogRoutes.js`)
- `controllers/` — route handlers (`blogController.js`)
- `models/` — Mongoose models (`blog.js`)
- `views/` — EJS templates and partials
- `public/` — static assets (CSS)
- `package.json` — project metadata and dependencies

## Notes

- The repository contains tutorial/demo code.
