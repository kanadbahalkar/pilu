# Pilu
Simple Instagram Clone built on MEAN stack

### Installation
cd client

bower install

npm install

cd ..

cd server

npm install

### Running
Go to server directory and start the API server: node server.js

Go to client directory and serve the frontend: grunt serve


### API Docs
Server runs on: https://52.203.15.26:4731

Base API route: https://52.203.15.26:4731/api

Subsequent routes: 
1. Get publicly available stories for users who are not logged in

getPublicStories: /stories/public

2. Get stories for users who are logged in

getUserStories: /stories/mystories

3. Create a new story

addNewStory: /stories/new

4. Update a story

updateAStory: /stories/update

5. Delete a story

deleteAStory: /stories/delete

6. Write a new comment 

addNewComment: /comments/new

7. Delete a comment

deleteAComment: /comments/delete




