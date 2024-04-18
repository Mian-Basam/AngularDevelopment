
# Angular
Angular is the Javascript framework used to develop frontend single-page applications written in type script. Type script is the superset of javascript that contains all the functionality of javascript + additional functionality like static typing, classes, interfaces, and other features of the language. It is developed and maintained by Microsoft and is widely used for building large-scale web applications.

# Setup Requirement 
- node
- @angular/cli
- typescript

## Installation of node typescript and typescript
In **ubuntu:20.04**, you can install it using the following commands:
- apt-get update
- apt-get install -y git curl
- curl -sL https://deb.nodesource.com/setup_18.x -o nodesource_setup.sh &&\
    bash nodesource_setup.sh
- apt-get install -y nodejs
- npm install  --global typescript &&\
  npm install  --global @angular/cli

## By default, Angular 17 creates a standalone app. [Angular Options](https://angular.io/cli/new#options)

if you do not want to create a standalone app, use this command ng new **NoStandaloneApp --standalone=false**

Standalone apps do not create **app.module.ts**. AppModule tells Angular how to assemble the application.
