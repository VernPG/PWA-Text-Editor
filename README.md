# Unit 19 PWA Homework: Text Editor (Modified Edition)

## Description

The task was to build a text editor that runs in the browser. The app is a single-page application that meets the PWA criteria. Additionally, it features a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application also functions offline.

## Table of Contents

- [Usage](#usage)
- [Install](#install)
- [Images and Repo](#images)

## Usage

```md
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
```

## Installation

[Deploy application HERE via Heroku](https://pwa-text-editor-vernpg-16b8f9c9dac0.herokuapp.com/)

## Images and Repo

![Preview image](./assets/Screenshot%202023-11-22%20at%204.49.57 PM.png)
![Preview Image](./assets/Screenshot%202023-11-22%20at%204.51.05 PM.png)
![Preview Image](./assets/Screenshot%202023-11-22%20at%204.51.20 PM.png)

\*\* [Repo can be found HERE](https://github.com/VernPG/PWA-Text-Editor.git)
