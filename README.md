# The Shoppies App for the Movie Nominations

## Problem
For the Front-end Developer Intern position at Shopify, I was asked to create an app for the application that imitates the Oscars known as 'The Shoppies App' that uses the OMDB API and fetches movie data from it.

Link to the Problem Document: [Problem Statement Documentation](https://docs.google.com/document/d/1AZO0BZwn1Aogj4f3PDNe1mhq8pKsXZxtrG--EIbP_-w/edit)

## Implementation
### Overview
All the required features that have been implemented:
- Search results should come from OMDB's API (free API key: http://www.omdbapi.com/apikey.aspx).
- Each search result should list at least its title, year of release and a button to nominate that film.
- Updates to the search terms should update the result list
- Movies in search results can be added and removed from the nomination list.
- If a search result has already been nominated, disable its nominate button.
- Display a banner when the user has 5 nominations.

There were extra things I added in:
- Storing nomination data and the theme into local storage
- Added more movie information so that the user is benefitted  more.
- Dark Theme(For Dark theme lovers!!)

### Things I learned from this project
This project helped me understand how important React and Redux are since these tools allow us to handle multiple components in an application which makes a big difference when the application is scaled and complexity increases. 

