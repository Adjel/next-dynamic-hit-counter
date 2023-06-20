# Dynamic Hit Counter exercise

Once again, we're working on our hit counter!

This time, everything works swell when we run in development (`npm run dev`), but things don't quite work when we try to build for production (`npm run build` and then `npm run start`). The number of hits appears fixed in place, and doesn't increase when we refresh the page.

Your mission is to fix this bug!

## Running a development server

First, install the dependencies:

```bash
$ npm install
```

Then, start a local development server:

```bash
$ npm run dev
```

**Note:** Unlike create-react-app, we need to run the `dev` command, not `start`. The `start` command is used to run a _production_ server; we'll learn more about that later in the course.
