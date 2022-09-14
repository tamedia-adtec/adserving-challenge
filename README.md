# Adserving hiring challenge
This project represent a minimal ad serving sdk that wraps the Google publisher tag (GPT) and provides a small API to initiate ad calls.

### Tasks
#### 1. Bugfix
If you reload the page several times you will notice that ads are loaded that does not fit the ad slot properly. 
Fix this behavior and request only sizes that fit the ad slot(s).


#### 2. Feature
At the moment the ads are getting requested no matter if they are in the viewport.
Implement a simple lazy loading functionality that requests the ads when they enter the viewport. In the ```registerAdSlot``` function is a line is marked where you could start implementing this feature.


### install the project
```
npm i
```
Will download and install the project dependencies. 

### run the project in development mode
```
npm start
```
This will start a local webserver and open a browser where a testpage gets served and the code runs.
Whenever you do a change to your codebase it will rebuild your project and reload the preview.
