# Moments

This project is a full-stack application built with [Angular CLI](https://github.com/angular/angular-cli) version 16.2.3 on the front-end and AdonisJS on the back-end.

## Backend

To get started, follow these steps:
1. Clone the repository: `git clone https://github.com/matheusbattisti/curso_adonis_api_yt.git`
2. Navigate to the project directory: `cd curso_adonis_api_yt`
3. Install the dependencies: `npm install`
4. Generate a secret key: `node ace generate:key`
5. Create a new `.env.example` file by copying the `.env.example` file and replacing the `APP_KEY` value with the generated secret key.
6. Run the database migrations: `node ace migration:run`
7. Start the server: `node ace serve`Once the server is running, you can make requests to the API. Contributions are welcome under the MIT License.

For more details, please visit the [GitHub repository](https://github.com/matheusbattisti/curso_adonis_api_yt).

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
