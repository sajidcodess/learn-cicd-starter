![pass test badge](https://github.com/sajidcodesdotcom/learn-cicd-starter/actions/workflows/ci.yml/badge.svg)

# learn-cicd-starter (Notely)

This repo contains the starter code for the "Notely" application for the "Learn CICD" course on [Boot.dev](https://boot.dev).

## Local Development

Make sure you're on Go version 1.22+.

Create a `.env` file in the root of the project with the following contents:

```bash
PORT="8080"
```

Run the server: You can also directly go run without creating executable.

```bash
go build -o notely && ./notely
```

_This starts the server in non-database mode._ It will serve a simple webpage at, the 8080 is the PORT added in .env file `http://localhost:8080`.

You do _not_ need to set up a database or any interactivity on the webpage yet. Instructions for that will come later in the course!

thank you.
