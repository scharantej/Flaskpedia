# Google App Design

## Overview
- The Google app will be built using Python Flask, enabling users to search for information and display the results in a user-friendly interface.
- Users will interact with the app through a simple yet elegant HTML interface, allowing them to input their search queries.
- The Flask application will handle the search logic, utilizing Google's search API to retrieve relevant results.

## HTML Files
- **index.html**: This will serve as the main page of the application, presenting a simple search bar where users can enter their queries.
- **results.html**: This HTML file will display the search results, consisting of a list of links to relevant web pages retrieved from Google's API.

## Routes
- **/**: This route will serve the index.html page, displaying the search bar to users.
- **/search**: When a user enters a query and submits the search form, this route will be triggered. It will handle the interaction with Google's API, retrieve the search results, and render the results.html page, presenting the links to the user.

## Conclusion
This Flask application design provides a basic yet functional user interface for searching and displaying results from Google. It adheres to the constraints of using only Python Flask and offers a simple user experience for search functionality.