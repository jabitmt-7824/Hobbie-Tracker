# Habit/Hobbie Tracker

### Features
1) Add multiple habits to track like reading a book, going to the gym etc
2) Delete a hobbie/habit when required
3) Track each habit everyday. These are the 3 statuses of a habit:
     + Done - Mark the habit as done for a day
     + Not done - Mark the habit as not done for a day
     + None - User did not take any action on a habit for a day


### Database Models
1) Hobbie (name)
2) Status (hobbie_id,date,status)

###  Folder Structure
> assets
  + css
    + addForm.css // style for form page for adding new hobbie/habit
    + calenderView.css // style for page for calnder view of hobbies for tracking
    + home.css // style for home page
    + layout.css // common style for all pages
> config
  + moongose.js //for database connection
> controllers
  + hobbieController.js // contain all controllers related hobbies/habits
> Models
  + hobbie.js
  + status.js
> routes
  + index.js // contain all routes
> views
  + addForm.ejs // form for adding new hobbie/habit
  + calenderView.ejs // calnder view of hobbies for tracking
  + home.ejs // home page
  + layout.ejs // common layout view for all pages
> index.js
> package.json
> package-lock.json

### how to start
npm start
