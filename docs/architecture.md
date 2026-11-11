# Architecture

How the main parts connect. Read this before adding a module or changing how
parts talk to each other. Describe the shape, not every file.

## Parts

- Web Frontend: single-page interface powered by Vite and styled with Tailwind CSS, hosting pages for Login, Task List, and Administration.
- State / Auth Layer: handles user authentication, session state, and permissions (User vs Admin).
- Task Management Layer: handles CRUD operations on to-do items.

## How they connect

- Frontend UI components interact with the Auth and Task service modules via clean function interfaces or HTTP client requests.

## Data

- User profiles, role definitions (Standard User, Administrator), and user task lists.

## What does not belong here

How to start the project (docs/dev-environment.md) and why a choice was made
(docs/decisions.md).
