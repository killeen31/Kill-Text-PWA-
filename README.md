# Kill-Text-PWA-
A progressive web-application text editor
 
- Table of contents 
-Description 
-Installation 
-Usage 
-What I learned 
-Contributing
-Credits
-License 

# User Story 
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use

# Acceptance Criteria
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application


# Decsription 
The task was to make a text editor that follows PWA (Progressive Web Apllication) crieteria. We needed to impliment a service worker and webpack as well so that this application can be used without an internet connection. 


# Installation 
This app is installed by visiting my GitHub page and cloning my repository "Kill-Text-PWA" 
This app was built with:
Node.js 16.18.1
Javascript
Express.js
Webpack
Service Workers
* Open the repo using vscode 

# Usage
To use this application go to my GitHub repository killeen31 and clone the ssh key, I also uploaded this applicatiion to heroku and can be found there. 


# What I learned 
What I learned while creating this app was how to create a PWA using service workers and webpack. 

# Credits 
This app can be credited to Jack Killeen with some help from the TAs and one tutoring session

GitHub - killeen31 


# License 
This application uses an MIT license 


