<!-- ⚠️ This README has been generated from the file(s) "blueprint.md" ⚠️--><p align="center">
  <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/logo-shadow.png" alt="Logo" width="150" height="150" />
</p>
<h1 align="center">@appnest/readme</h1>
<p align="center"> 
<a href="https://www.npmjs.com/package/@appnest/readme"><img alt="NPM Version" src="https://img.shields.io/npm/v/@appnest/readme.svg" height="20"/></a>
<a href="https://david-dm.org/andreasbm/readme"><img alt="Dependencies" src="https://img.shields.io/david/andreasbm/readme.svg" height="20"/></a>
 
<!-- <a href="https://github.com/badges/shields"><img alt="Custom badge" src="https://img.shields.io/badge/custom-badge-f39f37.svg" height="20"/></a> -->
<a href="https://github.com/andreasbm/readme/graphs/commit-activity"><img alt="Maintained" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" height="20"/></a>
	</p>

<p align="center">
  <b>Named this website socialNetwork inspired from day to day many social app.
Here are some required future like 
<li>a) Implementing friend 
<li>b)chatting-> chatting between friends and storing messages in database
 <li>c)posts ->images,qoutes
<li>d)user wall ,recent posts by user
<li>e)adding more social authentication strategy (Githu<li>b) like passport,google authentication.
<li>f)profile page contain about user,photos, email id and many more
<li>g)Reactions to Posts and Comments</b></br>

   
Start with most important part in code is authentication in  code,whenever we tried login 
or sign up in page ,you get too the some data is specific  for you only and your email or
 your on wall render on filed,this is possible beacuse you logged in as you ,you establish
 your identity to that  website,this is more fundamental and core  part for every website.
<br/>
And we recieved some email notification  from this  website as your post got like,comments,
or you active online you will recive that email or that is something while user look up to. 
<br/><p>
Deleting and updating objects in database + distributing Views ,so we need authorize which user 
have to delete comment which  not,more  over user can edit his/her name ,change profile,
email and <h2>a many more functinally are done in this project. </h2>
</p>

 
</p>

<br />
<br/>
<br/>

## MVC Framework
<p>
 The MVC (Model-View-Controller) is an architectural pattern that
separates an application into three main logical components:<br/>
the model, the view, and the controller. Each of these components
</p>
are built to handle specific development aspects of an application. 


[![Social Network](https://i.postimg.cc/Z5DycP05/social0main.png)](https://postimg.cc/SnCsQMWB)

* **Simple**: Extremely simple to use - so simple that it almost feels like magic!
* **Powerful**: Customize almost everything - add your own templates and variables if you like.



# SOCIAL NetWork 


 

<!-- <summary>    </summary> -->

<br />



[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)]( )

# ➤ 📖 Working With these 
<br/>

* [➤ Installation](#-installation)
1. [➤ Getting Started (quick)](#-getting-started-quick)
   * [Usage](#usage)
   * [Configuration](#configuration)

 

2. [➤ Templates](#-templates)
	* [Title](#title)
	* [Description](#description)
	* [Table of Contents](#table-of-contents)
 
 

3. [➤Setting Up Directory Structure](#-directory)
	* [Starting Express  ](#startingexpress )
	* [ Adding Git & NPM Start ](#add-git)
	* [ Setting up the Express Router ](#setting-up-router )
	* [ Create a Controller ](#create-controller )
	* [Create another Controller & Router  ](#crete-controller-router )
	* [ Installing EJS & Set Up the View Engine](#enstall-ejs)
	* [ Create a view for home ](#create-viw)
	* [ Implementing Partials ](#implimenting-particles)
	* [ Static Files For Pages ](#static-files)

  
4. [➤ Databases:: An Introduction](#-DatabasesAnIntroduction)
	* [MongoDB :: Terms ](#mongodb)
	* [Creating the DB Schema ](#Schema)
	* [Fetching Data from DB  ](#populating )
	 
   * [ Connecting to MongoDB using Mongoose](#-connecting-Mongoose)
   * [ Linking our MongoDB using Mongoose ](#likingMongoDB)

 
5. [➤Manual Authentication](#-manual-authentication)
	* [ Setting up User Schema ](#setup_userSchema)
	* [ Rendering Pages for Sign up and Sign in ](#renderpages)
	* [ Explaining Cookies  ](#cookies)
	* [ Creating and Alternating a Cookie ](#creating-cookie )
	* [ User Sign Up](#user-signup)
	* [ User Sign In ](#userSignin)
	* [ Show Details of Signed in User ](#showdetail )
  

6. [➤ Authentication Using Passport](#-Authentication-Using-Passport)
	* [ Glancing through and Installing Passport.js ](#install-passport )
	* [ Setting up Passport.js ](#set-up-passport)
	* [ Express sessions and using passport for authentication ](#Express-sessions-and-using-passport-for-authentication )
	* [ Setting Current Authenticated User ](#Setting-Current-Authenticated-User)
	* [ Passing User data to views and restricting page access ](#Passing-User-data-to-views-and-restricting-page-access )
	* [ Setting up Mongo store for session cookies ](#Setting-up-Mongo-store-for-session-cookies )
	* [ Creating Sign Out ](#Creating-Sign-Out)

 
 

7. [➤ SASS](#-a-bit-about-this-readme)
	* [ SCSS or SASS? ](#SCSS-or-SASS)
	* [ Setting Up SCSS ](#Setting-Up-SCSS )
	* [  Using SCSS](#Using-SCSS)

 
 

8. [➤ Database Relations (Posts, Comments)](#-database-realtion)
	* [ Node.js:: Explaining ](#Node.js:-Explaining)
	* [ Creating Schema for Posts ](#Creating-Schema-for-Posts )
	* [ Saving Posts to the DB ](#Saving-Posts-to-the-DB )
	* [Display Post and Related User ](#Display-Post-and-Related-User  )
	* [ Check Authentication on Creating Post ](#Check-Authentication-on-Creating-Post-)
	* [ Creating Schema for Comments ](#Creating-Schema-for-Comments )
	* [ Nesting Population:: Display Comments and Related User ](#Nesting-Population::-Display-Comments-and-Related-User )
	* [ Adding Comments to the DB ](#Adding-Comments-to-the-DB )

 
 

9. [➤ Deleting and Updating Object in Database + Distributing Views!](#-DeltingandpdatingObject )  
	* [ Deleting a Post (Authorized)](#Deleting-a-Post-(Authorized) )
	* [ Deleting a Comment (Authorized) ](#Deleting-a-Comment-(Authorized)-)
	* [ Distributing the Code into Partials ](#Distributing-the-Code-into-Partials )
	* [User Profile links  ](#User-Profile-links )
	* [ Updating a User’s profile ](#Updating-a-User’s-profile )
 
 


10. [➤  Async Await + Error Handling](#Async-Await-+-Error-Handling )
	* [Converting to Async Await ](#Converting-to-Async-Await )
	* [ Converting More Code to Async Await ](#-Converting-More-Code-to-Async-Await )

 
 

11. [➤ Flash Messages:: Introduction ](#Flash-MessagesIntroduction )
	* [ Creating Flash Messages ](#Creating-Flash-Messages )
	* [Introducing Noty  ](#Introducing-Noty )
	* [ Adding Flash Messages to more Actions ](#Adding-Flash-Messages-to-more-Actions )
 
 
 
  
12. [➤ Converting to Ajax ](#Converting-to-Ajax )
	* [ Creating a Post:: Sending Data ](#Creating-a-Post::-Sending-Data )
	* [ Creating a Post:: Receiving Data ](#Creating-a-Post::-Receiving-Data  )
	* [ Deleting a Post ](#Deleting-a-Post )

 
 

13. [➤ File Upload ](#file-uploading )
	* [ Uploading Files: How Does It Work? ](#Uploading-Files:-How-Does-It-Work? )
	* [ Installing Multer + Documentation ](#Installing-Mult+-Documentation)
	* [ Configuring Multer for User Avatar ](#Configuring-Multer-for-User-Avatar )
	* [ Saving File from Params ](#Saving-File-from-Params )
	* [ Showing the Avatar, Connecting the Dots ](#Showing-the-Avatar-Connecting-the-Dots )
	* [ Edge Case:: Replacing an Avatar  ](#Edge-Case::-Replacing-an-Avatar )
 
 
 

14. [➤APIs  ](#Api )
	* [ APIs:: Why and What ](#APIs::-Why-and-What )
	* [  The Postman](#The-Postman )
	* [ Setting Up The Directory Structure ](#Setting-Up-The-Directory-Structure)
	* [ Rendering an AP  ](#Rendering-an-AP )
	* [ Playing With APIs ](#Playing-With-APIs )
	* [ Authentication With APIs:: JWT { JSON Web Tokens } ](#Authentication-With-APIs::-JWT-{-JSON-Web-Tokens-} )
	* [ Setting Up Passport JWT ](#Setting-Up-Passport-JWT )
	* [Creating a Token  ](#Creating-a-Token)
	* [ Authentication And Authorization ](#Authentication-And-Authorization )
 
 


15. [➤ Social Authentication  ](#Social-Authentication )
	* [ Creating Credentials on Google ](#Creating-Credentials-on-Google )
	* [ Social Authentication:: How does it work ](#Social-Authentication::-How-does-it-work )
	* [Setting up Passport - Google - OAuth  ](#Setting-up-Passport---Google---OAuth )
	* [ Using Google Auth:: With a Link ](#Using-Google-Auth::-With-a-Link )
 
 
 
16. [ ➤ Parallel Jobs + Mailer  ](#Parallel-Jobs-+-Mailer- )
	* [Setting Up Nodemailer  ](#Setting-Up-Nodemailer )
	* [ Sending Our First Email via SMTP ](#Sending-Our-First-Email-via-SMTP )
  * [ Send HTML Template Emails ](#Send-HTML-Template-Emails )
	* [  Introduction to Delayed Jobs](#Introduction-to-Delayed-Jobs )
        * [Installing and Understand KUE ](#Installing-and-Understand-KUE ) 
	* [Setting KUE and Using It  ](#Setting-KUE-and-Using-It )

 
 


17. [ ➤  Friends + Likes ](#Friends-+-Likes )
  * [ Polymorphic Relations ](#Polymorphic-Relations )
  * [ Schema Setup:: Likes ](#Schema-Setup::-Likes )
  * [Actions and Routes:: Likes  ](#Actions-and-Routes::-Likes  )
	* [ Making Friendships ](#Making-Friendships )
* [Understanding the Code:: Friendship  ](#Understanding-the-Code::-Friendship ) 
 
 


18. [ ➤ Chatting Engine  ](#Chatting-Engine  )
	* [ Reaching Sockets ](#Reaching-Sockets )
	* [  Understanding the Chat Box](#Understanding-the-Chat-Box )
  * [ Setting Up Socket.io ](#Setting-Up-Socket.io-)
	* [ Beginning the Initial Connection ](#Beginning-the-Initial-Connection )
	* [ Time to Create and Join Chat Rooms ](#Time-to-Create-and-Join-Chat-Rooms) 
	* [ Finally, Let’s Send and Receive Messages. ](#Finally,-Let’s-Send-and-Receive-Messages )
  
 
 




* [➤ Future work](#-future-work)
* [➤ FAQ](#-faq)
	* [Can I see how my README file is going to look before I commit it?](#can-i-see-how-my-readme-file-is-going-to-look-before-i-commit-it)
	* [How can I get involved?](#how-can-i-get-involved)
	* [I already have a large README file - I don't have time to rewrite everything!](#i-already-have-a-large-readme-file---i-dont-have-time-to-rewrite-everything)
	* [How can I support you?](#how-can-i-support-you)
 
 


[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#installation)

## ➤ Installation

```node
npm install 
```

If you don't want to install anything you can use the `npm install  ` command instead.

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#getting-started-quick)

## ➤ Getting Started (quick)

This getting started guide is super quick! Follow these two steps and you will have run

1. npm install nodemon
2. Run `npm start`

 


[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#getting-started-slower)
  


### Configuration
-  Partials (Partial code put into another file) - The advantage of EJS is that it
combines data and a template to produce HTML. This makes our code scalable and
manageable. One of the most important features of EJS is its use of partials. Using
partials, you may write a piece of code just once, and use it at many places as and
when required.<br/>
-  Whenever we have some piece of code that is either very long or a piece of code
that is used again and again in different files, we may store that in a separate file,
and then re-use it wherever it needs to be added. One such example would be the
creation of a NavBar

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#templates)

 

### Title

##
 SOCIAL NETWORK

<h1 align="center">@appnest/readme</h1>

The important thing to note here is that the template automatically reads your `package.json` file and inserts the `name` from the package.

```json
{
  "name": "@appnest/readme"
}
```

That's cool.  


The logo template adds a logo to your readme and looks like this:

 

```json
{
  "logo": {
    "src": "https://raw.githubusercontent.com/readme/master/assets/logo-shadow.png",
    "width": "150"
  }
}
```







### Starting Express

Install express using {npm install express}.

 -  Interpolation - Instead of using (,) or (+) for concatenating two strings, we can embed
our variable inside {} the string using backticks (``).
-  To include the variable inside the string this should be done “${``}”. So Instead of
those [console.log(“Error: ”, err)], we can do [console.log(`Error: ${err}`)].
-  Anything inside [${}] is to be evaluated.
-  Run command {nodemon index.js} to run the server.
<br />

```node 
const express = require('express');
const app=express();
const port=800;
app.listen(port, function(err){
    if (err){
        console.log(`Error in running the server: ${err}`);
    }

    console.log(`Server is running on port: ${port}`);
});

```
### Adding Git & NPM Start 
To make the project scalable we need to take care of some important points -<br/>
- We need to initiate the project as a git repository to track all of the changes that
were done.
- Different branches for different features.


 



### Setting up the Express Router
-  In the routes, folder create a new file {index.js}, which is the entry point for all the
routes.
-  The App index.js file will send in the request to the routes/index and this will further
route us to all the different routes files that will be present in the website code.
-  Express contains a module, express. router, which will help in separating the app
routes and the controller.
-  To check whether the routes are loaded, we will use the console.log in routes
{index.js}

```node
const express = require('express');

const router = express.Router();
console.log('router loaded');

module.exports=router;
```

### Create a Controller

After route setup, it’s time to set up the controller {Action that is taken up for any route}. A
group of actions bundled together is known as a controller.

Create a new inside controller {home_controller.js}
```node
	router.get('/',homeController.hom);
```

```node
module.exports.home=function(req,res);

```
### Create another Controller & Router

Create more routes and more controllers and commit the changes till now

```node
const homeController = require('../controllers/home_controller');

```
```node

router.get('/', homeController.home);
router.use('/users', require('./users'));
```
- Any request to the home page goes to homeController.home, any
request to /users goes the users route and where further mapping is
done

### Installing EJS & Set Up the View Engine

App. set is an object where different properties are predefined {keys are present}.
Whenever we put a value of those keys, the express app takes up those values and does
something with those values. The view and view engine property is also defined here

```node

// set up the view engine
app.set('view engine', 'ejs');
app.set('views', './views');

```

### Implementing Partials
```node
<%- style %>
        
     

    <body>
        <%- include('_header'); %>

       
        
        <main id="layout-main">
            <%- body %>
	<body>		
```

#### Static Files For Pages
```node
app.use(expressLayouts);
// extract style and scripts from sub pages into the layout
app.set('layout extractStyles', true);
app.set('layout extractScripts', true);

```


### Linking our MongoDB using Mongoose
Inside the config folder create a new file { mongoose.js }.
-  Install mongoose { npm install mongoose }.
-  Require mongoose in { mongoose.js }.
-  We need to provide a connection to the database
-  Whenever there is an error while connecting to the database we need to console
that, This will display the console.log like an error.
-  If the database is connected properly one callback function will be called.
-  To make that {mongoose.js } file usable we need to export it.
-  Require mongoose in { inde.js } [Entry point].


```node

const db=require('./config/mongoose');
```



[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#table-of-contents)
 

### Databases:: An Introduction

The Databases:: An Introduction template adds the list of Databases:: An Introduction and looks like this:


#### MongoDB :: Terms
-  MongoDB stores the data in the form of JSON.
-  Suppose we have to store the details of a student in the JSON format. So all the
characteristics of a student will be in the form of Field and each of the Field has a

#### Installing MongoDB, Robo3T, and Moongoosejs
 We need to install MongoDB and check whether it is installed or not.
EXTRA: You can install MongoDB according to the OS you are using.
https://www.mongodb.com/try/download/community
-  To check that the MongoDB has been installed, type the command { mongo } in the
terminal. This will take you to the Mongo Shell if the MongoDB has been installed.
-  We need to install Robo3T - { It is a tool to visualize the database }.
EXTRA: You can install Robo3T according to the OS you are using.
https://robomongo.org/
-  We need to install Mongoose


#### Connecting to MongoDB using Mongoose

We have to set up the configuration so that the express server can interact with the
database { MonogDB } using the layer in between that is called Mongoose.
-  We need to create another folder in the project and name it as { config }.
-  Inside the config folder, we need to create a file { mongoose.js }.
-  Inside the file, we need to require the mongoose.
EXTRA: You can read about Mongoose using the following link https://mongoosejs.com/

```node
const mongoose = require('mongoose');
mongoose.connect('mongodb://localhost:27017/test', {useNewUrlParser: true, useUnifiedTopology: true});

const Cat = mongoose.model('Cat', { name: String });

const kitty = new Cat({ name: 'Zildjian' });
kitty.save().then(() => console.log('meow'));

```


#### Creating the DB Schema
Schema is the definition of what fields would be there in one document.
-  A document needs a schema to define in mongoose. Mongoose then populates the
model or the collection using the schema.
-  When we are storing in an array of different documents we need to pre-define the
fields that we are using

```node

const userSchema = new mongoose.Schema({
    email: {
        type: String,
        required: true,
        unique: true
    },
    password: {
        type: String,
        required: true
    },
    name: {
        type: String,
        required: true
    },
    avatar: {
        type: String
    },
    friendships: [
        { 
            type: mongoose.Schema.Types.ObjectId,
            ref: 'Friendship' 
        }
    ]

}, {
    timestamps: true
});

```

#### Fetching Data from DB

-  We have submitted the data using the form and it gets entered into the database as
a document.
-  We need to render the data that we have submitted on the home page { home. ejs }.
-  We need to fetch all the contact in the database and store into the variable, then
pass it onto the template or the view






[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#-manual-authentication)
 

 # ➤ Manual-authentication
 To establish the identity manually then we
will look at the drawbacks { extra code that we have to write }. Then we will be using a
library for authentication.

### Setting up User Schema
Whenever you create a new object the database should store a field called created
at and whenever you update that object the database should store a field called
updated at which gets updated. These two fields are managed by the mongoose
itself using the timestamps property

```node
const express = require('express');
const router = express.Router();
const passport = require('passport');

const usersController = require('../controllers/users_controller');


```
### Rendering Pages for Sign up and Sign in
-  We will create two files inside the views folder - { user_sign_in.ejs } and {
user_sign_up.ejs }.
-  To render these pages we need to have some controllers.
-  In { users_controller.js } we have to create some actions for the sign-up page and
sign-in page.
-  We have to render the { user_sign_up.ejs } and { user_sign_in.ejs } files though
actions.
-  Inside the routes folder in { users.js } file, we have to create routes for the two
pages.
-  The type of request for both pages will be a GET request.

### Explaining Cookies
- Browser is the environment in which the cookies reside. Thus, if free space is filled
by the cookies in the browser, it will automatically clear all the cookies present over
there.

### Creating and Alternating a Cookie
- For reading and writing into cookies, we will be using a library called cookie-parser.
-  Install the library using the command { npm install cookie-parser }.
-  Require the installed library in the { index.js file }.
-  We have to tell the app to use the library in the middleware.
-  We have to set up the cookie parser using the app. use method. {
app.use(cookieParser()}
```node

app.use(express.urlencoded());

app.use(cookieParser());

app.use(express.static('./assets'));
// make the uploads path available to the browser
app.use('/uploads', express.static(__dirname + '/uploads'));

```
### User Sign Up  & User Sign In
- There can be two cases-
○ If the user already exists, we do not need to recreate his data.
○ If the user does not exist in the database, we will store all the data we have
collected in the database.

```node 
const User = require('../models/user');
const fs = require('fs');
const path = require('path');

// let's keep it same as before
module.exports.profile = function(req, res){
    User.findById(req.params.id, function(err, user){
        return res.render('user_profile', {
            title: 'User Profile',
            profile_user: user
        });
    });

}



// render the sign up page
module.exports.signUp = function(req, res){
    if (req.isAuthenticated()){
        return res.redirect('/users/profile');
    }


    return res.render('user_sign_up', {
        title: "Codeial | Sign Up"
    })
}


// render the sign in page
module.exports.signIn = function(req, res){

    if (req.isAuthenticated()){
        return res.redirect('/users/profile');
    }
    return res.render('user_sign_in', {
        title: "Codeial | Sign In"
    })
}

// get the sign up data
module.exports.create = function(req, res){
    if (req.body.password != req.body.confirm_password){
        req.flash('error', 'Passwords do not match');
        return res.redirect('back');
    }

    User.findOne({email: req.body.email}, function(err, user){
        if(err){req.flash('error', err); return}

        if (!user){
            User.create(req.body, function(err, user){
                if(err){req.flash('error', err); return}

                return res.redirect('/users/sign-in');
            })
        }else{
            req.flash('success', 'You have signed up, login to continue!');
            return res.redirect('back');
        }

    });
}

// sign in and create a session for the user
module.exports.createSession = function(req, res){
    req.flash('success', 'Logged in Successfully');
    return res.redirect('/');
}

module.exports.destroySession = function(req, res){
    req.logout();
    req.flash('success', 'You have logged out!');


    return res.redirect('/');
}


```



[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#-Authentication-Using-Passpor)

# ➤ Authentication Using Passport
### Setting up Passport.js
-  We need to find out whether the user with a particular username and password
exists or not.
-  If the user having a particular username and password exists, then we are required
to set that user in the cookie.
-  Passport.js uses a session cookie { session cookie stores all the session information
plus it is encrypted }.
-  In the config folder create a new file { passport-local-strategy }.
-  Require passport in the { passport-local-strategy } file.
-  Require passport-local-strategy inside the same file.
-  We need to tell the app to use the passport session.
-  Passport also helps in maintaining the session.
-  Inside the file { users_controller.js } we need to redirect the page after the session
is created successfully in the passport.

```node 

const express = require('express');
const router = express.Router();
const passport = require('passport');

const usersController = require('../controllers/users_controller');

router.get('/profile/:id', passport.checkAuthentication, usersController.profile);
router.post('/update/:id', passport.checkAuthentication, usersController.update);

router.get('/sign-up', usersController.signUp);
router.get('/sign-in', usersController.signIn);


router.post('/create', usersController.create);

// use passport as a middleware to authenticate
router.post('/create-session', passport.authenticate(
    'local',
    {failureRedirect: '/users/sign-in'},
), usersController.createSession);


```
passport-local-strategy
```node
const passport = require('passport');

const LocalStrategy = require('passport-local').Strategy;

const User = require('../models/user');


// authentication using passport
passport.use(new LocalStrategy({
        usernameField: 'email',
        passReqToCallback: true
    },
    function(req, email, password, done){
        // find a user and establish the identity
        User.findOne({email: email}, function(err, user)  {
            if (err){
                req.flash('error', err);
                return done(err);
            }

            if (!user || user.password != password){
                req.flash('error', 'Invalid Username/Password');
                return done(null, false);
            }

            return done(null, user);
        });
    }


));


// serializing the user to decide which key is to be kept in the cookies
passport.serializeUser(function(user, done){
    done(null, user.id);
});



// deserializing the user from the key in the cookies
passport.deserializeUser(function(id, done){
    User.findById(id, function(err, user){
        if(err){
            console.log('Error in finding user --> Passport');
            return done(err);
        }

        return done(null, user);
    });
});


// check if the user is authenticated
passport.checkAuthentication = function(req, res, next){
    // if the user is signed in, then pass on the request to the next function(controller's action)
    if (req.isAuthenticated()){
        return next();
    }

    // if the user is not signed in
    return res.redirect('/users/sign-in');
}

passport.setAuthenticatedUser = function(req, res, next){
    if (req.isAuthenticated()){
        // req.user contains the current signed in user from the session cookie and we are just sending this to the locals for the views
        res.locals.user = req.user;
    }

    next();
}



module.exports = passport;
```
 
### Setting Current Authenticated User
- Once the user is signed in, set the users for the views using the
setAuthenticatedUser function that will again take three parameters req, res, and
next. This function will internally use the isAuthenticated function that is present in
passport.js in which the req. user contains the currently signed-in user from the
session cookie

### Passing User data to views and restricting page access
### Creating Sign Out
these thopics discuss above



[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#manual-authentication)
# ➤   SASS
SCSS and SASS are two different ways of writing CSS.

### SCSS or SASS

-  SCSS is the most commonly used and SASS is called the indented syntax.
-  SCSS stands for ( Sassy Cascading Style Sheets ) and it’s an extension of CSS which
adds nested rules, variables, mix in selectors, inheritance, and a lot more features.
-  Sass (Syntactically Awesome Style Sheets) is an extension of CSS that enables you
to use things like variables, nested rules, inline imports, and more. It also helps to
keep things organized and allows you to create stylesheets faster.
-  At the end of it, both SASS and SCSS are converted to look like CSS because
browsers only understand CSS.
-  In SCSS, we need brackets and semicolons for the styling properties but in SASS we
don’t need brackets and semicolons.


### Setting Up SCSS
Source - Path from where we pick up the SCSS files to convert them into CSS.
-  Destination - Path where we put the CSS files.
-  Debug Mode - Whatever information we see while the server is running over the
terminal, do we want to display some error that is there in the compilation of files
while conversion. If yes then set it to true. {If it is in production mode then we have
to set it to false }.
-  OutputStyle - Do we want everything to be in a single line or do we want it in
multiple lines. If we want in multiple lines then use “extended” otherwise
“compressed”.
-  Prefix - It is basically the location where the server should look for the CSS files

 ```node
 
app.use(sassMiddleware({
    src: './assets/scss',
    dest: './assets/css',
    debug: true,
    outputStyle: 'extended',
    prefix: '/css'
}));

 ```

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#Authentication Using Passport)


## ➤  Database Relations (Posts, Comments)
### Creating Schema for Posts
We need to create a schema for posts and link it to the users. Whenever a post is
posted on a website it has to be coming from a user, someone who is logged in.
Thus, a post needs to have a user in it.
- We need to create a file inside the models folder { post.js }.
- We need to import mongoose inside the file { post.js }.
- For creating a schema we need to use mongoose.Schema method, which will
contain multiple fields.
- Timestamps automatically introduce two fields created at and updated at.

```node
const mongoose = require('mongoose');

const postSchema = new mongoose.Schema({
    content: {
        type: String,
        required: true
    },
    user: {
        type:  mongoose.Schema.Types.ObjectId,
        ref: 'User'

    },
    // include the array of ids of all comments in this post schema itself
    comments: [
        {
            type:  mongoose.Schema.Types.ObjectId,
            ref: 'Comment'
        }
    ],
    likes: [
        {
            type: mongoose.Schema.Types.ObjectId,
            ref: 'Like'
        }
    ]
},{
    timestamps: true
});

const Post = mongoose.model('Post', postSchema);
module.exports = Post;
```
### Saving Posts to the DB
We need to import the post schema that we have created inside the models folder.
```node

module.exports.create = async function(req, res){
    try{
        let post = await Post.create({
            content: req.body.content,
            user: req.user._id
        });
        
        if (req.xhr){
            // if we want to populate just the name of the user (we'll not want to send the password in the API), this is how we do it!
            post = await post.populate('user', 'name').execPopulate();

            return res.status(200).json({
                data: {
                    post: post
                },
                message: "Post created!"
            });
        }

        req.flash('success', 'Post published!');
        return res.redirect('back');

    }catch(err){
        req.flash('error', err);
        // added this to view the error on console as well
        console.log(err);
        return res.redirect('back');
    }
  
}

```
### Display Post and Related User
### Check Authentication on Creating Post
### Nesting Population:: Display Comments and Related User


[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#Authentication Using Passport)

# ➤ Deleting and Updating Object in Database + Distributing Views
### Deleting a Post (Authorized)
-  The first step is to learn how to delete a post. While deleting the post, we need to
remember that there are comments associated with the posts therefore we need to
delete all the comments as well.
-  To delete the post we need to create an action. The same action will delete the
comments associated with the post.
-  We need a route that maps to that action.
-  We need to place a link to the route that we created to map the actions.
-  We will be making this format of the route- “ /posts/destroy/id “ where id will be
the string params.
-  Before deleting any post, we need to find whether that post id exists in the database
or not.

## Setting Up Directory Structure

 - Create a new folder in your workstation {SOCIAL NETWOKR}
 - Create a new file which is the entry point {index.js}.
- Create multiple directories for a scalable project using terminal
{mkdir routes controllers models views config}
-  According to routes, which function would be called routes will be stored in the
controllers folder mapped into different files.
- Views will contain different HTML files
```node


module.exports.destroy = async function(req, res){

    try{
        let post = await Post.findById(req.params.id);

        if (post.user == req.user.id){

            // CHANGE :: delete the associated likes for the post and all its comments' likes too
            await Like.deleteMany({likeable: post, onModel: 'Post'});
            await Like.deleteMany({_id: {$in: post.comments}});



            post.remove();

            await Comment.deleteMany({post: req.params.id});


            if (req.xhr){
                return res.status(200).json({
                    data: {
                        post_id: req.params.id
                    },
                    message: "Post deleted"
                });
            }

            req.flash('success', 'Post and associated comments deleted!');

            return res.redirect('back');
        }else{
            req.flash('error', 'You cannot delete this post!');
            return res.redirect('back');
        }

    }catch(err){
        req.flash('error', err);
        return res.redirect('back');
    }
    
}
```
#### Deleting a Comment (Authorized)
#### Authorization on different levels -
-  At the view level - show the button only if the user is authorized to.
-  At the Router level - Allow the user to be able to send the request only when the
user is logged in.
-  At the action level inside the controller - Allow the post to be deleted only if the post
and the user that is sending the request are the same.

### Distributing the Code into Partials
```node
<link rel="stylesheet" href="/css/post.css" />
<link rel="stylesheet" href="/css/home.css" />
<link rel="stylesheet" href="/css/chat_box.css" />

<div id="home-container">
  <section id="feed-posts">
    <h2 class="fw7 bg-text-clip shine">Posts</h2>
    <% if(locals.user){ %>
    <form action="/posts/create" id="new-post-form" method="POST">
      <textarea
        style="background-color: rgb(236, 223, 104)"
        name="content"
        cols="30"
        rows="3"
        placeholder="Type Here..."
        required
      ></textarea>
      <input type="submit" value="Post" />
    </form>
    <% } %>

    <div id="posts-list-container">
      <ul style="list-style: none">
        <% for(post of posts){ %> <%- include('_post') -%> <%} %>
      </ul>
    </div>
  </section>

  <section id="user-friends">
    <h4>Friends</h4>
    <% for(u of all_users){%>
    <p>
      <a href="/users/profile/<%= u.id %>"><%= u.name %></a>
    </p>
    <% } %>
  </section>

  <%- include('_chat_box') -%>
</div>

<!-- importing this script for creating the comments -->
<script src="/js/home_post_comments.js"></script>
<script src="/js/home_posts.js"></script>

<!-- CHANGE :: import the script file for toggle likes, also run it over for the already present posts and comments on the page -->
<script src="js/toggle_likes.js"></script>
<script>
  $(".toggle-like-button").each(function () {
    let self = this;
    let toggleLike = new ToggleLike(self);
  });
</script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/socket.io/2.2.0/socket.io.js"></script>
<script src="/js/chat_engine.js"></script>
<% if (locals.user){ %>
<script>
  new ChatEngine(
    "user-chat-box",
    "<%= locals.user.email %>",
    "<%= locals.user.name %>"
  );
</script>
<% } %>

```



### Updating a User’s profile
### User Profile links




[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#Authentication Using Passport)


# ➤Async Await + Error Handling
 ### Converting to Async Await
Asynchronous - When the task is running on the CPU at the same time the main thread of
the node.js server is executing something else. Asynchronous code doesn't have to wait –
the program can continue to run. We can do this to keep the site or app responsive,
reducing waiting time for the user
-  We will make the { home_controller.js } page clutter-free using either promises or
async-await.
- Async await tells the server that the function contains some asynchronous
statements and we need to wait with each async statement. Once it gets executed
then and only then moves on to the next statement.

### Converting More Code to Async Await
- It is not always necessary to change every part of the async code to async-await.
Although it is a good practice to follow the same convention everywhere.
- We will convert { posts_controller.js } and { comments_controller.js } files into
Async Await.

```node

module.exports.create = async function(req, res){

    try{
        let post = await Post.findById(req.body.post);

        if (post){
            let comment = await Comment.create({
                content: req.body.content,
                post: req.body.post,
                user: req.user._id
            });

            post.comments.push(comment);
            post.save();
            
            comment = await comment.populate('user', 'name email').execPopulate();
            // commentsMailer.newComment(comment);

            let job = queue.create('emails', comment).save(function(err){
                if (err){
                    console.log('Error in sending to the queue', err);
                    return;
                }
                console.log('job enqueued', job.id);

            })

            if (req.xhr){
                
    
                return res.status(200).json({
                    data: {
                        comment: comment
                    },
                    message: "Post created!"
                });
            }


            req.flash('success', 'Comment published!');

            res.redirect('/');
        }
    }catch(err){
        req.flash('error', err);
        return;
    }
    
}


module.exports.destroy = async function(req, res){

    try{
        let comment = await Comment.findById(req.params.id);

        if (comment.user == req.user.id){

            let postId = comment.post;

            comment.remove();

            let post = Post.findByIdAndUpdate(postId, { $pull: {comments: req.params.id}});

            // CHANGE :: destroy the associated likes for this comment
            await Like.deleteMany({likeable: comment._id, onModel: 'Comment'});


            // send the comment id which was deleted back to the views
            if (req.xhr){
                return res.status(200).json({
                    data: {
                        comment_id: req.params.id
                    },
                    message: "Post deleted"
                });
            }


            req.flash('success', 'Comment deleted!');

            return res.redirect('back');
        }else{
            req.flash('error', 'Unauthorized');
            return res.redirect('back');
        }
    }catch(err){
        req.flash('error', err);
        return;
    }
    
}
```

### Flash Messages:: Introduction
Flash messages are the ones that get displayed on your website. We require that the users
should be given a response in terms of notification whenever they are performing actions
on the website, and this is where Flash messages come in.

#### Creating Flash Messages
Flash messages are stored in the session cookies and they are cleared on the next
request. Hence, whenever we sign in, the flash message is sent into the session
cookie, and whenever we refresh that flash message is erased.
-  We will be using the { Connect Flash library } for creating flash messages.

```node


// sign in and create a session for the user
module.exports.createSession = function(req, res){
    req.flash('success', 'Logged in Successfully');
    return res.redirect('/');
}

module.exports.destroySession = function(req, res){
    req.logout();
    req.flash('success', 'You have logged out!');


    return res.redirect('/');
}
```

### Introducing Noty

To include Noty.js in the project we have to include following links -
- Include the CSS link in the { layout.ejs }file { <link rel="stylesheet"
href="https://cdnjs.cloudflare.com/ajax/libs/noty/3.1.4/noty.css"
integrity="sha512-NXUhxhkDgZYOMjaIgd89zF2w51Mub53Ru3zCNp5LTlEzMbN
NAjTjDbpURYGS5Mop2cU4b7re1nOIucsVlrx9fA==" crossorigin="anonymous" />
}.

```node
<html>
    <head>
        <title>
            <%= title  %>
        </title>
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/noty/3.1.4/noty.min.css">
        <script src="https://cdnjs.cloudflare.com/ajax/libs/noty/3.1.4/noty.min.js"></script>

        <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.4.0/jquery.min.js"></script>

        <link rel="stylesheet" href="/css/layout.css">
        <link rel="stylesheet" href="/css/header.css">
        <link rel="stylesheet" href="/css/footer.css">

        <%- style %>
        
    </head>

    <body>
        <%- include('_header'); %>

       
        
        <main id="layout-main">
            <%- body %>

        </main>


        <%- include('_footer'); %>

        <%- script %>

        <script>
            <% if (flash.success && flash.success.length > 0) {%>
                new Noty({
                    theme: 'relax',
                    text: "<%= flash.success %>",
                    type: 'success',
                    layout: 'topRight',
                    timeout: 1500
                    
                }).show();    
            <%} %>

            <% if (flash.error && flash.error.length > 0) {%>
                new Noty({
                    theme: 'relax',
                    text: "<%= flash.error %>",
                    type: 'error',
                    layout: 'topRight',
                    timeout: 1500
                    
                }).show();    
            <%} %>
        </script>
        
    </body>
</html>
```






[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#Authentication Using Passport)

# ➤Converting to Ajax
o incorporate AJAX into our website. Whenever we submit
the form for creating a post, we will submit it via AJAX, get the response in the form of a
JSON and append it to the page

### Creating a Post:: Sending Data
We will be going to use JQUERY AJAX for the website.
 - In { layout.ejs } paste the link { <script
src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script
> } to include jquery just below noty link.
-  We have to create a JS file that fetches the data from the form and sends it in the
JSON format to the action.
-  In the js folder inside the assets folder, we create a file {home_posts.js}.
-  Include the script {home_posts.js} inside the {home.ejs} file to load the script.
-  While creating a post, we need two things -
○ A function that handles the submission of the post
○ A function that receives the data of the created post and displays it.
-  Create a function that sends the data to the controller action in {home_posts.js}
-  Whenever the form is submitted, we don’t want it to submit own its own. Hence, we
will use the parameter preventDefault.
-  Submit the form manually using AJAX.
 ### Creating a Post:: Receiving Data
 - For deleting the post we need some id that can uniquely identify the post. This will
come in handy when we progress in this lecture.
- Add class to the delete button so that we can give it common styling and also attach
click listeners to it.
- For creating the post in the DOM, we need a function that will help us in converting
the text of HTML into a JQuery object.
- Create the function and pass the post data that we have received and return the
text of HTML.
- The data that has been displayed has another key data that needs to be sent as a
post.
- Prepend it to the list of posts that are displayed on the screen
 ```node
 <link rel="stylesheet" href="/css/post.css" />
<link rel="stylesheet" href="/css/home.css" />
<link rel="stylesheet" href="/css/chat_box.css" />

<div id="home-container">
  <section id="feed-posts">
    <h2 class="fw7 bg-text-clip shine">Posts</h2>
    <% if(locals.user){ %>
    <form action="/posts/create" id="new-post-form" method="POST">
      <textarea
        style="background-color: rgb(236, 223, 104)"
        name="content"
        cols="30"
        rows="3"
        placeholder="Type Here..."
        required
      ></textarea>
      <input type="submit" value="Post" />
    </form>
    <% } %>

    <div id="posts-list-container">
      <ul style="list-style: none">
        <% for(post of posts){ %> <%- include('_post') -%> <%} %>
      </ul>
    </div>
  </section>

  <section id="user-friends">
    <h4>Friends</h4>
    <% for(u of all_users){%>
    <p>
      <a href="/users/profile/<%= u.id %>"><%= u.name %></a>
    </p>
    <% } %>
  </section>

  <%- include('_chat_box') -%>
</div>

<!-- importing this script for creating the comments -->
<script src="/js/home_post_comments.js"></script>
<script src="/js/home_posts.js"></script>

<!-- CHANGE :: import the script file for toggle likes, also run it over for the already present posts and comments on the page -->
<script src="js/toggle_likes.js"></script>
<script>
  $(".toggle-like-button").each(function () {
    let self = this;
    let toggleLike = new ToggleLike(self);
  });
</script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/socket.io/2.2.0/socket.io.js"></script>
<script src="/js/chat_engine.js"></script>
<% if (locals.user){ %>
<script>
  new ChatEngine(
    "user-chat-box",
    "<%= locals.user.email %>",
    "<%= locals.user.name %>"
  );
</script>
<% } %>

 ``` 
  ### Deleting a Post
```node
<li id="post-<%= post._id %>">
  <p>
    <% if (locals.user && locals.user.id == post.user.id){ %>
    <small>
      <a href="/posts/destroy/<%= post.id %>">
        <button
          class="delete-post-button"
          style="background-color: rgb(175, 101, 101)"
        >
          Delete
        </button>
      </a>
    </small>
    <% } %> <%= post.content %>
    <br />
    <small> <%= post.user.name %> </small>

    <!-- CHANGE :: display the likes of this post, if the user is logged in, then show the link to toggle likes, else, just show the count -->
    <br />
    <!-- study about the data attribute -->
    <small>
      <% if (locals.user){ %>
      <a
        class="toggle-like-button"
        data-likes="<%= post.likes.length %>"
        href="/likes/toggle/?id=<%=post._id%>&type=Post"
      >
        <i class="fab fa-gratipay"> <%= post.likes.length %> Likes</i>
      </a>
      <% }else{ %>
      <i class="fab fa-gratipay"> <%= post.likes.length %> Likes</i>
      <% } %>
    </small>
  </p>
  <div class="post-comments">
    <% if (locals.user){ %>
    <!-- let's give an id to the new comment form, we'll also need to make the same changes in home_posts.js where we're adding a post to the page -->
    <form
      id="post-<%= post._id %>-comments-form"
      action="/comments/create"
      method="POST"
    >
      <input
        type="text"
        name="content"
        placeholder="Type Here to add comment..."
        required
      />
      <input type="hidden" name="post" value="<%= post._id %>" />
      <input
        type="submit"
        style="background-color: rgb(240, 217, 217)"
        value="Add Comment"
      />
    </form>

    <% } %>

    <div class="post-comments-list">
      <ul id="post-comments-<%= post._id %>">
        <% for (comment of post.comments){%> <%- include('_comment') -%> <%} %>
      </ul>
    </div>
  </div>
</li>

```

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#File Upload)

# ➤ File Upload
### Introduction to Uploading files
   ### Uploading Files: How Does It Work?
    We have our server that has been initialized on a file system or an operating system.
-  Let’s say on our profile page, we choose a picture and we send it to the server in the
form of a file { File is a sequence or a stream of bytes }.
-  The server is connected to the database which is not saving the file. When the file is
sent to the server we store our file inside the folder { avatar } and reference it
inside the database.
-  The hash of every user in our database { MongoDB }, we have a key called an
avatar and that key has a value which is the path to the file.

### Installing Multer + Documentation
 For setting up multer we will go to the models folder and inside the file { user.js }
we will be doing the following things.
1. Import the multer library and the path of where the file will be stored.
2. We will define the path that is { /uploads/users/avatars }.
3. We will create a new folder { uploads }, inside the uploads folder we will
create one more folder { users }, inside the users folder we will create one
more folder { avatars }.

### Configuring Multer for User Avatar
multer.diskStorage is a function that will take an object which has further two
keys, one of them defines the destination and the other defines the filename.
### Saving File from Params
In the filename key of the multer.diskStorage function, there exists the field name
in which we are storing the file.
-  Every file that we upload for the field for every user will be stored as avatar- { the
value of Date. now() function } .
-  We need to define static functions - { Static functions are the ones which can be
called overall on the whole class }.
-  .single is the property that says that only one file can be uploaded for the field name
avatar.
-  We have to define the avatar path because we need this avatar path {
/uploads/users/avatars } to be available publicly for the user model.

### Showing the Avatar, Connecting the Dot
We have to declare an img tag and the src for this image will be users.avatar as this
is the path for our image.
-  We need to make this path available to the browser when the browser asks for it.
-  Inside the { index.js } file, make the uploads path available to the browser using
app.use method








[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#Authentication Using Passport)

# ➤ API
### Introduction APIs- Why and What
 Whenever we want two devices to communicate with minimalist resources, we use
API { Application Programming Interface }.
-  When we use an API, two devices communicate using a particular format. The most
popular is the JSON.
-  We are not sending HTML and receiving it back because we want our
communication to be fast.
 
 ### Setting Up The Directory Structure
  Create one folder inside the controllers folder and routes folder named { API }.
-  Create a new V1 folder for each API folder inside the controllers and route folder.
-  API folders will have their index files. Each version also has its index files

```node

const express = require('express');

const router = express.Router();
const likesController = require('../controllers/likes_controller');


router.post('/toggle', likesController.toggleLike);


module.exports = router;
```

## Rendering an API
route/API/INDEX.JS
```node
const express = require('express');

const router = express.Router();

router.use('/v1', require('./v1'));

module.exports = router;
```

routes/api/v1/index.js
```node
const express = require('express');

const router = express.Router();

router.use('/posts', require('./posts'));
router.use('/users', require('./users'));

module.exports = router;
```
routes/api/v1/posts
```node
const express = require('express');

const router = express.Router();
const passport = require('passport');
const postsApi = require("../../../controllers/api/v1/posts_api");


router.get('/', postsApi.index);
router.delete('/:id', passport.authenticate('jwt', {session: false}), postsApi.destroy);



module.exports = router;
```
 ## Authentication With APIs:: JWT { JSON Web Tokens }
-  Whenever we are sending some data as a user to the server in the form of a
request, the server checks whether that data matches a user in the database.
○ If it matches a user, then the server generates a token or an encrypted key,
stores it somewhere, and sends it back to the browser in the cookie.
-  For every request that the browser makes, the cookies have the generated
authentication token and the server establishes the identity of the user using that
token.
-  APIs do not have cookies. For that, we have to store the authentication token
somewhere else.
-  While using JWT, we don’t need to store anything in the database.
-  Whenever we are sending in the details of the user, his identity is verified. The token
generated has three parts separated by dots that are JWT JSON web tokens. {
Header - What algorithm is used to encrypt JSON web tokens, payload - It contains
the encrypted information, Signature - It is composed by some algorithm applied
on the combination of header and payload}.
-  These tokens are passed to the applications on android or mobile devices or any
other frontend framework.
-  Once this token is sent to the frontend framework, it stores the token in the local
storage.
-  The token contains all the necessary information. Hence, we will send that token in
the header whenever we are sending back some requests The server in return
establishes the identity.

### Setting Up Passport JWT
 We need to mention every strategy that is being used in the { index.js } file of the
application.
-  Import passport jwt strategy in the { index.js } file.
-  Create a new file inside the config folder { passport-jwt-strategy.js }.
-  Import passport and passport-jwt strategy inside the { passport-jwt-strategy.js }
file.
-  We will be storing complete user information inside the payload information in an
encrypted format.

```node
const passport = require('passport');
const JWTStrategy = require('passport-jwt').Strategy;
const ExtractJWT = require('passport-jwt').ExtractJwt;

const User = require('../models/user');


let opts = {
    jwtFromRequest: ExtractJWT.fromAuthHeaderAsBearerToken(),
    secretOrKey: 'codeial'
}


passport.use(new JWTStrategy(opts, function(jwtPayLoad, done){

    User.findById(jwtPayLoad._id, function(err, user){
        if (err){console.log('Error in finding user from JWT'); return;}

        if (user){
            return done(null, user);
        }else{
            return done(null, false);
        }
    })

}));

module.exports = passport;

```
### Creating a Token
-  Earlier we were signing in and some cookies were set in the background by
passport.
-  Now we will explicitly create JSON web tokens and send them using a library called
JSON web tokens.
-  Install JSON web tokens using the command { npm install jsonwebtoken } in the
terminal.
-  This is used to generate tokens and then the passport is capable of decrypting
those encrypted token using the library.
-  Create a new file inside the API folder inside the controllers folder named as {
users_api.js }.
-  Whenever a username and password are received we need to find that user and
generate the JSON web token corresponding to that user using async-await style.

{ controllers/API/V1/users_api.js }
```node

const User = require('../../../models/user');
const jwt = require('jsonwebtoken');


module.exports.createSession = async function(req, res){

    try{
        let user = await User.findOne({email: req.body.email});

        if (!user || user.password != req.body.password){
            return res.json(422, {
                message: "Invalid username or password"
            });
        }

        return res.json(200, {
            message: 'Sign in successful, here is your token, please keep it safe!',
            data:  {
                token: jwt.sign(user.toJSON(), 'codeial', {expiresIn:  '100000'})
            }
        })

    }catch(err){
        console.log('********', err);
        return res.json(500, {
            message: "Internal Server Error"
        });
    }
}
```

{ routes/API/V1/users.js }
```node
   const express = require('express');

const router = express.Router();
const usersApi = require('../../../controllers/api/v1/users_api');


router.post('/create-session', usersApi.createSession);

module.exports = router; 
```
{ routes/API/V1/index.js }

```node
const express = require('express');

const router = express.Router();

router.use('/posts', require('./posts'));
router.use('/users', require('./users'));

module.exports = router;
```
 

## Authentication And Authorization
-  We are setting the session to be false because we do not want the session cookie to
be generated.
{ controllers/API/V1/users_api.js }
```node

const User = require('../../../models/user');
const jwt = require('jsonwebtoken');


module.exports.createSession = async function(req, res){

    try{
        let user = await User.findOne({email: req.body.email});

        if (!user || user.password != req.body.password){
            return res.json(422, {
                message: "Invalid username or password"
            });
        }

        return res.json(200, {
            message: 'Sign in successful, here is your token, please keep it safe!',
            data:  {
                token: jwt.sign(user.toJSON(), 'codeial', {expiresIn:  '100000'})
            }
        })

    }catch(err){
        console.log('********', err);
        return res.json(500, {
            message: "Internal Server Error"
        });
    }
}

```
{ controllers/API/V1/posts_api.js }
```node
const Post = require('../../../models/post');
const Comment = require('../../../models/comment');
module.exports.index = async function(req, res){


    let posts = await Post.find({})
        .sort('-createdAt')
        .populate('user')
        .populate({
            path: 'comments',
            populate: {
                path: 'user'
            }
        });

    return res.json(200, {
        message: "List of posts",
        posts: posts
    })
}


module.exports.destroy = async function(req, res){

    try{
        let post = await Post.findById(req.params.id);

        if (post.user == req.user.id){
            post.remove();

            await Comment.deleteMany({post: req.params.id});


    
            return res.json(200, {
                message: "Post and associated comments deleted successfully!"
            });
        }else{
            return res.json(401, {
                message: "You cannot delete this post!"
            });
        }

    }catch(err){
        console.log('********', err);
        return res.json(500, {
            message: "Internal Server Error"
        });
    }
    
}
```



{  routes/API/V1/posts_api.js }
```node
const express = require('express');

const router = express.Router();
const passport = require('passport');
const postsApi = require("../../../controllers/api/v1/posts_api");


router.get('/', postsApi.index);
router.delete('/:id', passport.authenticate('jwt', {session: false}), postsApi.destroy);



module.exports = router;
```





[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#Authentication Using Passport)

# ➤ Social Authentication
### Creating Credentials on Google
 Go to { My Projects } where you have your list of projects and click on a
{new project }
-  Give the name of your project ( codeial -sample ) and click on {create it}.
-  Go on to the title project and click on create credentials.
-  Credentials are for OAuth -2.

### Social Authentication:: How does it work
This involves the third-party authentication provider which establishes the identity
of the user.
-  There will be a user, third-party authentication provider, and server with the
database.
-  The user comes and clicks on the sign-in or sign up with google. A pop-up opens in
another window that asks us to sign in with google if we are not signed in or we
have signed using multiple accounts. For the latter case, we choose from one of
those accounts.
-  Google then asks for permission from the user, that ‘project_name is asking for
your permission to access your account’. This happens only if the user is accessing
the website for the first time.
-  When the pop-up opens and we submit some credentials or select an account, the
request is redirected to the servers of Google. Google checks its database whether
the user exists or not. If the user exists, Google checks if and the credentials are
correct or not.
- 
-  If the authentication is unsuccessful, you will be redirected back to the login page
with an error.
-  Once the credentials are matched successfully, the user will be redirected to
another URL on the same browser for the server which is called using the callback
URL with some data of the signed-in user. This is created by the developer of the
website.
- 
-  The server checks with the database whether the Email ID that has been provided
by Google is there in the database or not.
-  If it is there in the database, the user signs in successfully.

### Setting up Passport - Google - OAuth
-  Create a file inside config { passport-google -oauth-2-strategy.js }.
-  We need to install some library for that { npm install passport-google-oauth }.
-  Require passport library in { passport-google -oauth-2-strategy.js } file.
-  Require passport-google-oauth in { passport-google -oauth-2-strategy.js } file.
-  We need to install the crypto library { npm install crypto } and require it inside {
passport-google -oauth-2-strategy.js } file.
-  Require users file from the models folder.
-  We need to tell passport to use google strategy using passport.use in which we pass
in the options - { client ID, client secret, callback URL }.
-  We need to put in the callback function which will be taking { access token, refresh
token, profile information, and the final function which will be taking callback from
this function }.

{ passport-google -oauth-2-strategy.js }

```node
const passport = require('passport');
const googleStrategy = require('passport-google-oauth').OAuth2Strategy;
const crypto = require('crypto');
const User = require('../models/user');


// tell passport to use a new strategy for google login
passport.use(new googleStrategy({
        clientID: "-----",
        clientSecret: "___no ",
        callbackURL: "http://localhost:8000/users/auth/google/callback",
    },

    function(accessToken, refreshToken, profile, done){
        // find a user
        User.findOne({email: profile.emails[0].value}).exec(function(err, user){
            if (err){console.log('error in google strategy-passport', err); return;}
            console.log(accessToken, refreshToken);
            console.log(profile);

            if (user){
                // if found, set this user as req.user
                return done(null, user);
            }else{
                // if not found, create the user and set it as req.user
                User.create({
                    name: profile.displayName,
                    email: profile.emails[0].value,
                    password: crypto.randomBytes(20).toString('hex')
                }, function(err, user){
                    if (err){console.log('error in creating user google strategy-passport', err); return;}

                    return done(null, user);
                });
            }

        }); 
    }


));


module.exports = passport;

```
### Using Google Auth:: With a Link
user.js
```node
const express = require('express');
const router = express.Router();
const passport = require('passport');

const usersController = require('../controllers/users_controller');

router.get('/profile/:id', passport.checkAuthentication, usersController.profile);
router.post('/update/:id', passport.checkAuthentication, usersController.update);

router.get('/sign-up', usersController.signUp);
router.get('/sign-in', usersController.signIn);


router.post('/create', usersController.create);

// use passport as a middleware to authenticate
router.post('/create-session', passport.authenticate(
    'local',
    {failureRedirect: '/users/sign-in'},
), usersController.createSession);


router.get('/sign-out', usersController.destroySession);


router.get('/auth/google', passport.authenticate('google', {scope: ['profile', 'email']}));
router.get('/auth/google/callback', passport.authenticate('google', {failureRedirect: '/users/sign-in'}), usersController.createSession);



module.exports = router;
```



[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#Parallel Jobs + Mailer)

# ➤Parallel Jobs + Mailert
### Setting Up Nodemailer
We will be installing the module Nodemailer and setting up the config for it.
-  We will be setting up the file that will have the function to send mail. It will have
predefined content.
-  We want to send mails with some HTML content that will have different formatting,
we will be sending those emails using templates.
-  To install nodemailer use the command { npm install nodemailer } in the terminal.
-  Nodemailer has two things- transporters and template { transporter defines the
configuration using which we will be sending emails }.
-  We will create a separate folder in views wherein we define the mail template to be
used.
-  Inside the config folder, we need to create a new file { config.js }.
-  We need to import nodemailer inside the { config.js } file.
-  We need to define the transporter that will be attached to the nodemailer.
-  For the rendering of the template we need to require EJS in the file

```node
const nodemailer = require("nodemailer");
const ejs = require('ejs');
const path = require('path')


let transporter = nodemailer.createTransport({
    service: 'gmail',
    host: 'smtp.gmail.com',
    port: 587,
    secure: false,
    auth: {
        user: ' xyz@gmail.com',
        pass: ' '
    }
});


let renderTemplate = (data, relativePath) => {
    let mailHTML;
    ejs.renderFile(
        path.join(__dirname, '../views/mailers', relativePath),
        data,
        function(err, template){
         if (err){console.log('error in rendering template', err); return}
         
         mailHTML = template;
        }
    )

    return mailHTML;
}


module.exports = {
    transporter: transporter,
    renderTemplate: renderTemplate
}
```
### Sending Our First Email via SMTP
The triggering point of mail is whenever one user comments on someone’s posts, let
the mail come to the user itself who is commenting in the initial stage. Later, send
that mail to the user who has posted the post.
-  We will create a new folder { mailers }, and inside it a new file {
comments_mailer.js }.
-  We need to import nodemailer inside the { comments_mailer.js } file.
-  We need to create a function that will create the mail.

{ comments_mailer.js }
```node
const nodeMailer = require('../config/nodemailer');


// this is another way of exporting a method
exports.newComment = (comment) => {
    let htmlString = nodeMailer.renderTemplate({comment: comment}, '/comments/new_comment.ejs');

    nodeMailer.transporter.sendMail({
       from: ' @ .in',
       to: comment.user.email,
       subject: "New Comment Published!",
       html: htmlString
    }, (err, info) => {
        if (err){
            console.log('Error in sending mail', err);
            return;
        }

        // console.log('Message sent', info);
        return;
    });
}
```
{ comments-controller.js }
```node
const Comment = require('../models/comment');
const Post = require('../models/post');
const commentsMailer = require('../mailers/comments_mailer');
const queue = require('../config/kue');
const commentEmailWorker = require('../workers/comment_email_worker');
const Like = require('../models/like');

module.exports.create = async function(req, res){

    try{
        let post = await Post.findById(req.body.post);

        if (post){
            let comment = await Comment.create({
                content: req.body.content,
                post: req.body.post,
                user: req.user._id
            });

            post.comments.push(comment);
            post.save();
            
            comment = await comment.populate('user', 'name email').execPopulate();
            // commentsMailer.newComment(comment);

            let job = queue.create('emails', comment).save(function(err){
                if (err){
                    console.log('Error in sending to the queue', err);
                    return;
                }
                console.log('job enqueued', job.id);

            })

            if (req.xhr){
                
    
                return res.status(200).json({
                    data: {
                        comment: comment
                    },
                    message: "Post created!"
                });
            }


            req.flash('success', 'Comment published!');

            res.redirect('/');
        }
    }catch(err){
        req.flash('error', err);
        return;
    }
    
}


module.exports.destroy = async function(req, res){

    try{
        let comment = await Comment.findById(req.params.id);

        if (comment.user == req.user.id){

            let postId = comment.post;

            comment.remove();

            let post = Post.findByIdAndUpdate(postId, { $pull: {comments: req.params.id}});

            // CHANGE :: destroy the associated likes for this comment
            await Like.deleteMany({likeable: comment._id, onModel: 'Comment'});


            // send the comment id which was deleted back to the views
            if (req.xhr){
                return res.status(200).json({
                    data: {
                        comment_id: req.params.id
                    },
                    message: "Post deleted"
                });
            }


            req.flash('success', 'Comment deleted!');

            return res.redirect('back');
        }else{
            req.flash('error', 'Unauthorized');
            return res.redirect('back');
        }
    }catch(err){
        req.flash('error', err);
        return;
    }
    
}
```
### Send HTML Template Emails
{ comments.mailer.js }
```node
const nodeMailer = require('../config/nodemailer');


// this is another way of exporting a method
exports.newComment = (comment) => {
    let htmlString = nodeMailer.renderTemplate({comment: comment}, '/comments/new_comment.ejs');

    nodeMailer.transporter.sendMail({
       from: ' xc@ .in',
       to: comment.user.email,
       subject: "New Comment Published!",
       html: htmlString
    }, (err, info) => {
        if (err){
            console.log('Error in sending mail', err);
            return;
        }

        // console.log('Message sent', info);
        return;
    });
}
```

{ new_commnents.ejs}
```node
<li id="comment-<%= comment._id %>">
        <p>
            <% if (locals.user && locals.user.id == comment.user.id){ %>
            
            <small>
                <a class="delete-comment-button" href="/comments/destroy/<%= comment.id %>">X</a>
            </small>
            <% } %>
            <%= comment.content %>
            <br>
            <small>
                <%= comment.user.name %>
            </small>
            <!-- CHANGE :: display the likes of this comment, if the user is logged in, then show the link to toggle likes, else, just show the count -->
            <!-- study about the data attribute -->
            <small>
                <% if (locals.user){ %>
                    <a class="toggle-like-button" data-likes="<%= comment.likes.length %>" href="/likes/toggle/?id=<%=comment._id%>&type=Comment">
                            <%= comment.likes.length %> Likes
                    </a>
                <% }else{ %>
                    <%= comment.likes.length %> Likes
                <% } %>
            </small>

        </p>    

</li>
```
### Introduction to Delayed Jobs
#### Installing and Understand KUE
#### Setting KUE and Using It
   We need to configure KUE.
-  We need to create a new file inside the config folder { Kue.js }.
-  We need to require the KUE library.
{ Kue.js }.
-  We need to create workers for the KUE.
-  We need to create a new folder worker and inside that create a new file {
comment_email_worker.js }.
-  //The code for this is missing { workers/comment_email_worker.js}
```node
const Comment = require('../models/comment');
const Post = require('../models/post');
const commentsMailer = require('../mailers/comments_mailer');
const queue = require('../config/kue');
const commentEmailWorker = require('../workers/comment_email_worker');
const Like = require('../models/like');

module.exports.create = async function(req, res){

    try{
        let post = await Post.findById(req.body.post);

        if (post){
            let comment = await Comment.create({
                content: req.body.content,
                post: req.body.post,
                user: req.user._id
            });

            post.comments.push(comment);
            post.save();
            
            comment = await comment.populate('user', 'name email').execPopulate();
            // commentsMailer.newComment(comment);

            let job = queue.create('emails', comment).save(function(err){
                if (err){
                    console.log('Error in sending to the queue', err);
                    return;
                }
                console.log('job enqueued', job.id);

            })

            if (req.xhr){
                
    
                return res.status(200).json({
                    data: {
                        comment: comment
                    },
                    message: "Post created!"
                });
            }


            req.flash('success', 'Comment published!');

            res.redirect('/');
        }
    }catch(err){
        req.flash('error', err);
        return;
    }
    
}
 
```



[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#Authentication Using Passport)

# ➤    Chatting Engine
### Reaching Sockets
 { Views / chat_box.ejs }
 ```node
<!-- CHANGE :: Creat the code for chat box -->
<% if (locals.user){ %>
	<div id="user-chat-box" class="container gradient-border chat-history">
		<ul id="chat-messages-list" class="">
			<li class="other-message  ">
				<span>Other Message</span>
			</li>
			<li class="self-message">
				<span>
					Self Message
				</span>
				
			</li>

		</ul>
		<div id="chat-message-input-container">
			<input id="chat-message-input" placeholder="Type message here">
			<button id="send-message">Send</button>
		</div>
	</div>
<% } %>


<!-- desgin chat box -->


 ```
 ### Beginning the Initial Connection
{ chat_sockets.js }
```node

module.exports.chatSockets = function(socketServer){
    let io = require('socket.io')(socketServer);

    io.sockets.on('connection', function(socket){
        console.log('new connection received', socket.id);

        socket.on('disconnect', function(){
            console.log('socket disconnected!');
        });

        
        socket.on('join_room', function(data){
            console.log('joining request rec.', data);

            socket.join(data.chatroom);

            io.in(data.chatroom).emit('user_joined', data);
        });

        // CHANGE :: detect send_message and broadcast to everyone in the room
        socket.on('send_message', function(data){
            io.in(data.chatroom).emit('receive_message', data);
        });

    });

}
```

{ chat_engine.js }
``` node
class ChatEngine{
    constructor(chatBoxId, userEmail,userName){
        this.chatBox = $(`#${chatBoxId}`);
        this.userEmail = userEmail;
        this.userName = userName;

        this.socket = io.connect('http://localhost:5000');

        if (this.userEmail){
            this.connectionHandler();
        }

    }


    
```
### Time to Create and Join Chat Rooms
 Whenever two or more users are chatting with each other, we create a virtual
environment that is called a Chat Room.
-  There is an array of id’s and emails wherein a user’s email and unique ids are stored
for a particular chatbox.
-  One socket connection can hold multiple sockets.
-  Whenever a user is connected or clicks a specific name, the user will ask to start a
chat with that specific user.
-  We will send a request to the other user and we receive an acknowledgment of that
sent-in request. Whenever the other user also comes online or joins the room we
will receive a notification.


```node
connectionHandler(){
        let self = this;

        this.socket.on('connect', function(){
            console.log('connection established using sockets...!');


            self.socket.emit('join_room', {
                user_email: self.userEmail,
                user_name: self.userName,
                chatroom: 'codeial'
            });

            self.socket.on('user_joined', function(data){
                console.log('a user joined!', data);
            })


        });

        // CHANGE :: send a message on clicking the send message button
        $('#send-message').click(function(){
            let msg = $('#chat-message-input').val();

            if (msg != ''){
                self.socket.emit('send_message', {
                    message: msg,
                    user_email: self.userEmail,
                    user_name: self.userName,
                    chatroom: 'codeial'
                });
               
            }
        });

       
    }
}
```
### Finally, Let’s Send and Receive Messages.
```node
 self.socket.on('receive_message', function(data){
            console.log('message received', data.message);


            let newMessage = $('<li>');

            let messageType = 'other-message';

            if (data.user_email == self.userEmail){
                messageType = 'self-message';
            }
            
            newMessage.append($('<span>', {
                'html': data.message
            }));

            newMessage.append($('<sub>', {
                'html': data.user_name
            }));

            newMessage.addClass(messageType);

            $('#chat-messages-list').append(newMessage);
        })
```

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#Authentication Using Passport)

# ➤   Using  
Button used for clicking!

### 

| Property   | Attribute  | Type      | Default  | Description           |
|------------|------------|-----------|----------|-----------------------|
| `disabled` | `disabled` | `boolean` | false    | Disables the element. |
| `role`     | `role`     | `string`  | "button" | Role of the element.  |

###  

| Name | Description     |
|------|-----------------|
|      |   Mohammad Shahansha |

 
