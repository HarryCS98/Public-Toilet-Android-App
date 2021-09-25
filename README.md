# Public toilet Android APP (Work In Progress)


### Contents of project

- Introduction to the project
- Current Features/Planned Features
- [Project Progress](https://github.com/HarryCS98/public-toilet-Android-App/blob/main/README.md#download-link)
- [Dowload Link](https://github.com/HarryCS98/public-toilet-Android-App/blob/main/README.md#download-link)
- Source Code



## Introduction to the project
This project was created after a friend of mine was diagnosed with Crohns disease. Crohns disease is a serve type of inflammatory bowel disease which causes extreme pain and discomfort during out breaks and causes the need to be able to find and access toilets quickly often with little notice. I looked at the current public toilet apps on the app store and i found they where badly designed hard to use and had outdated information contained within them. So i decided to create my own completely free public toilet map App of the UK. The initial app is being developed for android with the backend (RESTAPI in laravel 8) but I hope to make a matching IOS app in the future.


## Current Features/Planned Features

 - [x] Map loading and tracking current location
 - [x] Scraping up to date public toilet information
 - [x] Loading toilet locations from JSON file
 - [x] Loading toilet locations from external database
 - [x] RESTAPI created using laravel 8 for serving toilet locations and handling logging in and registering.
 - [x] Login (token)/ Logout and Registration working in app
 - [x] Login and Register field validation in app (Required fields, non unique emails, non matching password and confirm passwords, not correctly formatted email address, insecure passwords)
 - [x] Customisation of map style
 - [x] Custom Icon markers for toilet locations
 - [x] Custom clustering algorithm meaning 6k toilet locations can be loaded smoothly and zooming performance is great
 - [x] Error handling for  connection failures/Database failures
 - [ ] Custom cluster icons
 - [ ] Custom information windows when selecting a toilet location
 - [ ] GUI Design (Currently all placeholder)
 - [ ] Loading in descriptions and toilet information (accessibility options)
 - [ ] User added toilet locations
 - [ ] User reviews for toilets
 - [ ] Opening and closing times for toilets (Effecting toilet location marker)
 - [ ] Leader Boards
 - [ ] Profile pictures for accounts
 - [ ] Advanced registration and login features (Verify email address, forgotten password)
 - [ ] Custom Online dashboard to view (accounts created/deleted, Database and connection statues, Errors logged and sent from users, Location data visualization data from users locations, Server status and performance)
 - [ ] Online admin controls for users, reviews and toilet location management
 - [ ] Toilet location History
 - [ ] Toilet location favourites
 - [ ] Toilet location searching
 - [ ] Location Searching within map (For example searching for London and see all toilets there)
  



  ## Project Progress

**Locations loaded from database:**

[![Image from Gyazo](https://i.gyazo.com/3e94490d95c108527acd047d98e80fc5.png)](https://gyazo.com/3e94490d95c108527acd047d98e80fc5)


**Locations loaded from JSON:**

[![Image from Gyazo](https://i.gyazo.com/dd5aa454b2f843c77e1fb6c44e03f7af.png)](https://gyazo.com/dd5aa454b2f843c77e1fb6c44e03f7af)

**Custom Clustering: [More Custering GIF's](https://i.gyazo.com/eb3681cb010b6e687c8994a0cbee8eef.gif)**


[![Image from Gyazo](https://i.gyazo.com/e52316cc18ab55bebd98a3ff1605f73e.gif)](https://gyazo.com/e52316cc18ab55bebd98a3ff1605f73e)



**Map Styling:**

[![Image from Gyazo](https://i.gyazo.com/cb191b9caf4b620074c3c30063669684.gif)](https://gyazo.com/cb191b9caf4b620074c3c30063669684)


**Error handling for when database connection not available:**

[![Image from Gyazo](https://i.gyazo.com/616a29cd8ec07479f3b5ef3da5ec4997.gif)](https://gyazo.com/616a29cd8ec07479f3b5ef3da5ec4997)


**Validation for Register and login forms:**

[![Image from Gyazo](https://i.gyazo.com/20772164ca0baa8512505a1ae4c91a1c.png)](https://gyazo.com/20772164ca0baa8512505a1ae4c91a1c)

[![Image from Gyazo](https://i.gyazo.com/01f437ed7bc32aea34c76025b658b1b2.png)](https://gyazo.com/01f437ed7bc32aea34c76025b658b1b2)


**In App Registration:**

[![Image from Gyazo](https://i.gyazo.com/e12fb315eb0669128dccaeb1aeb84ba4.gif)](https://gyazo.com/e12fb315eb0669128dccaeb1aeb84ba4)


**Logging in:**

[![Image from Gyazo](https://i.gyazo.com/abd3d64061a48e7189f014204c610228.gif)](https://gyazo.com/abd3d64061a48e7189f014204c610228)



  ## Download Link

> Coming Soon

  ## Source code 

> On Request
