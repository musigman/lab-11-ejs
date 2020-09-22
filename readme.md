# book_app
Lots of information about any city of your choosing!  The website displays information for a user defined city through aggregation of data via 6 APIs.


# City Explorer

**Author**: Paul Leonard and Keith Musig
**Version**: 1.1.0 (increment the patch/fix version number if you make more commits past your first submission)

## Overview
When traveling to a new city, or waking up in your home town, there is so much information you need for the day!  What's the weather going to be like?  Do you need a coat or umbrella?  What time do you need to get out of work to catch the new flick at the theatre?  Have any dinner plan ideas?

City Explorer brings answers to all of these questions and more with one simple stop!  Explore your or any other city just by entering the name and clicking Explore!

## Getting Started
1. Create a new repo on GitHub
1. Populate repo with base structure including gitignore, eslintrc, readme, and data files.
1. Create an express server
1. Deploy to Heroku
1. Get city of interest from the user using a route
1. Define routes and actions to take for given routes
1. Injest data from JSON files
1. Restructure data appropriately to format expected by client
1. Protect for mishaps with try/catch and error codes


## Architecture
This project develops a backend information gathering, management, and aggregation system to provide data to an existing front end interface called City Explorer.  The information is collected across 6 APIs and consolidated using object constructors.  The backend is written in JavaScript using Node.js.  Libraries used in this server include express, dotenv, and cors.


## Change Log
09-14-2020 4:50pm - Created repo, populated file structure, set up server.js and supporting files (package.json; lock-package.json; .env).

09-14-2020 6:00pm - Application now has a fully-functional express server, with a GET route for the location resource.

09-14-2020 10:55pm - Weather and date now returns.

09-14-2020 11:05pm - Error codes in place.

**1.1.0** 09-15-2020 4:45pm - Refactored weather handler to use .map.

**1.2.0** 09-15-2020 6:15pm - Connect to real location API

**1.3.0**  09-15-2020 x:xxpm - Connect real weather API

**2.0.0**  09-15-2020 1:50am - Added trail, location, weather API to provide real data

**2.1.0**  09-16-2020 12:08am - Added SQL server support and table

**3.0.0**  09-18-2020 2:29am - postgres SQL DB functioning to supply data to limit API calls


## Credits and Collaborations
- Collaboration with Dominique Augurson
- [Converting Date String to DATE Object](https://stackoverflow.com/questions/5619202/converting-a-string-to-a-date-in-javascript/5619263)
- [Method to Create Date String in Format Desired](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/toDateString)
- [How to refer to an object's parameter without dot notation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_Objects)


## Time Log





Number and name of feature: 1: scaffold server, libraries, proof of life on heroku

Estimate of time needed to complete: 1.5-2 hours

Start time: 1:50pm_____

Finish time: 4:58; with one hour break

Actual time needed to complete: 3 hours






Number and name of feature: 2|create forms and deploy to heroku

Estimate of time needed to complete: 0.5 hours 

Start time: 5pm

Finish time: ~5:30pm

Actual time needed to complete: ~0.5 hours






Number and name of feature: 3|setup google api and make constructor for Books; render page

Estimate of time needed to complete: 1.5-3 hours

Start time: ~5:30pm

Finish time: 7:00pm

Actual time needed to complete: 1.5 plus tuesday when finish


Number and name of feature: 4________________________________

Estimate of time needed to complete: _____

Start time: 2:20pm_____

Finish time: _____

Actual time needed to complete: _____