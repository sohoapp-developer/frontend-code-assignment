# Frontend code assignment
1. Create a web application that consumes [Github API](https://developer.github.com/v3/) and follow the requirements as listed below.
2. Host your production ready application ([Heroku](http://heroku.com) preferably but you can choose other platform too)
3. Push your new repository in your Github account
4. Send us the links to your Github repository and the deployed application
5. Completing all bonus points is not mandatory
 
## Requirements
- There is a search bar to let the user search by username (login name)
- While searching, the application shows an animated loading indicator made by CSS 
- After the search is completed, the application shows the list of users along with their avatar and their username on the same page
- If the results are not complete in one page, the pagination is shown on the screen
- When a list item is clicked, the application is navigated to a new page that display the parsed JSON payload of that user
- The new page also has to display the list of the user's repositories, followers and following
- The application is built by [React](https://github.com/facebook/react) and [Redux](https://github.com/reactjs/redux)
- [Webpack](https://github.com/webpack/webpack) is being used to build the application
- The application style is built by one of the CSS preprocessors or CSS-in-JS
- The application has to be responsive and optimised for mobile
- A documentation on how the application works and how to set up and build the project is provided
 
## Bonus points 
- The pages are server-side rendered and are cached in the server
- All pages' URL is reusable - meaning it can be copied and pasted on different browser and still shows the same result
- All pages are SEO optimised
- The results list also asynchronous-ly shows the number of followers and following of each user without going the user page
- The search input does the searching as you type (See google search as an example)
- There is animated transition between pages

Happy Coding!
