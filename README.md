# PlatePal

CodePath WEB103 Final Project

Designed and developed by: Julia Alfaro, Devin Khun, Michael Ly

🔗 Link to deployed app:

## Table of Contents
* [PlatePal](#platepal)
* [About](#about)
* [Description and Purpose](#description-and-purpose)
* [Inspiration](#inspiration)
* [Tech Stack](#tech-stack)
* [Features](#features)
* [Additional Features](#additional-features)
* [Installation Instructions](#installation-instructions)

## About

PlatePal is an interactive recipe-sharing platform where culinary enthusiasts can not only showcase their own creations but also explore and review recipes from a global community. With powerful filters for dietary restrictions, meal types, and international cuisines, PlatePal ensures users can easily find the perfect dish to match their taste and lifestyle preferences, making it the ultimate destination for food lovers.

### Description and Purpose

We wanted to create a webpage where users can share recipes with each other, and provide feedback to others about the recipes they’ve tried. Additionally, this website can help people explore dishes from different cultures, or possibly reconnect with their own. 

### Inspiration

We felt inspired by the fact that there are a lot of unique people with unique tastes in this world, and the desire to connect with others across the world over something we share in common: food. Everyone needs to eat, and most enjoy doing so, and thus sharing recipes with others is a great way to connect people and learn about different cultures, try to be healthier, or learn something new!

## Tech Stack

Frontend: React, Typescript, TailwindCSS, MaterialUI

Backend: Node.js, Express, Railway hosting the PostgreSQL Database, Prisma

DevOps: ESLint + Prettier, Docker

## Features

### Sign Up/Log In User Authentication

Users must create an account to post recipes, and they’ll need to log in each time they visit. The platform will maintain a user database to manage accounts and authentication.

[gif goes here]

### Publish Recipes

Users can publish recipes by providing the name, ingredients, steps, and relevant tags for filtering. Once a recipe is live, users can edit or delete it at any time.

[gif goes here]

### ✅  Recipes Feed 

The main page displays a variety of recipes.
![RecipeFeedClip1](https://github.com/user-attachments/assets/731c953c-5dd4-4c50-a54a-1eb1db1472b5)


[gif goes here]

## Additional Features

### Review Other Recipes
Users can leave reviews on other recipes (1-5 stars with commentary). This is what will determine the highest-rated recipes.

### Bookmark Other Recipes
Users can bookmark other recipes they really like so they can easily access them again

### Filter By Ingredients
Users can find recipes that save them a trip to the grocery store by selecting only the ingredients that they have, and the webpage will only show recipes that they can make with what they have

## Installation Instructions

### Prerequisites

Make sure you have the following installed:
* Node.js (v14 or later)
* npm (v6 or later)

### 1. Clone the Repository

```bash
git clone https://github.com/Shadowowl888/WEB103-FinalProject.git
cd WEB103-FinalProject
```

### 2. Install Client (Frontend)

Navigate to the client directory and install the dependencies:

```bash
cd client
npm install
```

### 3. Install Server (Backend)

Navigate to the server directory and install the dependencies:

```bash
cd ../server
npm install
```

### 4. Set Up PostgreSQL Database

Make sure you have PostgreSQL running and set up your .env file in the server directory with the database connection string:

```php
CONNECTION_STRING="postgresql://postgres:<password>@junction.proxy.rlwy.net:<port>/railway"
```

### 5. Run the Client and Server

In separate terminal windows, run the following commands:

* Client (Vite React):

```bash
cd client
npm run dev
```

* Server (Express):

```bash
cd ../server
npm start
```

### 6. Access the Application
The frontend will be available at http://localhost:3000, and the backend API at http://localhost:4000.
