# AngularJS
Created this repository to retain tutorials taken to learn AngularJS

* Angular JS is a JS framework
* for building client side applications
* using HTML, CSS and JS

## Part 1-Pluralsight Angular: Getting Started by Deborah Kurata

Angular patterns for components, modules, patterns and services->
- Components, 
- Templates, Data binding and directives, 
- Services and dependency injection,
- Http and observables
- Navigation and routing
- Angular CLI to generate, execute and test 

Angular makes HTML expressive, contains data binding, promotes mmodularity, and buil-in support to communicate iwht back end.

AngularJS->speed (faster initial load, hange detection and rendering), modern (classes, modules, directives), simplified (easier to learn, simple binding), productivity 

### Module- First things first-
#### Anatomy of an app
- Set of components (comprised of templates)
    - Template (HTML)
    - Class (Code associated with the view)
        - Properties
        - Methods
    - Metadata
- Services across the components

Angular modules - At least one root that consolidate the components together
* Installation comments
Node.js was installed at
   /usr/local/bin/node
npm was installed at
   /usr/local/bin/npm
Make sure that /usr/local/bin is in your $PATH.

Files of base template
- github.com/DeborahK/Angular-GettingStarted
- has all the basic files you need
- files of the program can be found in APM-Start->src->app-> ALL the files here
- main folder configuration files are also called boiler plate files
    - package.json contains all the dependencies
    - scripts seems important
    
#### Start
- Clone deborah's repo for angular getting started
- Open VS Code, then go to File-> Open-> Deborah's folder
- Then go to View->Integrated Terminal to open the terminal
- Type "npm install" and hit enter to install all the packages needed
- Type npm start to build the page and launch the browser
- Go to src->app->shared->app.component.html and change the text
-  Stop it using Ctrl + C (on Mac)

### Module- Introduction to Components-

## Part 2-Pluralsight Play by Play: AngularJS Application Design with John Papa and Ward Bell
