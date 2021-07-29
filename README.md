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
● Partials (Partial code put into another file) - The advantage of EJS is that it
combines data and a template to produce HTML. This makes our code scalable and
manageable. One of the most important features of EJS is its use of partials. Using
partials, you may write a piece of code just once, and use it at many places as and
when required.<br/>
● Whenever we have some piece of code that is either very long or a piece of code
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

## Setting Up Directory Structure

 - Create a new folder in your workstation {SOCIAL NETWOKR}
 - Create a new file which is the entry point {index.js}.
- Create multiple directories for a scalable project using terminal
{mkdir routes controllers models views config}
-  According to routes, which function would be called routes will be stored in the
controllers folder mapped into different files.
- Views will contain different HTML files



### Starting Express

Install express using {npm install express}.

 ● Interpolation - Instead of using (,) or (+) for concatenating two strings, we can embed
our variable inside {} the string using backticks (``).
● To include the variable inside the string this should be done “${``}”. So Instead of
those [console.log(“Error: ”, err)], we can do [console.log(`Error: ${err}`)].
● Anything inside [${}] is to be evaluated.
● Run command {nodemon index.js} to run the server.
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
 
