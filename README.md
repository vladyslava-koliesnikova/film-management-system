# Films Management Application 🎬

A web application for managing a film database, developed as a university project using Angular and TypeScript.

The application provides an interface for browsing, adding, and editing films, including information about directors, characters, and film rankings.

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 19.1.7.

## Features

- Browse and view film information
- Add and edit films
- Add, edit, and remove directors and characters
- Manage film details, including titles, release years, and IMDb IDs
- Edit AFI 1998 and AFI 2007 film rankings
- Form validation and protection against losing unsaved changes
- Communication with a backend REST API

## Technologies Used

- **Angular 19**
- **TypeScript**
- **Angular Material**
- **Angular Forms**
- **Angular Router**
- **RxJS**
- **REST API**

## Development Server

The application requires the provided Java backend server (`films-server.jar`) to be running.

To start a local Angular development server, run:

```bash
npm install
ng serve
```

Once the server is running, open your browser at `http://localhost:4200/`.

The application will automatically reload whenever you modify any of the source files.

## Building

To build the project, run:

```bash
ng build
```

This will compile the project and store the build artifacts in the `dist/` directory.

## Running Unit Tests

To execute unit tests with the [Karma](https://karma-runner.github.io) test runner, run:

```bash
ng test
```

## About the Project

This project was developed as part of a university course focused on modern web application development.

It demonstrates working with Angular components, forms, REST API integration, routing, and managing complex data relationships between films, directors, and characters.
