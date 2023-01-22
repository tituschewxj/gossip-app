# Gossip-app
A forum made for the CVWO assignment.

## Overview
Gossip-app is a minimalistic forum.

## Showcase
![Searching with tags](assets/chrome-capture-2023-0-22%20(1).png)
![Searching with tags](assets/chrome-capture-2023-0-22%20(2).png)
![Searching with tags](assets/chrome-capture-2023-0-22%20(3).png)
![Searching with tags](assets/chrome-capture-2023-0-22%20(4).png)
![Searching with tags](assets/chrome-capture-2023-0-22%20(5).png)
![Searching with tags](assets/chrome-capture-2023-0-22%20(6).png)
![Searching with tags](assets/chrome-capture-2023-0-22%20(7).png)
![Searching with tags](assets/chrome-capture-2023-0-22.png)

## Features
- CRUD operations on posts and comments
- User authentication with JWT
- Searching of posts via tags
- User profile pages
- Pagination
- Input validation

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

## Set up
### Cloning this repository
Use `git clone --recursive https://github.com/tituschewxj/gossip-app.git` to clone this repository.

### Installing dependencies
The frontend uses yarn as it's package manager.
Use `yarn install` to install all dependencies in the frontend.

Use `bundle install` to install dependencies in the backend.

### Running the application
1. Run backend server on port 3000: `rails s`
2. Run frontend server on port 3001: `yarn run start` and type `y` to use port 3001

#### Login information for pre-generated fake users
- Default email: `${username}@email.com`
- Default password: `password`

## Submodules
This project has 2 submodules
1. `gossip-app-backend` contains the source code for the backend api.
2. `gossip-app-frontend` contains the source code for the frontend.

<!-- Update submodules with git submodule update --remote -->