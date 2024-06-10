# boilerplate-three-js
This project was generated manually using a bundler and parcel.

## Development server

- Run `npm init -y` to create a package.json file.
- Run `npm install parcel --save-dev` to install parcel(bundler).
- Create an `src` folder which will consist of the js script file, the assets and a index.html file.
- Insert `script` tag in order to read your script.js file. The type for the tag will always be `module` since we want to use the import statements in our scrip.js file.
- Run `npm install three` to install three.js in your project.
- Run `parcel ./src/index.html` so that parcel reloads the page automatically whenever we save any update in our code.
- The above command will create a dist folder.
- Navigate to `http://localhost:1234/`. The application will automatically reload if you change any of the source files.