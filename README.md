## Mühle
This is a meta-repo for my implementation of the german board-game 'Mühle'. I made this game as an exercise for learning both angular⁠/⁠typescript and spring⁠/⁠java and to get a feel for developing client/server-applications.

This repo contains both server and client as git submodules.
Either clone it with ```git clone --recursive ``` or run ```git submodule update --init``` after cloning it, to download everything.

You need [Node.js](https://nodejs.org) for the frontend and Java 16 for the backend.

Setup the frontend with:  
```npm install```  
Run the frontend with:  
```ng serve```  
Run the backend with:  
```./mvnw clean spring-boot:run```