# <center style="font-weight: bold"><span style="color:red">reddi</span>Sort Web App</center>

![](assets/screenshot.JPG)

## Features
- Organize your saved Reddit posts by subreddit
- Search globally through all subreddits, or search within a specific subreddit (you can also use both at the same time)
- Toggle which subreddits will have their content displayed
- Easily access saved content by clicking the title displayed on a card
- Test the web app using a demo account

## Compatibility

This web app has been tested on Chrome, Firefox, and Safari for iOS.

## Privacy
reddiSort functions without the use of a database, and no user data is ever stored on the server. When a user authenticates the app with their reddit account an OAuth2 access token is stored in the browser and can be used to retrieve the user's data from the reddit API for up to one hour.

## Tech Stack

### Frontend:
- Framework: React
- Styling: CSS
- Hosting: DigitalOcean VPS

### Backend:
- NodeJS, Express, Oauth2
- Hosting: Heroku

## What I Learned From This Project

### React
- State Management
- Lifecycle Methods
- Component Management

### Authentication
- OAuth2
- JSON Web Tokens

### Design
- Adobe XD
- Masonry Style Layout with CSS Grid
