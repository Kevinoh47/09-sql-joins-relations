# Project Name
Lab 09 SQL JOINS RELATIONS

**Author**: Nick Welch and Kevin O'Halloran
**Version**: 1.0.0 

## Overview
<!-- Provide a high level overview of what this application is and why you are building it, beyond the fact that it's an assignment for a Code Fellows 301 class. (i.e. What's your problem domain?) -->
This blogging application allows readers to filter articles by author or category, and allows writers to upload their articles via an online form.

## Getting Started
<!-- What are the steps that a user must take in order to build this app on their own machine and get it running? -->
Fork and clone the github repository
install Node.js
install Postgressql and in a terminal, start psql and create a lab9 database. 
From the working subdirectory in a terminal, type npm init
Type node server.js to start the webserver.
With the webserver running, in a browser navigate to localhost:3000


## Architecture
<!-- Provide a detailed description of the application design. What technologies (languages, libraries, etc) you're using, and any other relevant design information. -->
This application uses Postgresql as the backing relational datastore.
The web server is built in Node.js.
The front end code consists of HTML, handlebar templates, JavaScript, jQuery, and CSS.

## Change Log
<!-- Use this are to document the iterative changes made to your application as each feature is successfully implemented. Use time stamps. Here's an examples:

01-01-2001 4:59pm - Application now has a fully-functional express server, with GET and POST routes for the book resource.
-->

Author: Kevinoh47 <kohok47@gmail.com>
Date:   Sat Aug 18 16:12:26 2018 -0700

    finished changes to server.js

commit bd9b4d30981a4430b1d114318642e1191992b76e
Author: Kevinoh47 <kohok47@gmail.com>
Date:   Sat Aug 18 14:11:25 2018 -0700

    all sql should be working

commit 3f73c7938260bd877be883a980532ba369318329
Author: Kevinoh47 <kohok47@gmail.com>
Date:   Thu Aug 16 13:51:10 2018 -0700

    code for inserting article is now working

commit d9643a61843be92b09442e6960f9733428ed0154
Author: Kevinoh47 <kohok47@gmail.com>
Date:   Thu Aug 16 12:45:07 2018 -0700

    server running and sql select added

commit c9327f6405adea498850a75f34e4e11f645060fc
Author: Kevinoh47 <kohok47@gmail.com>
Date:   Thu Aug 16 11:24:44 2018 -0700

    first commit with working folder

commit a73261dd72feca3452a0f43680ff3619ae990b4c (origin/master, origin/HEAD, master)
Author: JB Tellez <jb.tellez@gmail.com>
Date:   Wed Aug 15 20:32:03 2018 -0700

    publishes lab

commit 85052c962eb2ab463978facfaaaf4b592b79bfb6
Author: JB Tellez <jb.tellez@gmail.com>
Date:   Wed Aug 15 20:26:48 2018 -0700

    Initial commit

## Credits and Collaborations
<!-- Give credit (and a link) to other people or resources that helped you build this application. -->

