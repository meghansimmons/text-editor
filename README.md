# Text Editor

![MIT license](https://img.shields.io/badge/license-MIT-blue.svg)

## Description
The application **text-editor** allows a user to create notes with or without the internet. The notes can be retrieved for later use. 

## Installation
This application requires Node.JS to be installed. The user should run ```npm install``` and ```npm run build``` in their terminal. In some cases, the user may need to run 
```npm i @babel/plugin-proposal-object-rest-spread``` if they incur an error during install. From the integrated terminal, ```npm run start``` should be run to invoke the server. In the browser at ```localhost:3000```, the user can download the 'Just Another Text Editor' application for use while offline.

If the user would like to use the text editor without loading and running the code, they can visit https://text-editor-ms.herokuapp.com

Below are a few screenshots of the application showing the online deployed application, download button, and the application as a standalone, offline app:

<img width="500" alt="Screen Shot 2023-06-06 at 10 30 24 PM" src="https://github.com/meghansimmons/text-editor/assets/128755783/05046873-2de7-4b81-807a-9fedfb23fd59">
<img width="500" alt="Screen Shot 2023-06-06 at 10 30 36 PM" src="https://github.com/meghansimmons/text-editor/assets/128755783/de7ec377-7047-42f0-a2cc-55210181f32f">
<img width="500" alt="Screen Shot 2023-06-06 at 10 31 23 PM" src="https://github.com/meghansimmons/text-editor/assets/128755783/e0594ebe-9909-40e2-8965-2122ede7aa6b">
<img width="500" alt="Screen Shot 2023-06-06 at 10 31 58 PM" src="https://github.com/meghansimmons/text-editor/assets/128755783/33ae6d12-5d8c-4f70-9c1e-076fe37241e3">

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
