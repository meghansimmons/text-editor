# Text Editor

![MIT license](https://img.shields.io/badge/license-MIT-blue.svg)

## Description
The application **text-editor** allows a user to create notes with or without the internet. The notes can be retrieved for later use. 

## Installation
This application requires Node.JS to be installed. The user should run ```npm install``` and ```npm run build``` in their terminal. In some cases, the user may need to run 

```npm i @babel/plugin-proposal-object-rest-spread``` if they incur an error during install. From the integrated terminal, ```npm run start:dev``` should be run to invoke the servers. In the browser at ```localhost:3000```, the user can download the 'Just Another Text Editor' application for use while offline.

If the user would like to use the text editor as a standalone application, they can visit https://text-editor-ms.herokuapp.com

Below are a few screenshots of the application:

## Usage
The user can type notes or code snippets into the text editor.  If needed, the application can be downloaded by clicking on the 'Install' button on the left side of the screen or by clicking on the small icon at the right end of the address bar. Follow the prompt to download the application. The data entered in either the web browser or in the downloaded application will be accessible when online or when offline.

## Credits
Starter code was supplied for the **text-editor** application. The Unit 19 PWA Activities (especially 26 & 28 Mini Project) were utilized in adding proper logic, code and syntax for the **text-editor** application.

Online documentation for the webpack-pwa-manifest npm package was used to removed unwanted, added data to files. In particular, ```fingerprints: false```, was set in the webpack.config.js file under the WebpackPwaManifest plugin information.

## License
[MIT](https://choosealicense.com/licenses/mit/)

## Questions
For any further information about this application or questions you might have, please visit my GitHub profile
[meghansimmons](https://github.com/meghansimmons/text-editor).