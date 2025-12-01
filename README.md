# Routing

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 18.0.0.

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

## Codespace Addition

To use the Angular DevTools Pluggin, instead of npm start command, use `ng serve --host=0.0.0.0 --port=4200` to spin up the app. One option is to update the *package.json* under scripts add `"codespace": "ng serve --host=0.0.0.0 --port=4200"` so you can then use the command `npm run codespace` to spin up the site.

Also, for some reason the codespace Angular setup seems to not include *Angular CLI* services. So, run `npm install -g @angular/cli` so it will work.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

## Static Hosting Information

Firebase is a recommended free option to use with SPA type pages and offers options to extend the SPA deployment type.
1. Sign in / Create Account using Google Email
2. Click Console
2. Get Started with a new project.
3. Choose Hosting from the projects navigational.
4. Static Website -> choose Get started.
5. Will provide an, Install Firebase CLI command to install on your code project.
6. Will send your through various commands that require setup through your Google account & authentication to verify it's you connecting Firebase > Google > Code Project
7. Example of the Firbase config setup...

Your public directory is the folder (relative to your project directory) that
will contain Hosting assets to be uploaded with firebase deploy. If you
have a build process for your assets, use your build's output directory.

✔ What do you want to use as your public directory? dist/routing/browser (which is setup after running your `ng build` command)
✔ Configure as a single-page app (rewrite all urls to /index.html)? Yes
✔ Set up automatic builds and deploys with GitHub? No (May want to explore this option at a later date)
✔ File dist/routing/browser/index.html already exists. Overwrite? No
i  Skipping write of dist/routing/browser/index.html

8. Before using the Firebase deploy command, check the firebase.json file to ensure the public value does not have a space and is pointing to the correct directory of your production folder (ist/routing/browser).
9. Deploy & review provided URL