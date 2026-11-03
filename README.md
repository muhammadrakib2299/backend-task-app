# Backend Task App

A task notes app: a Node.js + Express + EJS server that creates, views and renames tasks saved as text files.

## Features

- Create a task from a title and details. It is saved as `files/<Title>.txt`, with spaces removed from the title.
- Home page that lists every file in `files/` as a task card
- "Read More" page that shows a task's contents
- "Edit file name" form that renames a task's file
- Pages rendered server-side with EJS and styled with Tailwind CSS (browser CDN build)

## Built with

Node.js, Express 5, EJS, Node's `fs` module, Tailwind CSS (CDN).

## What I practised

- Express routing with route params (`/file/:filename`) and form POSTs (`express.urlencoded`)
- Server-side rendering with EJS templates and passing data into views
- Reading, writing and renaming files with Node's `fs` callbacks

## Run locally

```bash
npm install
node index.js
```

Open http://localhost:3000. Tasks are stored in the `files/` folder, which must exist next to `index.js`.
