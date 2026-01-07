# That One Dish
That One Dish is a wep application that helps users save and organize dishes they want to remember. Users can store photos of dishes along with details such as restaurants information, cuisine, and add their personal notes. Dishes can also be saved as inspiration for home cooking. All dishes are shown in a gallery and can be shared with friends through shared boards.

## Problem Statement
People often remember a dish they loved but forget the restaurant name, location, or details of the meal. Existing apps like notes, photo galleries, or social media do not organize these food memories effectively. This makes it difficult to revisit or share favorite meals. 

## Core Features
- User authentication (Sign Up / Log In)
- Create, view, and edit dish entries
- Dish fields: name, photo, description or ingredients, optional restaurant information, add personal notes
- Toggle for restaurant vs. inspiration dish
- Gallery view of saved dishes
- Node.js API with MySQL for database/storage

## Data Model
- **User:** owns dishes and joins boards
- **Dish:** main entity, can be linked to restaurant
- **Restaurant:** stores restaurant information for dishes
- **Board:** shared list of dishes
- **BoardMembership:** connects users and borads

## User Flow
1. User logs in
2. User adds a dish (restaurant or inspiration)
3. User uploads a photo and enters details
4. Dish is saved and shown in the gallery