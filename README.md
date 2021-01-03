# AstonVillaApp

> docker build -t av-nginx .

> docker run --name av-app-multistage-container -d -p 8888:80 av-nginx

> docker login --username=[username]

> docker tag [imageId] [username]/av-nginx:latest

> docker push [username]/av-nginx

> docker container prune
> docker image prune -a

Prune deletes container and image

> docker comtainer logs [containerID]

az container create --resource-group cloud-shell-storage-westeurope --name mycontainer --image lutfioz/av-nginx --ports 80  
https://docs.microsoft.com/en-us/learn/modules/run-docker-with-azure-container-instances/2-run-aci   
or   

https://docs.microsoft.com/en-us/azure/container-instances/container-instances-quickstart-portal   


DockerHub to Container  
http://my-aston-villa.westeurope.azurecontainer.io/  

Static Web App  
https://green-coast-04884eb03.azurestaticapps.net/


This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.1.4.

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

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
