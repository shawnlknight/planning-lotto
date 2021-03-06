# Planning Lotto

This app allows software development teams to play [Planning Poker](http://en.wikipedia.org/wiki/Planning_poker).


## Description

This app is designed to allow a software development team to play "Planning Poker", a game used to estimate how much time different development tasks will take. To learn more about Planning Poker, check out the article on [wikipedia](http://en.wikipedia.org/wiki/Planning_poker). The app will run in your browser and allow your team to silently vote on tasks, then reveal the results.

## Redesigned

This app has had the UI updated from [Pete's Play's Lotto version](https://github.com/peteplays/plays-lotto). Pete also updated the UI and backend based off of [Jenni's Planning Poker](https://github.com/jenjaina/planning-poker).


## How to use the app

Clone the repository

`cd` into the directory

Run `npm install`

Start the build

`gulp build` _run at least the first time to create all required files_


## How to run the app locally

Edit the following files `www/index.html` & `app/js/main.js` & `app/css/main.less`

`npm run dev` will execute `gulp` and start a server at `localhost:1337`

Open multiple tabs to see how multiple users can submit their estimations and view the results.


## App Structure
```
├───┬ app/
|   ├───┬ css/
|   |   ├── main.less
|   |   └── slider.less
|   ├───┬ js/
|   |   ├── keepNewLines.js
|   |   ├── main.js
|   |   └── socketService.js
|   ├── app.js
|   └── app.less
├───┬ resources/
|   ├───┬ images/
|   |   ├── cross-scratches.png
|   |   ├── fabric-of-squares.png
|   |   ├── favicon.ico
|   |   └── playslogo.png
|   ├───┬ socketio/
|   |   └── main.js
├───┬ www/
|   ├───┬ css/
|   |   ├── bundle.css
|   |   └── bundle.min.css
|   ├───┬ fonts/
|   ├───┬ js/
|   |   ├── bundle.js
|   |   └── bundle.min.js
|   └── index.html
├── gulpfile.js
├── package.json
├── Procfile
├── README.md
└── server.js
```

## How to deploy the app

`npm start` will build the app and start `node server.js` for the host

Thanks for viewing!
