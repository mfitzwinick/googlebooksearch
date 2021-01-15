# GOOGLE BOOK SEARCH

[![forthebadge](https://forthebadge.com/images/badges/works-on-my-machine.svg)](https://forthebadge.com)

## Purpose

The user can easily search for books on Google and save their favorites! They can delete past favorites to keep their reading list up to date.

## File structure

- Client files contain pages and components. A utils folder contains Axios API calls. An App.js and index.js helps to render the page using React.
  A "registerservice worker" file serves assets from local cache.
  This lets the app load faster on subsequent visits in production, and gives
  it offline capabilities.

- The controllers define the methods used. The models folder contains the database schema.

- The routes allow the user to navigate through the pages.

- Server.js to connect to the PORT

## Dependencies

- react
- react-dom
- react-router-dom
- axios
- express
- mongoose (mongo db)

### Acknowlegements

Thank you to Bryan Swarthout and Wilson Lamm at UCLA.
