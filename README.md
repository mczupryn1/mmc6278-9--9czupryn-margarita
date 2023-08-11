# Meal Planner and Recipes App

Meal Planner is a simple web application crafted to help you manage and plan your meals effortlessly. Dive into our collection of recipes, personalize your meal plan, and set your culinary journey on a streamlined path.

![Meal Planner Application Screenshot](index.png)
![Recipe Application Screenshot](recipes.png)

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Configuration](#configuration)
  - [Running the Application](#running-the-application)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Browse & Select:** Dive into a collection of delicious recipes.
- **Personal Meal Plan:** Customize and view your meal plan, curated with your chosen recipes.
- **Manage With Ease:** A user-friendly interface to manage and plan your meals.

## Getting Started

### Prerequisites

- Node.js
- Express.js
- A relational database (MySQL, PostgreSQL, etc.)

### Installation

1. **Clone the Repository:**

```bash
git clone https://github.com/mczupryn1/mmc6278-9--9czupryn-margarita.git
cd mmc6278-9--9czupryn-margarita
```

2. **Install Dependencies:**

```bash
npm install
```

### Configuration

Ensure you have a `.env` file in your root directory with all the necessary configurations:

```makefile
SESSION_SECRET=your_session_secret
```

### Running the Application

```bash
npm start
```

Your application should now be running on `http://localhost:3000/`.

## Usage

Browse through the vast collection of recipes and seamlessly add them to your personalized meal plan. View and manage your plan with just a few clicks.

## API Endpoints

- **GET /recipes** - Fetch a list of available recipes.
- **POST /add-to-mealplan** - Add a chosen recipe to the user's meal plan.

## Contributing

Contributions are welcomed! Ensure you adhere to the coding standards set for this project.

## License

This project is licensed under the MIT License.

---