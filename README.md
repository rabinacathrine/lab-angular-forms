<<<<<<< HEAD
# Angapp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.0.2.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
=======
![Image description](https://i1.faceprep.in/ProGrad/face-logo-resized.png)

# ProGrad Lab | Angular Forms

## Learning Goals

After this lab, you will be able to:

- Create a static Angular application with Angular CLI.
- Build an Angular application with forms.
- Performing validation in angular forms.
- Validators in forms.

## Requirements

- Fork this repo.
- Clone this repo.

## Submission

Upon completion, run the following commands:

```bash
$ git add .
$ git commit -m "done"
$ git push origin master
```

Navigate to your repo and create a pull request from your master branch to the original repository's master branch. In the pull request name, add your ProGrad id, name, and last name separated by a dash "-".

## Deliverables

You need to generate the starter code and fill it with the necessary code to satisfy the requirements described below.

## Starter Code

To generate the starter code, follow the steps given below

- To create a new application,
    - Open your ubuntu or cmd terminal and execute the following command
      - ```ng new app-name```
      - for example, ng new super-wars
    - To create a new component, execute the command 
      - ``` ng generate component component-name```
      - example, ng generate component contacts
      
## How to run

- To run the project go to your ubuntu terminal or VScode editor
    - open the ubuntu or cmd terminal or inside the vscode editor
    - run the command following command
    - ```ng serve --open or ng serve -o```

## Instructions
Once you clone your project, 
```cd lab-angular-prograd-contacts
   run the below command
   npm install --save-dev @angular-devkit/build-angular
   ```

## Progression #1: Forms

Imagine you need to create sign up and login form for your application.

- Go to app.component.ts and try to complete the validation code for your form.
- To bind the form values along with your validation, try using the below code `ngClass` snippet in your html file inside the input tag.
``` [ngClass]="{ 'is-invalid': submitted && f.firstName.errors } ```
- Your form design in given in app.component.html, try to validate all the fields using `ngClass`.
- Validate all the fields given in the form.

## Expected Output:
![output](https://i1.faceprep.in/ProGrad/ts-registration.JPG)

Happy Coding ProGrad ❤️
>>>>>>> 1f28b2442e040be937483693c767cf70b013f1f4
