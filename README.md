<!-- ⚠️ This README has been generated from the file(s) "blueprint.md" ⚠️--><p align="center">
  <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/logo-shadow.png" alt="Logo" width="150" height="150" />
</p>
<h1 align="center">@appnest/readme</h1>
<p align="center"> 
<a href="https://www.npmjs.com/package/@appnest/readme"><img alt="NPM Version" src="https://img.shields.io/npm/v/@appnest/readme.svg" height="20"/></a>
<a href="https://david-dm.org/andreasbm/readme"><img alt="Dependencies" src="https://img.shields.io/david/andreasbm/readme.svg" height="20"/></a>
<a href="https://github.com/andreasbm/readme/graphs/Databases:: An Introduction"><img alt="Databases:: An Introduction" src="https://img.shields.io/github/Databases:: An Introduction/andreasbm/readme.svg" height="20"/></a>
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

  <sub>
Start with most important part in code is authentication in  code,whenever we tried login 
or sign up in page ,you get too the some data is specific  for you only and your email or
 your on wall render on filed,this is possible beacuse you logged in as you ,you establish
 your identity to that  website,this is more fundamental and core  part for every website.
 
And we recieved some email notification  from this  website as your post got like,comments,
or you active online you will recive that email or that is something while user look up to. 

Deleting and updating objects in database + distributing Views ,so we need authorize which user 
have to delete comment which  not,more  over user can edit his/her name ,change profile,
email and <h2>a many more functinally are done in this project. </h2>


<sub>
</p>

<br />

# MVC Framework
The MVC (Model-View-Controller) is an architectural pattern that
separates an application into three main logical components:
the model, the view, and the controller. Each of these components
are built to handle specific development aspects of an application. 


[![Social Network](https://i.postimg.cc/Z5DycP05/social0main.png)](https://postimg.cc/SnCsQMWB)

* **Simple**: Extremely simple to use - so simple that it almost feels like magic!
* **Powerful**: Customize almost everything - add your own templates and variables if you like.



# SOCIAL NetWork 


 

<!-- <summary>    </summary> -->

<br />



[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#table-of-contents)

# ➤ 📖 Working With these 

* [➤ Installation](#-installation)
* [➤ Getting Started (quick)](#-getting-started-quick)
* [➤ Getting Started (slower)](#-getting-started-slower)
	* [Blueprint](#blueprint)
	* [Usage](#usage)
	* [Configuration](#configuration)
* [➤ Templates](#-templates)
	* [Title](#title)
	* [Logo](#logo)
	* [Badges](#badges)
	* [Description](#description)
	* [Table of Contents](#table-of-contents)



* [➤Setting Up Directory Structure](#-directory)
	* [Starting Express  ](#startingexpress )
	* [ Adding Git & NPM Start ](#add-git)
	* [ Setting up the Express Router ](#setting-up-router )
	* [ Create a Controller ](#create-controller )
	* [Create another Controller & Router  ](#crete-controller-router )
	* [ Installing EJS & Set Up the View Engine](#enstall-ejs)
	* [ Create a view for home ](#create-viw)
	* [ Implementing Partials ](#implimenting-particles)
	* [ Static Files For Pages ](#static-files)



* [➤ Databases:: An Introduction](#-DatabasesAnIntroduction)
	* [MongoDB :: Terms ](#mongodb)
	* [Creating the DB Schema ](#Schema)
	* [Fetching Data from DB  ](#populating )
	* [ Deleting from DB ](#deleteDB )
  * [ Connecting to MongoDB using Mongoose](#-connecting-Mongoose)
	* [ Linking our MongoDB using Mongoose ](#likingMongoDB)




* [➤Manual Authentication](#-manual-authentication)
	* [ Setting up User Schema ](#setup_userSchema)
	* [ Rendering Pages for Sign up and Sign in ](#renderpages)
	* [ Explaining Cookies  ](#cookies)
	* [ Creating and Alternating a Cookie ](#creating-cookie )
	* [ User Sign Up](#user-signup)
	* [ User Sign In ](#userSignin)
	* [ Show Details of Signed in User ](#showdetail )


* [➤ Authentication Using Passport](#-Authentication-Using-Passport)
	* [ Glancing through and Installing Passport.js ](#install-passport )
	* [ Setting up Passport.js ](#set-up-passport)
	* [ Express sessions and using passport for authentication ](#Express-sessions-and-using-passport-for-authentication )
	* [ Setting Current Authenticated User ](#Setting-Current-Authenticated-User)
	* [ Passing User data to views and restricting page access ](#Passing-User-data-to-views-and-restricting-page-access )
	* [ Setting up Mongo store for session cookies ](#Setting-up-Mongo-store-for-session-cookies )
	* [ Creating Sign Out ](#Creating-Sign-Out)

* [➤ SASS](#-a-bit-about-this-readme)
	* [ SCSS or SASS? ](#SCSS-or-SASS)
	* [ Setting Up SCSS ](#Setting-Up-SCSS )
	* [  Using SCSS](#Using-SCSS)

* [➤ Database Relations (Posts, Comments)](#-database-realtion)
	* [ Node.js:: Explaining ](#Node.js:-Explaining)
	* [ Creating Schema for Posts ](#Creating-Schema-for-Posts )
	* [ Saving Posts to the DB ](#Saving-Posts-to-the-DB )
	* [Display Post and Related User ](#Display-Post-and-Related-User  )
	* [ Check Authentication on Creating Post ](#Check-Authentication-on-Creating-Post-)
	* [ Creating Schema for Comments ](#Creating-Schema-for-Comments )
	* [ Nesting Population:: Display Comments and Related User ](#Nesting-Population::-Display-Comments-and-Related-User )
	* [ Adding Comments to the DB ](#Adding-Comments-to-the-DB )

* [➤ Deleting and Updating Object in Database + Distributing Views!](#-DeltingandpdatingObject )  
	* [ Deleting a Post (Authorized)](#Deleting-a-Post-(Authorized) )
	* [ Deleting a Comment (Authorized) ](#Deleting-a-Comment-(Authorized)-)
	* [ Distributing the Code into Partials ](#Distributing-the-Code-into-Partials )
	* [User Profile links  ](#User-Profile-links )
	* [ Updating a User’s profile ](#Updating-a-User’s-profile )

* [➤  Async Await + Error Handling](#Async-Await-+-Error-Handling )
	* [Converting to Async Await ](#Converting-to-Async-Await )
	* [ Converting More Code to Async Await ](#-Converting-More-Code-to-Async-Await )

* [➤ Flash Messages:: Introduction ](#Flash-MessagesIntroduction )
	* [ Creating Flash Messages ](#Creating-Flash-Messages )
	* [Introducing Noty  ](#Introducing-Noty )
	* [ Adding Flash Messages to more Actions ](#Adding-Flash-Messages-to-more-Actions )
 
  
* [➤ Converting to Ajax ](#Converting-to-Ajax )
	* [ Creating a Post:: Sending Data ](#Creating-a-Post::-Sending-Data )
	* [ Creating a Post:: Receiving Data ](#Creating-a-Post::-Receiving-Data  )
	* [ Deleting a Post ](#Deleting-a-Post )
	 
* [➤ File Upload ](#file-uploading )
	* [ Uploading Files: How Does It Work? ](#Uploading-Files:-How-Does-It-Work? )
	* [ Installing Multer + Documentation ](#Installing-Multer-+-Documentation )
	* [ Configuring Multer for User Avatar ](#Configuring-Multer-for-User-Avatar )
	* [ Saving File from Params ](#Saving-File-from-Params )
	* [ Showing the Avatar, Connecting the Dots ](#Showing-the-Avatar-Connecting-the-Dots )
	* [ Edge Case:: Replacing an Avatar  ](#Edge-Case::-Replacing-an-Avatar )
 
* [➤APIs  ](#Api )
	* [ APIs:: Why and What ](#APIs::-Why-and-What )
	* [  The Postman](#The-Postman )
	* [ Setting Up The Directory Structure ](#Setting-Up-The-Directory-Structure)
	* [ Rendering an AP  ](#Rendering-an-AP )
	* [ Playing With APIs ](#Playing-With-APIs )
	* [ Authentication With APIs:: JWT { JSON Web Tokens } ](#Authentication-With-APIs::-JWT-{-JSON-Web-Tokens-} )
	* [ Setting Up Passport JWT ](#Setting-Up-Passport-JWT )
	* [Creating a Token  ](#Creating-a-Token)
	* [ Authentication And Authorization ](#Authentication-And-Authorization )

* [➤ Social Authentication  ](#Social-Authentication )
	* [ Creating Credentials on Google ](#Creating-Credentials-on-Google )
	* [ Social Authentication:: How does it work ](#Social-Authentication::-How-does-it-work )
	* [Setting up Passport - Google - OAuth  ](#Setting-up-Passport---Google---OAuth )
	* [ Using Google Auth:: With a Link ](#Using-Google-Auth::-With-a-Link )
 
* [ ➤ Parallel Jobs + Mailer  ](#Parallel-Jobs-+-Mailer- )
	* [Setting Up Nodemailer  ](#Setting-Up-Nodemailer )
	* [ Sending Our First Email via SMTP ](#Sending-Our-First-Email-via-SMTP )
  * [ Send HTML Template Emails ](#Send-HTML-Template-Emails )
	* [  Introduction to Delayed Jobs](#Introduction-to-Delayed-Jobs )
        * [Installing and Understand KUE ](#Installing-and-Understand-KUE ) 
	* [Setting KUE and Using It  ](#Setting-KUE-and-Using-It )



* [ ➤  Friends + Likes ](#Friends-+-Likes )
	* [ Polymorphic Relations ](#Polymorphic-Relations )
	* [ Schema Setup:: Likes ](#Schema-Setup::-Likes )
  * [Actions and Routes:: Likes  ](#Actions-and-Routes::-Likes  )
	* [ Making Friendships ](#Making-Friendships )
	* [Understanding the Code:: Friendship  ](#Understanding-the-Code::-Friendship ) 


* [ ➤ Chatting Engine  ](#Chatting-Engine  )
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
  
