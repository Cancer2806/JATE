# JATE

![License](https://img.shields.io/badge/License-MIT-yellow.svg)
  
## Description  

Simple Text Editor deployed to Heroku as a Progressive Web Application, using Webpack   



## Table of Contents

- [Installation](#installation-notes)
- [Usage](#usage)
- [Credits](#credits)
- [Contributing](#contributing)
- [Questions](#questions)
- [License](#license)



## Installation Notes  

  Copy from Github and maintain folder structure.  Open to the folder and use NPM to install the dependencies.  Once complete, you can type npm run start to open the applicationto the local server.   


## Usage 

  Project is deployed to Heroku.  Navigate to the deployment at 
  
  ova or similar software can be used to test the routes.  Users can be created, updated and deleted.  Thoughts can be created, updated and deleted.  A single user or all users can be displayed.  A single thought or all thoughts can be displayed.  Reactions can be added or removed from thoughts.  Friends (other users) can be added or removed from a Users profile.  Thoughts are linked to the User that created the thought and reactions retain the identity of the User entering the reaction.  The majority of the data is dated on creation.   

<br>

  A video walkthrough of the routes in action can be found at: 

<br>

  The Project code repository is stored at: https://github.com/Cancer2806/Thoughts 


<br>

  Following are screenshots showing the routes being used in Nova:  


Get Users:
<br>
<img src="./assets/images/GetUsers.png" width=700 alt = "Get All Users">  
This route lists all users with Friends and Thoughts fully populated

<br>

Delete Thought:
<br>
<img src="./assets/images/DeleteThought.png" width=700 alt = "Delete a Thought">  
This route allow a Thought to be deleted  

<br>

Add Friend:
<br>
<img src="./assets/images/AddFriend.png" width=700 alt = "Add a Friend">  
This route add a Friend sub-document to a User  

<br>

Delete User:
<br>
<img src="./assets/images/DeleteUser.png" width=700 alt = "Delete a User">  
This route deletes a User along with all of their Thoughts  

<br>


## Credits  

  Node, MongoDB, Mongoose, Express, are heavily used in the Project.  Nova was used for testing the routes.   


## Contributing  

  Suggestions for contributions can be sent by email   


## Questions
Questions can be submitted by email

Github:  https://github.com/Cancer2806

Email:  frank.lavery@westnet.com.au


## License
This project is licensed under [MIT](https://opensource.org/licenses/MIT).