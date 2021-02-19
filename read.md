## Electron App built using SWAPI wrapper

![alt text](star_wars_logo.png "star-wars-logo")

### Guide to run the swapi-wrapper

- Clone the repo and change the working directory

`cd repo/swapi-graphql-wrapper`

- Install all the dependencies

`npm install`

- Run the swapi wrapper

`npm run start`

- We need now start the electron app.

### Guide to run the frontend-electron-app

- Change the working directory

`cd repo/frontend-electron-app`

- Install all the dependencies

`npm install`

- Run the Electron App

`npm run electron-app`

##Functionalities

- The swapi wrapper is used to define graphql schema, it is publicly available, and provided by graphql. It is also used for making requests to the swapi API and returns the response.

`https://github.com/graphql/swapi-graphql`

- The electron-app has two buttons: Vehicles and Characters. Both display various attributes of vehicles and characters in star wars the popular sci-fi movie. The original series was ahead of it's time. They also have one sort function implemented. Sort by height for characters and sort by maximum atmospheric speed for vehicles.
