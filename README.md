
# Angular Admin Dashboard System with Login and Sign-Up

This project includes a Login system with Signup for new user. Validations exist on Signup and Login fields. Auth Guard is used for Authentication and Dashboard Access.

Once logged in, the Admin can Create, Read, Update and Delete entires in the Employee Details Table.

# To run the project on your local machine, first clone it to your system
# Then run the following commands..

	npm install   (installs node modules) 

   --- Add Angular if you haven't already --
	 
	 ng serve -o  (serves the Angular project on default port 4200)

	#json-server --watch dbcrud.json  (starts the json server(used to create fake backend API on default port 3000 and connects to database "dbcrud")

# AngularCRUD

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.2.6.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

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
