ROCKET LAUNCH EXPLORER

Project Description
Rocket Launch Explorer is a web application that allows users to select upcoming rocket launches and view their mission information. The website retrieves data from the Space Devs API and displays the launch name, mission description, and rocket image. It also includes loading messages, error handling, and responsive CSS styling.

GitHub Repository
https://github.com/BethanyYates/rocket-launch-explorer.git

Part 1: XMLHttpRequest and Callbacks
The callback version uses XMLHttpRequest to request upcoming launches and individual launch details from the Space Devs API. The getUpcomingLaunches() function receives populateDropdown as a callback, which runs after the request successfully returns the launch data. The getLaunchDetails() function similarly receives displayLaunchInfo as a callback to display the selected mission's information.

Part 2: Axios and Promises
The Axios version replaces XMLHttpRequest with axios.get() and uses promises to handle asynchronous API requests. The .then() method processes successful responses using response.data and calls the appropriate display function. The .catch() method handles failed requests and displays an error message, while loading messages inform users when requests are in progress.

Technologies Used
HTML5
CSS3
JavaScript
XMLHttpRequest
Axios
Space Devs API

API Endpoint
https://lldev.thespacedevs.com/2.3.0

Project Files
rocketlaunch.html - Website structure
styles.css       - Website styling
app.js           - JavaScript and API requests
README.txt       - Project documentation