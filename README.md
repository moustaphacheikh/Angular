# Angular
Angular learning resources

## Node package manager (npm)
you can use npm to install, share, and distribute code; manage dependencies in your projects; and share & receive feedback with others.
* npm insrall jquery
will install jquery in a folder named node_modules
npm help you get any javascript libary

# CustomerApplication

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.1.3.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component.
 You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

## angular instalation
* npm install -g @angular/cli

-g is for global use not use in this folder  

## Angular CLI
A command line interface for Angular
Generating and serving an Angular project via a development server Create and run a new project:
'''
ng new project
cd project
ng serve

'''

* **ng new**
The Angular CLI makes it easy to create an application that already works, right out of the box. It already follows our best practices!

* **ng generate**
Generate components, routes, services and pipes with a simple command. The CLI will also create simple test shells for all of these.

* **ng serve**
Easily test your app locally while developing.

## Angular files structure
* **e2e** : end 2 end testing
* **src** : code source of our app
* **node_modules** : all installed pakages are stored here
* **dist** : final compiled ts code to js code used in production

* **angular.json** : all angular configuration
* **tsconfig.json** : all ts configurations
* **pajage.json** :  all node configuration

* **tslint.json** : linter configurations

* **component** : receive the data from the API(model) and bind it with the html
a group of component is called module
