# Hacker Noon Website Clone

#### By **Ian Cook Westgate**

## Description

This copy of Hacker Noon is an app designed for Epicodus to practice cloning a website using the Angular framework. The links have no functionality. This final version includes posts brought in via a database acquired through Firebase.

## Setup

* Install Node.js.
* Clone the repo: https://github.com/iwestgate931/hacker-noonclone.git.
* Navigate to the folder in the terminal by typing in: "cd hacker-noonclone".
* `npm install` to install dependencies.
* Create and/or use an account with https://firebase.google.com/.
* Click the "GO TO CONSOLE" link in the top right of the screen.
* On the next page, click "Add project" below the + sign. Create a project with a name of your choice.
* When you get to the main page for this new project, click the "</>" icon near the center left of the screen.
* In the pop-up, note the part of the file that looks like this:
  'apiKey: "abcdefghijklmnopqrstuvwxyz12345",'
* Create an "api-keys.ts" file in the "app" folder of this project. Copy paste the info above into this new file. Take the API key that you created and put it in the "apiKey" section.
  export const masterFirebaseConfig = {
    apiKey: _"Put your apiKey here!"_,
    authDomain: "hacker-noon.firebaseapp.com",
    databaseURL: "https://hacker-noon.firebaseio.com",
    projectId: "hacker-noon",
    storageBucket: "",
    messagingSenderId: "1128055699"
  };
* Back in your terminal, run `ng serve --open` for a dev server. This will open a window in your web browser with which to view the project. The app will automatically reload if you change any of the source files.
* `npm run lint` to explicitly run ESLint.

## Site Features

* Navbar recreates the neon green appearance of Hacker Noon.
* Icons and imagery are in place, retrieved directly from Hacker Noon.
* Site is loosely structured to resemble Hacker Noon's presentation.

## Planned Features

* Tighten up the arrangement of posts to better match that of Hacker Noon's.
* Spend more time with CSS to properly format fonts, links, and post info.

## Technologies Used

* HTML
* CSS
* JavaScript
* Node.js
* Babel
* Webpack
* Firebase

## Known Bugs

* While all Angular component usage and Firebase data retrievals are now working, getting their info to display properly below the initial two highlighted posts has been a challenge.
* The posts are currently scrunched up together and are not as of yet responding to margin or padding changes. This is also a problem that has not yet been resolved for link arrangements in the navbar.
* The CSS for the highlighted images also doesn't stretch across the entire screen when taken to a maximum size (unlike that of Hacker Noon).

## Support and contact details

_Email iwestgate@hotmail.com with any questions._

## License

This software is licensed under the MIT license.

Copyright (c) 2019 **Ian Cook Westgate**
