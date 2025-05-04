# POC for Internationalization in Angular using ngx-translate and Standalone Components

## Description

This project is a Proof of Concept (POC) demonstrating how to implement internationalization (i18n) in an Angular 19 application using the `ngx-translate` library. Additionally, standalone components are used in Angular, enabling a more modular and flexible architecture.

The project includes the following features:

- Dynamic language switching with `ngx-translate`.
- Language selection via a dropdown menu with flags.
- A button to toggle between light and dark mode.
- Use of real Material Design themes for a modern look.

This POC showcases how to efficiently and flexibly achieve internationalization in Angular, leveraging standalone components and dynamically configuring the language of the application.

## Features

- **Multi-language support**: Implemented languages include English (en) and Spanish (es).
- **Light and dark mode**: Toggle between light and dark mode with a simple toggle button.
- **Language selector menu**: Users can select the app's language through a dropdown menu with representative flags.
- **Use of `ngx-translate`**: The `ngx-translate` library is used to manage app translations, allowing dynamic loading of translation files.

## Technologies Used

- **Angular 19**: The framework used to build the application.
- **ngx-translate**: Library for internationalization in Angular.
- **Angular Material**: A UI component library for Angular that helps create modern, accessible designs.
- **Custom CSS**: Classes used to toggle between light and dark themes.
- **SVG Flags**: Flags are managed through SVG files.

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/leonardonieves/poc-i18n-demo.git
   
2. Navigate to the project directory:
   ```bash
   cd poc-i18n-demo

4. Install the dependencies:
   ```bash
   npm install
   
6. Start the application:
   ```bash
   ng serve
   
5.Access the application in your browser:
  ```bash
   http://localhost:4200

## Usage
You can change the language of the application by selecting an option from the dropdown menu in the navigation bar (using flags).

You can also toggle between light and dark mode using the toggle button in the navigation bar.

## Project Structure
src/app: Contains the main files of the application.

app.component.ts: The main component of the app.

app.component.html: The HTML template that defines the UI structure.

app.component.css: Styles for the main component.

src/assets/i18n: Folder containing the translation files (en.json, es.json).

angular.json: Angular configuration, including routing and static file setup.

This project uses ngx-translate to provide a more flexible and dynamic solution for switching languages during runtime.

## Contributing
If you would like to contribute to this project, please follow these steps:

Fork this repository.

Create a new branch (git checkout -b feature/new-feature).

Make your changes and commit them (git commit -am 'Add new feature').

Push to your branch (git push origin feature/new-feature).

Create a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for more details.
