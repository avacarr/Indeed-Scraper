# Indeed-Scraper
  > SEI - Software Engineering Project 4
  > 
  > Created By: Alex Carr

### Indeed-Scraper
  The concept behind this is to create a smarter solution for job searching through indeed job opportunities based on some information entered by a user. 
  
  
### MVP
    - Home Page
      - Welcoming and showing login/signup button while start searching jobs button.
    - User Page
      - Shows all jobs saved, and past search history.
    - Show All Page
      - Resource type shows all data and allows for multiple page scrolls.
    - Show Page
      - Shows all data pertinent to the job selected.


### Stretch Goals
    - Users can log in using various methods offered. (OAuth)
    - Users can see best match counts on previous searches
    - Creating visually relaxing front-end
    - Pagination

### Tech Stack

#### Front-End
    - React
    - HTML
    - CSS
    - JavaScript
#### Back-End
    - Express
    - Morgan
#### Back-End
    - MongoDB


### List of Mongoose models and their properties
```js
//  Primary Model
User = {
  first_name: String,
  last_name: String,
  email: String,
  search: [{
    type: String,
    value: String
  }],
  search_history: [{
    type: String,
    value: String
  }],
  saved: [{
    title: String,
    company: String,
    location: String,
    summary:  String,
    url: String,
    postDate: String,
    salary: String,
  }],
}
```


### User Stories
    - As an unlogged-in user, I would like to be able to browse all the jobs.
    - As an unlogged-in user, I would like to be able to set the search parameters.
    - As an unlogged-in user, I would like to have the option to login/signup on any page.
    - As a logged-in user, I would like to be able to save jobs.
    - As a logged-in user, I would like to have a user page that displays all saves.
    - As a logged-in user, I would like to have the option to see my previous searches.


### Wireframe

#### Home View
   ![Home](https://user-images.githubusercontent.com/102195632/188215676-f2c31e4c-912c-4cbd-93a6-4569d6aa04b6.png)


#### User View
  ![User](https://user-images.githubusercontent.com/102195632/188217221-28d74a82-731d-4da1-bd98-a49e2dfeaf06.png)

#### Show All View
  ![Show All](https://user-images.githubusercontent.com/102195632/188217951-2c90d7cc-db36-410b-aada-4b6f40762c99.png)

#### Show View
  ![Show](https://user-images.githubusercontent.com/102195632/188218381-6d677721-9830-47f4-8fd7-dbc36097007f.png)

  
