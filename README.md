# Gossip-app
Gossip-app is a minimalistic forum made for the CVWO assignment.

## Features
- CRUD operations on posts and comments
- User authentication with JWT
- Searching of posts via tags
- User profile pages
- Pagination
- Input validation

## Showcase
![Searching with tags](assets/chrome-capture-2023-0-22%20(1).png)
![Searching with tags](assets/chrome-capture-2023-0-22%20(2).png)
![Searching with tags](assets/chrome-capture-2023-0-22%20(3).png)
![Searching with tags](assets/chrome-capture-2023-0-22%20(4).png)
![Searching with tags](assets/chrome-capture-2023-0-22%20(5).png)
![Searching with tags](assets/chrome-capture-2023-0-22%20(6).png)
![Searching with tags](assets/chrome-capture-2023-0-22%20(7).png)
![Searching with tags](assets/chrome-capture-2023-0-22.png)

### Write-up
The mid and final submission write-ups can be found in the write-up folder.
- [Mid-Submission: Execution plan and Use cases](write-up/TitusChewXuanJun_A0251687U.pdf)
- [Final-Submission: Accomplishments and User manual](write-up/TitusChewXuanJun_A0251687U_FinalWriteup.pdf)


### Technologies used
Frontend
 - React.js
    - axios
    - react query
    - moment
    - MUI
 - Typescript

Backend
- Ruby on Rails (as an API)
    - devise-jwt
    - faker
    - kaminari
- SQLite

## Final DB Schema
![DB Schema Diagram](assets/db-schema-diagram.png)
generated with https://dbdiagram.io/

## Submodules
This project has 2 submodules.
<!-- Update submodules with git submodule update --remote -->
1. `gossip-app-backend` contains the source code for the backend api.
2. `gossip-app-frontend` contains the source code for the frontend.

## Set up
### Cloning this repository
Use `git clone --recursive https://github.com/tituschewxj/gossip-app.git` to clone this repository.

### Setting up the backend
1. Navigate to the backend folder.
2. Use `bundle install` to install dependencies in the backend.
3. Use `rails s` to run the backend server on port 3000.

### Setting up the frontend
1. Navigate to the frontend folder.
2. The frontend uses yarn as it's package manager. Use `yarn install` to install dependencies.
3. Use `yarn run start` to run the frontend server on port 3001.

#### Login information for pre-generated fake users
- Default email: `${username}@email.com`
- Default password: `password`

#### Other details
- In `devise.rb`, the `jwt.expiration_time` is set to 30 minutes.
