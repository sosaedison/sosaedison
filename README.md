# Welcome 
I'm Sosa Edison, a software engineer based in Minneapolis, Minnesota. I like to test new technologies on this github and keep up with the basics of software development: TDD, CI/CD, building apps that scale well and thoughtful design decisions.

### email: me@sosaedison.io
### [linkedIn](https://www.linkedin.com/in/sosa-edison/)
### phone: (763) 221 - 1146

# Current Projects:
- ## [0] real-time chat applicaiton (built with scale in mind): 
  - The aim of this project is to go beyond the basic chat app that I've built before and to leverage technologies that companies use throughout the industry to solve common issues. Namely, decoupling and asynchronous messaging
  - ### Stack:
    - Backend:
      - FastAPI:
        - for learning purposes only. i could use flask but i wanna learn about fastapi
    - Frontend:
      - We'll use react as a frontend as to keep up to date with all things react
    - Datastore:
      - while the mvp of this app won't store message history, i plan to use a key-value store to record message history since the data is not relational by nature
      - Other chat information, like users and their accounts and their friends can be relational if the project reaches that scope
    - Middleware:
      - Authentication: if the app reaches this scope, we'll integrate with some third part social media logins 
      - Message Queue: in order to decouple the sending and recieving of messages, we'll include a message queue sync as if users could connect to different servers
  - ### Deployment:
    - Phase 1 -- we'll complete a simple react app that connects to the backend and sends messages through a websocket
    - Phase 2 -- we'll learn how to containerize our frontend and backend apps with docker and make sure the app works as intented
    - Phase 3 -- create CI/CD pipeline for deploying the app and new features
    
