# Movie_Lookup_Site_Project
This is Project 1 for Phase 3 of the Google Tech Training Program

Project 1 - Build a Movie Lookup Site
Introduction:
Using your knowledge of forms and APIs, you’ll build a website to look up information about movies and display the information for your users.

Tasks:
Create a new local project that uses Vite, Prettier, and ESLint
Register for a free OMDb API API key
Create a form that lets the user search the API using the following options:
API Key (required, string)
Don’t include the API key in your code! API keys are considered confidential secrets, like a social security number, that uniquely identifies you to the API you’re using. Including them in your code or in your codebase means that anyone who looks at your code can impersonate you, like identity fraud if someone were to steal your SSN. This is true of both backend and frontend development.
For this project, by making the API key an input field instead, you are able to keep it secure by only including it when you go to use it.. 
Title or IMDB ID (one or the other required, string)
Year (optional, number, greater than 1928, less than or equal to the current year, for whatever the current year is)
Short or long plot (required, one or the other)
Validate that all fields are correct, displaying error messages for any form input that’s incorrect
If all fields are correct, use the inputs to query the API, and disable all form fields and buttons
Make sure you use HTTPS for your API call! HTTPS, as opposed to HTTP, is a secure connection and will encrypt both the URL and the contents, preventing others from seeing what’s sent and received. 
If there’s a result, display the first movie or show’s title, year, rating, release date, and poster (if it has them) underneath the search form
Don’t use innerHTML to add items to the page! innerHTML can expose your website to a type of security vulnerability known as  cross-site scripting (XSS) by allowing untrusted HTML to be injected onto your trusted page. Instead, use document.createElement() and textContent to create HTML elements and set the text of elements where needed, and use append and remove to add and remove elements as needed. 
If there’s no result, display an error message that what they searched for could not be found underneath the search form
Whether there are results or not, re-enable all form fields and buttons
When a user searches again, remove any error messages or existing search results that may have been displayed from their previous search
The HTML, CSS, and JavaScript for the web page should be separate files. Use JavaScript module syntax (ES Modules) for your JavaScript
Submit your code by pushing it to GitHub, ensuring that there are no Prettier or ESLint errors
