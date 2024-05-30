# React-Node Recipe Platform 
# Recipe App

## Overview
The Recipe App is a React-based web application that allows users to search for specific recipes or find recipes based on the ingredients they have. The app initially used an ElephantSQL database, but it has now been replaced with MongoDB for better performance and scalability. Additionally, the app fetches recipe data from the Spoonacular API. However, the current API token has expired, and we are in the process of obtaining a new one.

## Features
- **Search Recipes:** Users can search for recipes by entering the name of a dish.
- **Ingredient-Based Search:** Users can input a list of ingredients they have, and the app will suggest recipes that can be made with those ingredients.
- **Responsive Design:** The app is designed to be responsive and user-friendly on both desktop and mobile devices.

## Technologies Used
- **Frontend:** React, HTML, CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (previously ElephantSQL)
- **API:** Spoonacular API (Token expired, awaiting renewal)

## Setup Instructions

### Prerequisites
- Node.js (v12 or higher)
- MongoDB (local or cloud instance)

### Installation
1. **Clone the Repository:**
   ```sh
   git clone https://github.com/calvinpatriot/recipe-app.git
   cd recipe-app
   ```

2. **Install Dependencies:**
   ```sh
   npm install
   ```

3. **Set Up Environment Variables:**
   Create a `.env` file in the root directory and add the following:
   ```sh
   MONGODB_URI=your_mongodb_connection_string
   SPOONACULAR_API_KEY=your_spoonacular_api_key (token expired, awaiting renewal)
   ```

4. **Start the Development Server:**
   ```sh
   npm start
   ```
   The app will be available at `http://localhost:3000`.

## Usage
1. **Search for a Recipe:**
   - Enter the name of a recipe in the search bar and press Enter.
   - The app will display a list of matching recipes.

2. **Find Recipes by Ingredients:**
   - Enter a list of ingredients you have in the search bar and press Enter.
   - The app will suggest recipes that can be made with those ingredients.

## Troubleshooting
- **API Issues:** If the app is not fetching recipes, it is likely due to the expired Spoonacular API token. We are currently waiting for a new token. Please check back later or update the `.env` file with the new token once received.
- **Database Connection:** Ensure your MongoDB instance is running and the connection string in the `.env` file is correct.

## Contributing
We welcome contributions to improve the Recipe App! Please follow these steps to contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new Pull Request.





---

Thank you for using the Recipe App! We hope it helps you find delicious recipes with ease. Happy cooking!
