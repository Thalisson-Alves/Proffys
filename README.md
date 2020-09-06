<h1 align="center">
  <img alt="Proffy" title="#NextLevelWeek2" src="./.github/landing.svg" />
</h1>

# Table of content
- [About](#About)
- [Technologies](#Technologies)
- [How to run](#How-to-run)
  - [Requirements](#Requirements)
  - [Cloning](#Cloning)
  - [Run API](#run-api)
- [Features](#features)

# About
 Proffys (slang for teacher in portuguese) is a plataform to connect teachers and students. As a teacher, you can register yourself putting your information, like price, schedule, biography, profile picture and the subject you want to teach. As a student you can choose the teacher that best fits your preferences, filtering them by subject, class schedule and days of the week.
 Project developed during Next Level Week #2 @Rocketseat
 
 ## Web screen shots
 <div style="display: flex; flex-direction: 'row'; align-items: 'center'; justify-content: space-evenly;">
   <img src="./.github/web_cadastro.png" width="400px">
   <img src="./.github/web_study.png" width="400px">
</div>

 ## Mobile screen shots
 <div style="display: flex; flex-direction: 'row'; align-items: 'center'; justify-content: space-evenly;">
   <img src="./.github/mobile_landing.png" width="180">
   <img src="./.github/mobile_study.png" width="180">
</div>

# Technologies
- Typescript
- React
- React native
- Expo
- Express

# How to run
  ## Requirements
  - Node.js
  - Npm
  - Expo
  
  ## Cloning
  ```bash
  # Clone repository
  $ git clone https://github.com/Thalisson-Alves/Proffy
  
  # Go to Proffy directory
  $ cd Proffy 
  ```
  
  ## Run API
  ```bash
  # Go to server directory
  $ cd server
  
  # Install dependecies
  $ npm install

  # Create sqlite database
  $ npm run knex:migrate
  
  # Run API
  $ npm start
  ```
  API run at http://localhost:3333
  
  ## Run Web project
  ```bash
  # Go to web directory
  $ cd web

  # Install dependecies
  $ npm install

  # Run web application
  $ npm start
  ```
  Web application run at http://localhost:3000

  ## Run Mobile application
  ```bash
  # Go to mobile directory
  $ cd mobile

  # Install dependecies
  $ npm install

  # Install all fonts used
  $ expo install expo-font @expo-google-fonts/archivo @expo-google-fonts/poppins

  # Run mobile application
  $ npm start
  ```
  Download the expo app on your smartphone and read the qr code that will appear in cmd

# Issues
Fell free to send a issue if you found a problem. If you already found a solution to the problem, send me a pull request, I would appreciate it.

<!-- # Features
Some features that I'm working on
- [ ] Extended layout
  - [ ] Login
  - [ ] Sign in
  - [ ] Success screen
- [ ] User authenticator
  - [ ] Web
    - [ ] Remember me
  - [ ] Mobile
- [ ] Password recovery
- [ ] Proffy's profile
- [ ] Splash screen
- [ ] Pagination in the list of Proffys
- [ ] Displaying class schedule
- [ ] Save favorite Proffys
- [ ] Logout
- [ ] Deploy -->