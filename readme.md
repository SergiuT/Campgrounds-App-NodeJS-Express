# YelpCamp

You can see the final project deployed [here](https://stark-bastion-70241.herokuapp.com/).

## Initial Setup
* Add Landing Page
* Add Campgrounds Page that lists all campgrounds

Each Campground has:
   * Name
   * Image

## Layout and Basic Styling
* Create our header and footer partials
* Add in Bootstrap

## Creating New Campgrounds
* Setup new campground POST route
* Add in body-parser
* Setup route to show form
* Add basic unstyled form

## Add Mongoose
* Install and configure Mongoose
* Setup campground model
* Use campground model inside of our routes

## Auth Pt. 1 - Add User Model
* Install all packages needed for auth
* Define User model 

## Auth Pt. 2 - Register
* Configure Passport
* Add register routes
* Add register template

## Auth Pt. 3 - Login
* Add login routes
* Add login template

## Auth Pt. 4 - Logout/Navbar
* Add logout route
* Prevent user from adding a comment if not signed in
* Add links to navbar

## Auth Pt. 5 - Show/Hide Links
* Show/hide auth links in navbar 

## Refactor The Routes
* Use Express router to reoragnize all routes

## Users + Comments
* Associate users and comments
* Save author's name to a comment automatically

## Users + Campgrounds
* Prevent an unauthenticated user from creating a campground
* Save username+id to newly created campground

## Editing Campgrounds
* Add Method-Override
* Add Edit Route for Campgrounds
* Add Link to Edit Page
* Add Update Route

## Deleting Campgrounds
* Add Destroy Route
* Add Delete button

## Authorization Part 1: Campgrounds
* User can only edit his/her campgrounds
* User can only delete his/her campgrounds
* Hide/Show edit and delete buttons

## Editing Comments
* Add Edit route for comments
* Add Edit button
* Add Update route

<!--/campgrounds/:id/edit-->
<!--/campgrounds/:id/comments/:comment_id/edit-->

## Deleting Comments
* Add Destroy route
* Add Delete button

## Authorization Part 2: Comments
* User can only edit his/her comments
* User can only delete his/her comments
* Hide/Show edit and delete buttons
* Refactor Middleware

## Adding in Flash!
* Demo working version
* Install and configure connect-flash
* Add bootstrap alerts to header


## RESTful Routes

     NEW         /campgrounds/new       GET
     CREATE      /campgrounds           POST
     SHOW        /campgrounds/:id       GET
     EDIT        /campgrounds/:id/edit  GET
     UPDATE      /campgrounds/:id       PUT
     DESTROY     /campgrounds/:id       DELETE
