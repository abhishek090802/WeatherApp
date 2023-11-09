Procedure:
Step-1:Featch the weather credentials from the rapid api(Open weather api) for the country speceific details more specifically temperature,Humidity and wind speed.

Prerequisites:

a)Node.js and NPM: Make sure that you have Node.js and npm installed prior 

b)Angular  CLI:Install the Angular CLI globally in your local system 

Command for installing Angular CLI: npm install -g @angular/cli

Step1: create an angular project folder in your local system 
Command: ng new angularapp

Step2:To fetch the weather details we will use the openweather api sign in for the free account. Once registered obtain an pi key which aare used when you make api requests 

Step3:Create Weather service logic in your angular application to encapsulate the logic of weather services fetched from the OpenWeather API.

Step4:Update the app component and its respected css files in systematic way 

Step5:Once you are done with all the coding part run the following command in your terminal to start the development server to view the weather app in your browser 

Command: ng serve 

After the code being executed your application will run on the http://localhost:4200/ in your local system 



# Weather

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.2.11.

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
