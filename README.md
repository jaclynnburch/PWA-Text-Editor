# PWA-Text-Editor
Progressive Web Application Text Editor - This is a text editor web application designed to function as a Progressive Web Application (PWA). Below are the instructions for setting up, running, and utilizing the features of this application.

## Getting Started
Install node.js
Clone the repository: git clone https://github.com/jaclynnburch/PWA-Text-Editor.git

## Functionality
Client-Server Folder Structure: Upon opening the application in your editor, you will find a client-server folder structure.

Webpack Bundling: Running the text editor application from the terminal will bundle JavaScript files using webpack.

Next-gen JavaScript Support: The application supports next-gen JavaScript, ensuring it functions without errors in the browser.

IndexedDB Integration: Upon opening the text editor, IndexedDB immediately creates a database storage. Content entered in the editor is saved in IndexedDB upon clicking off the DOM window. Content is retrieved from IndexedDB when reopening the text editor after closing it.

Install as Desktop Application: Clicking on the Install button allows you to download the web application as an icon on your desktop.

Service Worker: When loading the web application, a registered service worker using Workbox ensures static assets are pre-cached upon loading, along with subsequent pages and static assets.

## Deployment
To deploy the application to Render, ensure proper build scripts for a webpack application are set up.

## Resources
Preply Tutor
YouTube Tutorial: https://www.youtube.com/watch?v=4XT23X0Fjfk, https://www.youtube.com/watch?v=4XT23X0Fjfk&list=RDCMUCW5YeuERMmlnqo4oq8vwUpg&start_radio=1&rv=4XT23X0Fjfk&t=0

## License
This project is licensed under the MIT License - see the LICENSE file for details.
