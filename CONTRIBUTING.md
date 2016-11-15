# Contributing

The aim of this project is to allow users to provide *a collection of our open source projects, tools and best practices*.
Contributions should be aimed towards this and / or improve the development workflow.


## Guidelines

### Pull Requests

For new additions or changes to this project, create a branch and submit a Pull Request.
Only add/change 1 thing per Pull Request.


## Scripts

Development requires [Node.js](http://nodejs.org/) and [npm](https://npmjs.org/).

After installing dependencies (run `npm install`) the following scripts are available:

`npm run ...` | Description
---|---
`build` | Format index HTML page and copy readme to `dist/`.
`build:index` | Formats the readme as html page written to `dist/index.html`.
`build:readme` | Copies the readme to `dist/README.md`.
`start` | Starts a server on `http://localhost:6736` ("open" in T9).