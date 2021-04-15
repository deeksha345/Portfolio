---
title: Board Game Tracker
technologies: React Native, Backendless
languages: JS, Java
status: In Progress
thumbnail: images/portfolio/app2.jpg
shortDescription: This app lets you keep track of all the board games you have tried and lets you favorite one's you love. 


---
I am using React Native to create the front end for the web app because it allows you to develop native mobile apps for iOS and Android with a single JavaScript codebase. I am using Backendless for the back end because it is an open source project and has comprehensive documentation. 


For this app I will be implementing a google sign-in and user authentication feature. Also, I will be leveraging the Board Game Geek (BGG) APIs to fetch information about board games that users will search for. The BGG API doesn't support Cross-Origin Resource Sharing (CORS) requests because of that I had to employ a workaround and setup a reverse proxy using CORS Anywhere. This was the first time I had to set up a reverse proxy and was a valuable learning process. 