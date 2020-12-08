# ng-base

Angular 11.0.3 basic setup.

```bash
# bootstrapping
npm install -g @angular/cli
ng new ng-base # choose strict, router, scss
cd ng-base

ng generate component component-name # scaffolding
# also directive|pipe|service|class|guard|interface|enum|module

ng serve --open # dev server
ng build --prod # prod build to ./dist

ng test # unit karma tests
ng e2e # end-to-end Protractor tests

## Further help
ng help
```

Generated with [Angular CLI](https://github.com/angular/angular-cli).
