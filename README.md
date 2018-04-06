# JavaScriptAdviser

JavaScript Adviser

 Documentation

Node.js <https://nodejs.org/en/docs/>  
Angular <https://angular.io/>  
Angular CLI <https://cli.angular.io/>  
Material Design for Bootstrap 4 <https://mdbootstrap.com/>  
Firebase <https://firebase.google.com/docs/>  
Firebase CLI <https://firebase.google.com/docs/cli/>  
AnguarFire2 <https://github.com/angular/angularfire2>  
RxJS <http://reactivex.io/rxjs/>  
firebase Functions <https://github.com/firebase/functions-samples>  

# Git

## .gitignore
    # misc
    package-lock.json
    /functions/pagage-lock.json

    # dependencies
    /functions/node_modules

    # compiled output
    /functions/lib

# firebase

## Deployment

     firebase deploy --only hosting

# Angular CLI Scaffolding

    ng new cmr --service-worker --routing --style scss --skip-install
    cd cmr
    npm install
    ng generate module core -m app
    ng generate service core/auth -m core
    ng generate service core/validation -m core
    ng generate service core/notify -m core
    ng generate service core/profile -m core
    ng generate service core/application -m core
    ng generate service core/contact -m core
    ng generate service core/zipcodes -m core
    ng generate guard core/auth -m core
    ng generate module pages -m app
    ng generate module pages/pages-routing -m pages/pages
    ng generate component pages -m pages/pages
    ng generate component pages/home -m pages
    ng generate component pages/login -m pages
    ng generate component pages/register -m pages
    ng generate component pages/profile -m pages
    ng generate component pages/rates -m pages
    ng generate component pages/application -m pages
    ng generate module shared -m app
    ng generate component shared/components/header -m shared
    ng generate component shared/components/navbar -m shared
    ng generate component shared/components/action -m shared
    ng generate component shared/components/featured -m shared
    ng generate component shared/components/facts -m shared
    ng generate component shared/components/compare -m shared
    ng generate component shared/components/contact -m shared
    ng generate component shared/components/footer -m shared
    ng generate pipe shared/pipes/SelectUser -m shared
    ng generate pipe shared/pipes/SelectProfile -m shared
    ng generate pipe shared/pipes/SelectRate -m shared

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.7.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
