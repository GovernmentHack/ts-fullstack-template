# Template TS Express Server

A template mono-repo full-stack Typescript project that includes a debugging environemnt for VSCode, and dockerized production output.

## Commands

### Development

`npm run watch`

* Runs the server while watching for node and TS changes.

`npm run test`

* Runs all tests using Jest.

### Building

`npm run build`

* Cleans the compiled files and builds a fresh production build.

### Running

`npm run start`

* Runs the compiled JS project.

`docker-compose up`

* Will build a production build docker container and start it.
