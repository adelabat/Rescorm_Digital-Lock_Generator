# Webapp Password Strength Checker

## Installation
1. Previous requirements:
    * A computer with internet connection
2. Install [git](https://git-scm.com/downloads).
3. Open a new terminal, go to your working directory and clone this GitHub poject:
    ```bash
    git clone https://github.com/adelabat/Rescorm_Digital-Lock_Generator
    ```
4. Go to the 'Rescorm_Digital-Lock_Generator' folder that has been created.
5. Execute the following command to install all the project dependencies in the 'node_modules' folder:
    ```bash
    npm install
    ```
6. Execute the following command to start the development server:
    ```bash
    npm start
    ```
    The app will be available at the following URL [http://localhost:3000](http://localhost:3000).  
    
7. Development server can be stopped by pressing 'Ctrl-C'.
8. Configuration can be specified in:  
    * src/config/Config.js: Global configuration to customize the React application.  
    

## Available commands
### `npm start`
Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.
The page will reload if you make edits.<br>
You will also see any lint errors in the console.
### `npm test`
Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.
### `npm run build`
Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

## Available Configuration
#### title: "DIGITAL LOCK",
#### showUsername: true,
      timeout: 0,
      answer:"8132",
      tip:"Select the top 3 points starting from the left",
      CombinationLockImage:"./../assets/images/CajaFuerte.png",
      mode:"Symbol",
      theme:"sketchy",
      good:"Enhorabuena, lo has logrado!!",
      bad:"Lo siento, se acabó tu tiempo",
      escapp: true,
      puzzleId: 5,
      escapeRoomId: 1,
      puzzleLength: 4,
      scormVersion: "1.2",

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).
To learn React, check out the [React documentation](https://reactjs.org/).
