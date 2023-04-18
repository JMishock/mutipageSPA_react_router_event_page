# mutipageSPA_react_router_event_page

This application was part of a Udemy.com course React-The Complete Guide(incl Hooks, React Router, Redux)
by Maximlian Schwarzmuller.

Available Scripts
In the project directory, you can run:

npm start
Runs the app in the development mode.
Open http://localhost:3000 to view it in your browser.

The page will reload when you make changes.
You may also see any lint errors in the console.

npm test
Launches the test runner in the interactive watch mode.
See the section about running tests for more information.

npm run build
Builds the app for production to the build folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.
Your app is ready to be deployed!

See the section about deployment for more information.



This project actually contains two projects:
- A React.js application (i.e., the frontend SPA)
- A dummy backend API to which the React app can "talk" (to send + fetch data)

You must run "npm install" in both project folders.

Thereafter, you can start the dummy backend API server via "npm start" (inside the "backend-api" folder).
The React app dev server is then also started via "npm start" (though inside the "react-frontend" folder).

You MUST have both servers (backend + frontend) up and running for the projects to work.

The dummy backend API does not use any external database - instead the dummy data is saved to an "events.json" file inside the project folder.

This application let's the user navigate across an application that allows them to go from "Home", "Events", and "Newsletter".
The user can sign up for a newsletter by entering in a valid email address and submitting the "Sign up" button.
If the email does not meet the credentials an error message will open.
The user can create an event along with a date and details.
By clicking on the yellow "All Events" button the user can browse all events posted.
