# RichPdf

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.0.1.

### User Flow

##### Home Screen
>
* File upoad interface that should accept drag-and-drop .PDF upload
* Sample PDF file exists on repository
* Invalid file format prompt an alert message

##### Main Screen
>
* A file browsing interface that include an area rendering the file uploaded via Main Screen
* Use [PDF.js](https://mozilla.github.io/pdf.js/)
* An intuitively placed textfield that archives type-to-search functionality within the rendered PDF file
* Search again using different text
* Exact match only
* Navigate to first occurrence
* Go back to Home Screen to restart process

### Demo

Deployed on Heroku staging server
not yet (http://localhost:3000)

### Development server
Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

### Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

### Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

### Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
