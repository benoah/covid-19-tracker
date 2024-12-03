🦠 COVID-19 Tracker

The COVID-19 Tracker is a React-based application that provides live updates, statistics, and a global map visualization of COVID-19 cases. It leverages Chart.js for graphical data representation and Leaflet.js for the interactive map. The goal of this project was to understand data visualization and geospatial mapping in a React application.



🚀 Features

	1.	Global Overview:
	•	View global COVID-19 statistics (cases, recoveries, and deaths).
	•	Data is dynamically fetched from an API.

	2.	Country-specific Statistics:
	•	Dropdown menu to select and display statistics for specific countries.

	3.	Interactive Map:
	•	Displays geospatial data for COVID-19 cases around the world.
	•	Built using Leaflet.js for real-time map interactivity.

	4.	Graphical Representation:
	•	Dynamic line chart showing COVID-19 trends (cases over time).
	•	Built using Chart.js for responsive and interactive visualizations.

	5.	Live Data:
	•	Real-time data updates for accuracy.

🛠️ Technologies Used

![image](https://github.com/user-attachments/assets/1052566a-3010-455c-b173-edf1cceaaeb5)
![image](https://github.com/user-attachments/assets/b3191d65-8437-4848-862c-4f9cb06de092)


📋 Requirements

To run this project, ensure you have the following installed:
	•	Node.js (v14+ recommended)
	•	npm or yarn


📁 Folder Structure

	•	App.js: Main component orchestrating the app.
	•	components/:
	•	Contains reusable components like InfoBox, LineGraph, Map, etc.
	•	utils/:
	•	Utility functions for data formatting and processing.
	•	assets/:
	•	Images, icons, and other static resources.


⚡ Key Functionalities

1. Real-time Data Fetching

	•	The app fetches live data from a COVID-19 tracking API.
	•	Global and country-specific statistics are updated dynamically.

2. Geospatial Visualization

	•	The interactive map displays COVID-19 cases globally, using circles to indicate case density.
	•	Zoom and pan functionalities for exploring specific regions.

3. Data Visualization

	•	Graphs dynamically plot data trends (e.g., new cases over time) using React Chart.js 2.

4. Responsive UI

	•	Built with Material-UI for a modern and user-friendly design.

🧪 Learning Highlights

	•	Implementing real-time data fetching in React with useEffect.
	•	Creating reusable and modular components for UI.
	•	Leveraging Chart.js for dynamic graph visualizations.
	•	Understanding geospatial mapping with Leaflet.js.
	•	Working with third-party APIs to fetch and display live data.

⚡ Future Improvements

	1.	Add user authentication for personalized statistics.
	2.	Include vaccination data for a more comprehensive tracker.
	3.	Improve the map’s interactivity with more detailed tooltips and filters.
	4.	Add a dashboard for comparing data across multiple countries.


This project was created as part of my learning journey in web development and data visualization. It helped me strengthen my React skills and explore libraries like Chart.js and Leaflet.js. 😊



# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `yarn build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
