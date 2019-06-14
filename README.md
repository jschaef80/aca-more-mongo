# MongoDB Introduction

## Setup
Fork and clone this repo, then run `npm i` & `npm run start:dev`

NOTE: notice the ":dev". Make sure you run the above command exactly as written

## Investigation
Take a look at how the client folder is structured inside this project. We've put Create React App inside this project. 

## Tickets CRUD
Hints/Intructions are located in `express/controllers` and `express/routes` but are summarized here. You will be creating routes, controller functions, and mongoose functions (inside the controller functions) to access the data. 

### Prerequisite √√√
1. Add your connection string to the `mongoose.connect` function in index.js


### Part 1 - GET (Read)

1. In the routes folder (`express/controllers/tickets.js`), create a route for getting all the movies/tickets from the db. Create a controller function to go along with that. Finally, use the appropriate mongoose method to retrieve items from the database. 


### Part 2 - POST (Create)

1. In the routes folder (`express/controllers/tickets.js`), create a route for creating a ticket. Create a controller function to go along with that. Finally, use the appropriate mongoose method to create/insert an item into database. 

2. If done correctly, you should be able to "Create Movie" from the UI and it should show up in the list.

3. It should remain in the list when you refresh the page.


### Part 3 - DELETE (Delete)

1. In the routes folder (`express/controllers/tickets.js`), create a route for deleting a ticket by it's name. Create a controller function to go along with that. Finally, use the appropriate mongoose method to delete ONE item from database. 

2. If done correctly, you should be able to "Delete Movie" from the UI and it should be removed from the list.

3. It should remain removed from the list when the page is refreshed.

### Part 4 - GET (Read) - Again

1. In the routes folder (`express/controllers/tickets.js`), create a route for getting one ticket by it's id. Create a controller function to go along with that. Finally, use the appropriate mongoose method to find ONE item from database. 

2. When doing this.. research the ObjectId property of mongoose, you will need it

3. At this point you should be able to click the "details" link next to each movie in the UI and see the details
