# PWA-Challenge-

This assignment focuses on creating a browser-based text editor that meets the criteria for a Progressive Web Application (PWA). The text editor should include features such as data persistence, offline functionality, and the ability to be installed as a PWA. The following requirements should be fulfilled:

Utilize IndexedDB for storing and retrieving data.
Bundle JavaScript files using webpack.
Generate a manifest file using webpack.
Implement a service worker with Workbox to cache assets.
Ensure that the application works offline and can be installed as a PWA.

## Table of Contents
1. Installation
2. Usage
3. License
4. Contributing

## Installation

This application is deployed on Heroku, so it can be used directly in the browser. However, if you wish to run it from the command line, you will need to have Node.js, npm, Express.js, and idb installed.

## Usage

To run the application from the command line, follow these steps:

1. Run npm i to install the necessary dependencies.
2. Run npm start to create the dist files.
3. Open the specified port in your browser.
4. When using the application in the browser, whether through Heroku or the command line, follow these steps:
5. Click inside the text editor to enter notes or text snippets.
6. Click outside the text editor and refresh the page to persist the entered content.
7. To view the saved content, open the console, go to the Application tab, and navigate to IndexedDB under storage. Refresh the database to see the stored text in the jate database.
8. The entered text will also be saved in the local storage of the browser.
9. To test the offline functionality, go to the console, switch to the Network tab, and select "offline" from the dropdown menu. You can continue adding and saving text, and it will persist even without an internet connection.


## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Contributing
Contributions to this project are welcome! If you would like to contribute, please follow the standard Git workflow: fork the repository, make your changes, and submit a pull request.



