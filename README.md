This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Populate Github Repositories

Hi fren!

This is a React exercise where we'll use the Github API to fetch repositories and display them on a page (and other cool things).

### User stories

- As a user, I want to fetch all Github repositories above 25k stars and display the repo name and star count (stargazers_count) on screen
- As a user, I want some indication that data is being fetched
- As a user, I want to be able to specify the stars-count theshold that determines which which repos will be displayed
- As a user, I want to click on one of the rows and be taken to a "Repo details" view that contains repo name, stargazers_count, forks_count, and a link to the repository (html_url). Please use component state for this instead of using a library like react-router
- As a user, I want a "Back" button to return to the list of repos
- As a user, I want results to be paginated with 5 repos on each page
- As a user, I want everything to be styled and look good

### Setup

After cloning this repository:

- Run `npm install` to install dependencies
- Run `npm start` to start up the app

### Github API

We'll be using the following Github endpoint in our code [as documented here](https://developer.github.com/v3/search/#search-repositories). Here's an example of the endpoint we will be submitting requests to:

https://api.github.com/search/repositories?q=stars:>25000&sort=stars&order=desc
