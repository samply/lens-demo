# Samply.Lens Demo Application

This project holds a demo application for the [samply.lens](https://github.com/samply/lens) project. It's intended usage is to provide an example for developers on how to use samply.lens in their application.
To create your own application with Samply.Lens, you can copy the contents of this repository through the [template repository functionality](https://docs.github.com/de/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template#creating-a-repository-from-a-template) in github.

## Benefits of using this Project
The projects provides:
- [Dockerfile](./Dockerfile) for building the application
- ready to deploy [docker-compose.yml](./docker-compose.yml) with a [minimal configuration file](./example.env).
- [installation script](./install-lens.sh) for your severs
- Basic Usage Example of the current Lens API

Also planned are:
- Github Workflow for Pushing the Image to Github
- Github Workflow for deploying to Github Pages

## What is Samply.Lens?
This question is best answered by reading the README on [Samply.Lens Repository](https://github.com/samply/lens) 
## Developing your Application

### Run the development server
Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

### Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

### Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

### Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

### Running end-to-end tests
  
Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

### Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
