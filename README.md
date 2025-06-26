# Angular and Typescript
[Angular GitHub](https://github.com/semal-genc/offline-techcareer-angular-app)

## Git Kurulumu
https://git-scm.com/downloads/win
git config --global user.name "Şemal Genç"
git config --global user.email "semalgenc5@gmail.com"

---

## Node JS
https://nodejs.org/en/download

---

## Version
git -v
npm -v
--
npm list
npm list -g

## Npm Komutları
npm init
npm init -y
npm list
npm list -g
npm list -g --depth=0

npm root
npm root -g

npm config list -l

npm install
npm i
npm install --serve bootstrap
npm uninstall --serve bootstrap
npm update bootstrap

## Npm  Clean
npm uninstall -g @angular/cli
npm cache clean

## Angular İçin Öncelikle Kurmanız Gerekenler
npm install -g typscript
npm i typscript

npm install -g @angular/cli
npm i @angular/cli

npm i bootsrap
npm i fontawesome
npm i -g nodemon

## Angular Kurulumu
```sh
ng new tech-angular-app
cd tech-angular-app
ng serve
ng serve --open

ng serve --port 9999 --open
http://localhost:9999
curl localhost:9999
```

## Angular CLI Hazır Bileşenler
ng generate component login 
ng g v login
ng g pipe loginPipeline 
ng g service loginService 
ng g module loginModule
ng g directive loginDirective
ng g interface loginInterface
ng g enum loginEnum

## 3. Parti Uygulamalar Ekle
### Font-awesome
```sh
Terminal => npm i font-awesome
angular.json =>
"styles":   [
              "src/styles.css",
              "node_modules/font-awesome/css/font-awesome.css"
            ],
<i class="fa fa-car"></i>
```

### Bootstrap
```sh
Terminal => npm i bootstrap
angular.json =>
"styles":   [
              "node_modules/bootstrap/dist/css/bootstrap.css"
            ],
"scripts":  [
              "node_modules/bootstrap/dist/js/bootstrap.min.js",
              "node_modules/jquery/dist/jquery.js"
            ],
<div class="alert alert-primary" role="alert"></div>
```

### jQuery
```sh
Terminal => npm i jquery
angular.json =>
"scripts":   [
              "node_modules/jquery/dist/jquery.js"
            ],
<div class="alert alert-primary" role="alert"></div>
```







# TechAngularApp

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 20.0.4.

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running unit tests

To execute unit tests with the [Karma](https://karma-runner.github.io) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
