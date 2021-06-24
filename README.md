# tech-zone

Title: Tech-Zone</br>
Student: Dylan Trecker</br>
Description: A CMS-style tech blog site.</br>
Full Repository: https://github.com/d-trecker/tech-zone.git</br>
Get the repository by: $ git clone git@github.com:d-trecker/tech-zone.git </br>
Heroku: </br>

How to Set Up / Use Locally</br>
- Clone repo by using $ git clone git@github.com:d-trecker/tech-zone.git
- Install respected proper NPM packages by using the command 'npm install' in root directory. 
- Create a '.env' in the root directory.
- Update database name, MySQL username, and MySQL password to the .env file and save. 
- In MYSQL, run source db/schema.sql and USE tech_zone
- Start server by using 'npm start' command in root terminal. 

OR! visit the application on Heroku at: 

User Story </br>
AS A developer who writes about tech
I WANT a CMS-style blog site
SO THAT I can publish articles, blog posts, and my thoughts and opinions

Acceptance Criteria
GIVEN a CMS-style blog site
WHEN I visit the site for the first time
THEN I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in

- When you visit the site, you are presented with the above criteria. 

WHEN I click on the homepage option
THEN I am taken to the homepage

- When you click on the homepage, you are taken to the homepage. 

WHEN I click on any other links in the navigation
THEN I am prompted to either sign up or sign in

- When you click on other links, you are prompted to either sign up or sign in. 

WHEN I choose to sign up
THEN I am prompted to create a username and password

- When you prompted to sign up you are prompted to create user name and password. 

WHEN I click on the sign-up button
THEN my user credentials are saved and I am logged into the site

- When you click the sign up button, you are logged into sign into the site. 

WHEN I revisit the site at a later time and choose to sign in
THEN I am prompted to enter my username and password

- When you revisit the site later, you are prompted to enter username and password. 

WHEN I am signed in to the site
THEN I see navigation links for the homepage, the dashboard, and the option to log out

- When you are signed into the site, the above criteria is displayed. 

WHEN I click on the homepage option in the navigation
THEN I am taken to the homepage and presented with existing blog posts that include the post title and the date created

- When you click on the hommepage option, the above criteria is displayed. 

WHEN I click on an existing blog post
THEN I am presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment

- When you click on and existing blog post, the above criteria is presented. 

WHEN I enter a comment and click on the submit button while signed in
THEN the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created

- When you enter a comment and click submit, the comment is saved and displayed with the above criteria. 

WHEN I click on the dashboard option in the navigation
THEN I am taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post

- When you click on the dashboard in the navigation, the above criteria is presented. 

WHEN I click on the button to add a new blog post
THEN I am prompted to enter both a title and contents for my blog post

- When you click on the button to add a new post, you are presented with an alert to enter both a tile and content for your post. 

WHEN I click on the button to create a new blog post
THEN the title and contents of my post are saved and I am taken back to an updated dashboard with my new blog post

- When you click on the button to create a new blog post, contents are saved and you are taken to an updated dashboard with new post. 

WHEN I click on one of my existing posts in the dashboard
THEN I am able to delete or update my post and taken back to an updated dashboard

- When you click on one of your existing posts, you are able to update or delete post. You are then taken to an updated dashboard. 

WHEN I click on the logout option in the navigation
THEN I am signed out of the site

- When you click logout, you are signed out of the site. 

WHEN I am idle on the page for more than a set time
THEN I am automatically signed out of the site 

- When yoiu are idle on the page for over an hour, you are automatically logged out. 