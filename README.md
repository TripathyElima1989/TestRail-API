# Load Iframe on Click

## Description

The **Load Iframe on Click** web application allows users to dynamically load test results into an iframe when clicking a button in the navigation bar. The iframe is only created after the user clicks the "Load Test Results" button, providing a smooth experience and reducing page load time. The results are fetched from an API, displayed inside the iframe, and the user can easily scroll down to view them.

This project aims to demonstrate the usage of dynamic iframe creation, loading external data via an API, and providing a seamless user experience.

## Features

- **Dynamic Iframe Loading**: The iframe is created only when the user clicks a button, which helps to load the content only when needed.
- **Loading Indicator**: A "loading" indicator is shown while the test results are being fetched.
- **Test Results Display**: Once the test results are successfully fetched from the API, they are displayed inside the iframe.
- **Scroll Button**: A button appears that automatically scrolls the page to the iframe section once the content is ready.
  
## Technologies Used

- **HTML**: Provides the structure of the webpage.
- **CSS**: Used for styling and layout (via `styles.css`).
- **JavaScript**: Handles dynamic content loading and interactions.

## Usage

1. **Load Test Results**: When the user clicks on the "Load Test Results" button, an iframe is created dynamically. 
2. **Fetch Test Runs**: The application fetches data from the `http://localhost:3000/api/testruns` API endpoint and loads it into the iframe.
3. **Display Results**: Test results are shown with the status (completed or in-progress), including details such as:
   - Test Name
   - Description
   - Test Status
   - Passed, Failed, and Untested counts
4. **Scroll Button**: A button will appear that automatically scrolls to the results section once they are loaded.

### How to Use Locally

1. **Clone the repository** to your local machine.
   ```bash
   git clone https://github.com/yourusername/load-iframe-on-click.git
