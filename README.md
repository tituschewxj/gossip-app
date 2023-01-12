# Gossip-app
A forum made for the CVWO assignment. Still work in progress.

## Overview
Gossip-app is a simple forum that allows for posting and commenting.

## Technologies used
Frontend
 - React.js
    - axios
    - react query
    - moment
 - Typescript
 - MUI

Backend
- Ruby on Rails (as an API)
    - devise-jwt
    - faker
    - kaminari
- sqlite

## Features
- CRUD operations on posts and comments
- User authentication with JWT
- Searching of posts via tags
- User profile pages
- Pagination

## Cloning this repository
`git clone --recursive git@github.com:tituschewxj/gossip-app.git`

## Set up
1. Run backend server on port 3000: `rails s`
2. Run frontend server on port 3001: `yarn run start` and type `y` to use port 3001

### Login information for dummy users
- Default email: `${username}@email.com`
- Default password: `password`

## Submodules
This project has 2 submodules
1. `gossip-app-backend` contains code for the backend api.
2. `gossip-app-frontend` contains code for the frontend.

<!-- # Final DB Schema -->
