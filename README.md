# weather-journal-app
It helps the user to know the weather condition at a location using the zip code he provides

## Table of Contents

* [Description](#Description)
* [Process](#Process)
* [Major file](#Major_files)
* [Dependencies](#Dependencies)

## Description
An app that uses the zip code provided by the viewer to retrieve data from an open weather website and displays the result on the site together with the response he/she provided for the user to see.

## Major_files
```
weather-journal-app/
└── website/server.js
     ├── app.js
     ├── index.js
     ├── style.css
     └── ...
```

## Process

Firstly, I created a local server for the website at (server.js).

A starter code was already provided by Udacity for this project, index file(website/index.html) and css file(website/style.css).

Using the app.js file(website/app.js) I built the website to use the zip code provided by the user to retrieve weather data and displays the result as a list together with the response he/she provided for the user to see.

## Dependencies
To try out the web app, fill in your country code and api key at zip_code variable in your app.js file(website/app.js) or the  website will not retrieve any data and will give an error
I used a starter-code from *[refresh-2019](https://github.com/udacity/fend/tree/refresh-2019/projects/weather-journal-app)*