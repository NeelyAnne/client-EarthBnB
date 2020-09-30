# **EarthBnB Client**

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 10.0.8.

## **Description:**

EarthBnB is a vacation rental site clone that allows a user to click through 20 different location in the United States and see information about each location such as: where the rental is located, price per night to rent, points of interest nearby, host and cohost information, and many other features. Upon loading you are taken to a landing page that contains the cards for all 20 of the locations. As you scroll through each location page, notice that the majority of the information for each separately designed component remains the same even though they were created by completely different people. This is possible due to the server-side and database information that can be found at [EarthBnB Server](https://github.com/NeelyAnne/server-EarthBnB).

EarthBnB is not currently deployed, but can be cloned for local use with the provided instructions or you can check out a demo of the video on my YouTube channel at the link below.

## **Demo Link:**

https://www.youtube.com/watch?v=ozMwkHq5Luc&feature=youtu.be

## **My Contribution:**

My contribution to the EarthBnb application was both the "Location" map component on each individual location page as well as the entirety of the landing page. The actual Location component consists of a Google Maps module built specifically for Angular, as well as a description of the rental city, and a points of interest section near the rental that is powered by Google Places Search API. The longitude and latutide from each location is pulled from a database and displayed on the map in a marker as well, and each point of interest is accompanied by a logo representing what kind of location it is. 

![alt text](https://github.com/NeelyAnne/client-EarthBnB/blob/master/location.png "Map Photo")
![alt text](https://github.com/NeelyAnne/client-EarthBnB/blob/master/poin.png "POI Photo")

The landing page contains a uniquely designed header and BootStrap cards for each location. The background of the cards is the inital image used for each location and the corresponding information is all matching in comparison to the individual pages. You are automatically routed to the landing page when the application opens.

![alt text](https://github.com/NeelyAnne/client-EarthBnB/blob/master/landing.png "Landing Page Photo")

## **Instructions for Local Use:**

(1.) Clone the repository

(2.) Open Terminal or your command line interface of choice and run 'npm install' to download any required node modules

 - If you are unfamiliar with npm visit https://www.npmjs.com/get-npm

(3.) Next, run 'npm start' to open up a localhost version in your default web browser 
 
 - it should open to localhost:3000/
 
(4.) Obtain a Google API key, which you can do for free (up to a certain number of calls) with instructions found here

 - https://developers.google.com/maps/documentation/javascript/get-api-key
 
(5.) Replace the 'key=xxx' located in 1 _-_ the final script tag of the index.html file and 2 _-_ the app/service/addresses.service.ts file to read 'key=[YOUR_API_KEY]'
 
(6.) Browse

 - Click on any of the location cards to be taken to that location page

 - hit the back button to return to our landing page 

(7.) (Optional) To see a specific page simply change the number at the end to any between 1 & 20

 - e.g. localhost:3000/rooms/5 or localhost:3000/rooms/17

 - Most things will not appear correctly without also having the server (link listed above) running.

(8.) (Optional) 'npm test' will run all the pre-written tests 

## **Technologies:**

- JavaScript
- NodeJS
- Angular
- HTML
- CSS
- WebPack
- Google Maps
- Enzyme
- Bootstrap
- Babel

## **Models/Collections:**

 - Locations
 - Host
 - Check Ins
 - Photos
 - Reviews
 - Reservations
 - To Do
 - Amenities
 - Cohost
 - Sleeping Arrangements

## **The Quaran-Team consists of:**

- Bilikis Orulebaja
  - https://github.com/borulebaja
- Brandt Campbell
  - https://github.com/Reboot82
- Brian Loveless
  - https://github.com/BrianLoveGa
- Juan Avalo-Santiago
  - https://github.com/avalojc
- Michal Terranova
  - https://github.com/mrterranova
- Neely Mann
  - https://github.com/NeelyAnne
- Trevor Taylor
  - https://github.com/Trevis42

**Led by management team:**

Fred Zirdung and Jothi Nedungadi

## **Further help:**

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
---

All rights reserved by Talent Path 2020
a division of Genuent.

https://talentpath.com/what-we-do/

https://genuent.com/

