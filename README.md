# Project Agora Case Study 

Folder Structure
```bash
│   package-lock.json
│   package.json
│   README.md
│   webpack.config.js
│
├───dist
│       0d85613327d514896745.js
│       bedff6d4a15755ca637b.js
│       index.html
│       main.js
│
└───src
    │   index.html
    │   index.js
    │
    ├───ad_scripts
    │       ad_slot_1.js
    │       ad_slot_2.js
    │
    └───js
            image_viewport.js
            three_seconds_delay.js
            word_counter.js
```
## Short Reference of the source code files

The project has bootstraped with a javascript module bundler(webpack).

1) I changed the background of the header to red
2) In the src/js there is the word_counter.js. I got the whole content of main-content div I removed the HTML elements and then I printed the total number of words
3) In the src/js I created the image_viewport.js. The function check if the bottom of the img is smaller than window.innerHeight. After the check it renders the message "Ad fully viewed" inside a yellow box.
4) In the js folder the three_seconds_delay.js. The function checks if the page is fully loaded and then waits for 3 seconds, then calls another function that create the placeholder(adslot_2) for the second ad.
**Note**:I faced an unexpected error when I try loading the ad_slot_2.js so I implemented a walkaround solution for the desired result.

## How to run the application
In the app folder

**-Install*: npm run install
**-Build**: npm run build
**-DEV**: npm run start:dev
