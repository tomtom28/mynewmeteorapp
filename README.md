# :stars: Meteor-Gram :camera:

A `Meteor.js` app using `Iron Router`, `Blaze`, `SCSS` that allows user to take pictures using their laptop's webcam and then post them. Similiar to Instagram, other users can then click to like pictures.

Please check out the deployed version in Heroku [here](http://meteor-gram.herokuapp.com/)!



## Functionality

Within the `Meteor.js` framework, `MongoDB` is used to persist data. And `Materialize` is used as a styling framework.

Since this app was made during a walkthrough workshop, more information can be found [here](https://github.com/dannyvassallo/photofun).



## Cloning down the repo

If you wish to clone the app down to your local machine...
  1. Ensure that you have MongoDB set up on your laptop
    * An amazing repo to get you started with that can be found [here](https://github.com/dannyvassallo/mongo_lesson).
  2. Also ensure that you have Meteor installed on your laptop
    * Visit [https://www.meteor.com/](https://www.meteor.com/) to download a copy.
  3. Once you are set up, `cd` into this repo and run `meteor npm install`.
  4. Afterward, run `meteor` in Terminal to start up the app.
  5. Then, navigate to `localhost:3000` in your browser.



## Screenshots

#### Before login, all of the photos can be viewed but not voted on
![Not Signed In](/screenshots/Not Signed In.png)

#### To login, or to register, the Materialize package for Meteor includes a submission form
![Signed In](/screenshots/Sign In.png)

#### After login, users can like existing photos or add to the site by clicking the red plus button
![Signed In](/screenshots/Signed In.png)
Depending on your browser, you may need to adjust your privacy settings to be able to take a picture.

#### If the user is an Admin, they can adjust the admin status of any other users on the site
![Admin Menu](/screenshots/Admin Panel.png)
Admins are able to delete any image from the site, regardless of who posted it. Regular users can only delete their own posts.