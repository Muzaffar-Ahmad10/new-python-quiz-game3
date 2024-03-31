# Python Quiz Game 

- This python Game is consist on Quiz. 
- Its also a good way to learn information about some programimng languages.
- Game is very simple and informativ.


[Here is the live Quiz Game.](https://python-quiz-game-3ac9886f5af6.herokuapp.com/)

![An image previewing all devices](/assets/main.jpeg)

 ## How to play
 
- Firstly players need to sign up and after that they can continue the game.
- Players can select language and then continue the quiz in selected language. 
- At the end players can see the result. Players can also re-try the game. 
- players select the option by pressing the numbers.  

## Project Goals
### User Stories

- Play Quiz game
- Be able to sign up as new user
- Be able to login as existing user
- Be able to read the rules
- Be able to restart the game

### Site Owner Goals

- Create a game which is easy and clear to user
- Ensure that new user is able to signup
- Ensure that existing user can login
- Ensure that user is able to understand the game
- Ensure that user can restart the game

## User Experience
### Audience
- There is no specific players for the game. 
- I would recommend that its also a game to improve knowledge about the programming languages.

### User Requirements and Expectations

- A simple and fun game
- Straightforward Navigation
- Log-in works as expected and incorrect details do not allow the user access to their account.

#### Sign Up
- If user is a new player, they will be required to sign up
- The user will press the number to select the sign up
- User will be required to enter a new name and password
- Once sign up is successful, user will be ask to login to play the game


#### Login

- If user is an existing user, they will be asked to enter username and password
- If it matches will the data, the user will be logged in.

## User Stories

### Users

1. I want to be able to have an option as existing user or new user
2. I want to able to signup as new user
3. I want to be able to log-in if I return to the game
4. I want to be able to restart game when I'm logged in

### Site Owner

1. I want users to have a positive experience whilst playing the game
2. I want user names and password to play the game.



## Features
### Existing Features

- Firstly we enter yes to start the game, and then select the option 
<details>
    <summary>Sign Up Area screenshot</summary>
    <img src="assets/welcome.jpeg" alt="Sign up area">
</details>

- User can login or sign up by selecting the 2 number.

<details>
    <summary>After Sign Up Area screenshot</summary>
    <img src="assets/signin.jpeg" alt="After Sign up area">
</details>

- After sign in user can select the language and start the game.

<details>
    <summary>Enter Password screenshot</summary>
    <img src="assets/select type.jpeg" alt="Enter Password">
</details>

- At the end of the quiz user can see the score.

<details>
    <summary>score screenshot</summary>
    <img src="assets/result.jpeg" alt="score">
</details>

- If user want to know about the right answers the press Y

<details>
    <summary>result screenshot</summary>
    <img src="assets/answers.jpeg" alt="result">
</details>

- If user want to re try the game press Y

<details>
    <summary>Re-try screenshot</summary>
    <img src="assets/retry.jpeg" alt="re-try">
</details>

## Technology Used
### Language Used

  - Python
### Other websites and tools used

- [GitHub](https://github.com/) was used for saving and storing files.
- [GitPod](https://www.gitpod.io/) was the IDE used for writing code.
- [Heroku](https://www.heroku.com/) was used as the deploying platform for this site.

## Testing
- Manual testing of user stories
- Testing on Browsers
- Validator Testing
- Tested in my local terminal and code institute Heroku terminal.
### Validator Testing
- PEP8
Python code that passes through a linter (eg PEP8) with no significant issues. All the code is working perfectly

### Bugs and Fixes
#### unfixes bugs
- In pep8 code got some errors (line too long (93 > 79 characters))


## Deployment
### Deploying the website in Heroko:
- The website was deployed to Heroko using following steps.
- Make an account in Heroko and login.

#### Creating an app
  - Create new app in the top right of the screen and add an app name.
  - Select region
  - Then click "create app".

#### Open settings Tab
  ##### Click on config var
  - Store CREDS file from gitpod in key and add the values
  - Store PORT in key and value

 ##### Add Buildpacks
  - Add python buildpack first
  - Add Nodejs buildpack after that

 #### Open Deploy Tab
   ##### Choose deployment method
  - Connect GITHUB
  - Login if prompted  

##### Connect to Github
  - Choose repositories you want to connect
  - Click "Connect"

##### Automatic and Manual deploy
  - Choose a method to deploy
  - After Deploy is clicked it will install various file

##### Final Deployment
  - A view button will display
  - Once clicked the website will open


## Credits
#### The following code idea was taken from google search and various youtube videos

### Thank You
- To my mentor Mo Shami for supporting me.
- Special thanks to my friend to help me finding out the issues in the game
- To Code Institute and Slack community for helping me when I was getting stuck with some challenges.