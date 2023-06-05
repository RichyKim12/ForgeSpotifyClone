# SpotifySocial 
## Project Description
Online social music platform to connect with friends and discover new users with similar music tastes. 
## Table of Contents
	Installation ………………. Line X
	How to Use ……………… Line X
	Features & Status …….… Line X
	Credits …………………… Line X
## Installation
This software is to be run locally and will require Node.js and npm (node package manager) installed. To begin installing the app once Node.js and npm are installed, clone the repository and change the directory to the root directory. From there, run the command ‘npm install’ to install all necessary dependencies for the app.
- Npm i firebase
- npm install react-router-dom@6
- npm install @mui/material
- npm install @mui/material @emotion/react @emotion/styled
- npm install @mui/icons-material
## How to use
After installing the required dependencies as listed above. A user may need to request access to the firebase or create their own substitute in the required id/keys. Similarly, a new developer account may need to be created and a new client id listed. Any potential users must be added to the Spotify dashboard. Plan addendums may be required as the free plan may not be suitable for your use.
## Major Components and Features
### Login Page
- Allows the user to create a SpotifySocial account by logging in with Spotify, or login to their SpotifySocial account if it already exists. Additionally, the user will remain logged in after refreshing the page through the use of cookies.
- Status: The Login Page is complete for now,
### Discovery Page
### Users
- A grid showing all users of SpotifySocial.
- Status: The grid of other users currently only shows the usernames of users whose profiles are set to public, but in the future may include links to those profiles in order to view top songs, top artists, and liked songs as specified by those users.
### Discussion Forum 
- A table that lists all public discussion posts. Discussions can be posted by clicking the forum icon and deleted with the three-dot icon. Posts can not be altered after going public. Replies can be viewed with the discussion icon where all replies are listed. Responses cannot be edited after posting
- Status: all components of the discussion are completed
### Messaging
A simple chat feature allowing SpotifySocial users to message other SpotifySocial users from within the app.
Status: The UI for the messaging feature is complete, but still requires a backend connection. In the future, this may include securely storing messages for each user as well as including a search feature to search for new users to message.
### “My Music” Page
### Liked Songs Page
This feature displays the user’s liked songs 8 most recently liked songs. The display shows the liked song with the album cover and artist. The display could show all the liked songs in the past month, year, or all time. 
### User’s Top Artists Page
This feature displays the user’s 8 most listened to artists. The display shows the artist with an album cover. Additionally, the top artist of the past month, year, or all time can be displayed. 
### User’s Top Songs Page
This feature displays the user’s 8 most listened to songs. The display shows the artist with an album cover. Additionally, the top songs of the past month, year, or all time can be displayed. 
### Profile Page
Allows the user to view how other users can see them. Here, the user can see their username and profile picture of their Spotify account
Access to settings
Private / Public profile toggle to control whether or not other users can see them on their
### Discovery Page
Show Top Songs Toggle to choose whether or not to display the user’s top songs on their profile
Show Top Artists Toggle to choose whether or not to display the user’s top artists on their profile
Show Liked Songs Toggle to choose whether or not to display the user’s liked songs on their profile
Status: While the profile page is complete, there is currently no way to view other users’ profiles (just their usernames), so the toggles for top songs, top artists, and liked songs do not have much of an effect.
## Credits
Ethan Haller, Anisha Poudel, Jay Patel, Zaid Fada, Richard Kim
