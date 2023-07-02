# Social Network API

![License](https://img.shields.io/static/v1?label=license&message=MIT&color=${badge.color})

  ## Description
  
This social networking api allows creating, updating, and deleting users, thoughts, and reactions. In addition to CRUD functionality, this API allows users to add and remove friends, keeps track of friend count, and number of reactions for each thought posted.
  
## Table of Contents
  
* [Installation](#Installation)
  
* [Usage](#Usage)

* [Walkthrough Video](#Walkthourgh-video)

* [Technologies](#Technologies-Used)
  
* [Contributing](#Contributing)
  
* [Tests](#Tests)
  
* [Questions](#Questions)
  
* [License](#License)
  
## Installation
  
1. Download or clone this repository to your local machine
2. Setup Node and MongoDB to get started
3. Install required dependencies by navigating the root directory in your CLI. Enter `npm i` 
4. To run the application enter `npm start`

## Usage
  
After installing the application enter `npm start` to start your local server. When the server is started the mongoose models will be synced with the MongoDB database "socialDB". To view data in the database, open MongoDB using the URI: mongodb:localhost:27017. Navigate to the socialDB us view users and thoughts collections. To create additional seed data and 

## Walkthrough Video:

[Walkthrough video URL](https://xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx)
  
## Technologies Used

<div style="display: inline_block"><br>
  <img alt="JavaScript" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 <img alt="Node.js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg">
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img height="30" width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" />
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 <img alt="Mongodb" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg">
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[Mongoose](https://https://mongoosejs.com/docs/)
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[Moment.js](https://momentjs.com/)
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</div>

## Contributing
  
Please let me know if you'd like to contribute to this project!
  
## Tests
  
Insomnia is used to test REST API calls. Please see the walk-through demonstration videos: https://xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx as well as the sections on Description and Usage to see how data is added and tested using Insomnia.

On Insomnia, the following API routes have been created and used to add, update, or remove users, friends, thoughts, and reactions in the user's database.

📁 USER

Create a new user: POST /api/users

Get all users: GET /api/users

Get a single user by its id: GET /api/users/:userId

Update a user by its id: PUT /api/users/:userId

Delete a user by its id: DELETE /api/user/:userId

📁 FRIEND

Add a new friend to a user's friend list: POST /api/users/:userid/friends/:friendId

Delete a friend from a user's friend list: DELETE /api/users/:userid/friends/:friendId

📁 THOUGHT

Create a new thought: POST /api/thoughts/

Get all thoughts: GET /api/thoughts/

Get a single thought by its id: GET /api/thoughts/:thoughtId

Update a thought by its id: PUT /api/thoughts/:thoughtId

Delete a thought by its id: DELETE /api/thoughts/:thoughtId

📁 REACTION

Create a reaction: POST /api/thoughts/:thoughtId/reactions

Delete a reaction by the reactionId: DEL /api/thoughts/:thoughtId/reactions/:reactionId  

## Questions
  
Have more questions? Head over to my github profile or email me:
  
[Checkout my GitHub](www.github.com/jhdavey)
  
[Email me!](hdwebdevelopment@gmail.com)
  
## License
  
License: MIT - see the [License](https://choosealicense.com/licenses/mit/) page.
