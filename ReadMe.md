#Title : Personal Gallery

#Author : [Ngugidavid](github.com/Drongo-1)

## Description
This web-app allows a user to create a Profile,add a Location and Post that are all under his username allowing other users to vote for them.

## Setup/Installation Requirements

### Known Bugs

### Behaviour Driven Development
* The program should return all users posts on the home page<br>
Given:All posts<br>
When: Url is changed to home page<br>
Then: All Posts are displayed<br>

* Modal should be displayed when the user clicks on any post and have the post's details<br>
Given:A Post<br>
When: User cicks on the post <br>
Then: A modal with the post's details is displayed<br>

* Admin site should be displayed when "admin/" url is chosen<br>
Given: An admin url<br>
When: User enters admin url in browser<br>
Then: Admin Login is displayed<br>

* User authentication occurs when Admin tries to Login<br>
Given:Admin page is accessed<br>
When: User tries to login<br>
Then: User details are authenticated to confirm if user is an admin<br>

* User session should end when logout url is chosen<br>
Given:Logout option is given<br>
When: User chooses logout option<br>
Then: User session is ended<br>


### Technologies Used
* Vs code was the source code editor of choice.
* Git and Github were used as my local and online repositories respectively.
* Django was used as the framework of choice
* Heroku was used in deploying the live site


### Support and contact details

### License
Moringa School
Copyright (c)2021 **Instagram by Yours-Ngugidavid**