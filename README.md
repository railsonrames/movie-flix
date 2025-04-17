# Movieflix - Academic Netflix Clone in Angular

This project, **Movieflix**, is an academic clone of the popular streaming service Netflix. Developed as a proof of concept and for learning the Angular technology (version 19.2.8), Movieflix aims to replicate some of the functionalities and the interface of Netflix, offering a simulated movie and series viewing experience.

## Overview

The main goal of this project is to demonstrate the application of Angular concepts and features in building a modern and interactive web application. Movieflix will focus on presenting a catalog of content (simulated), allowing navigation between different sections, and displaying details of movies and series.

## User Interface Design

The Movieflix user interface was inspired by the Netflix design and prototyped using Figma. You can view the complete prototype here:

[![Link to Figma Prototype](https://img.shields.io/badge/Figma-Movieflix%20Prototype-blue?style=for-the-badge&logo=figma)](https://www.figma.com/proto/FSkHiMRTRa09CljCjXmedJ/P%C3%A1ginas-Hor%C3%A1cio?page-id=195%3A20&node-id=195-28&p=f&viewport=93%2C29%2C0.29&t=BZ0d8wCey2K8NzLL-1&scaling=contain&content-scaling=fixed)

Access the prototype to get a detailed view of the layout, navigation, and visual elements planned for Movieflix.

## Backend

This Angular project is intended to consume data and functionalities from a backend developed in Java. The backend repository can be found here:

[Java Backend Repository](https://github.com/renanlessa/miniature-fortnight/tree/main)

While the primary focus of this repository is the Angular frontend, integration with the Java backend is a future goal to demonstrate communication between different layers of a complete web application.

## Local Development Server

To start the local development server, run the following command in your terminal:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you save changes to the source files.

## Code Scaffolding

The Angular CLI makes code organization and generation easy. To create a new component, use the following command:

```bash
ng generate component component-name
```

To explore other generation capabilities (such as directives and pipes), run:

```bash
ng generate --help
```

## Building the Project

To build the project for production, run:

```bash
ng build
```

The optimized build artifacts will be stored in the `dist/` directory.

## Running Unit Tests

To execute unit tests using Karma, use the following command:

```bash
ng test
```

## Running End-to-End (E2E) Tests

Currently, the Angular CLI does not include an end-to-end testing framework by default. You can integrate the tool of your choice to perform end-to-end tests.

## Additional Resources

For more information on using the Angular CLI and its commands, refer to the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.