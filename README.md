# Findtrend - Trend Aggregation Web Application

Findtrend is a web application designed to help you gather all your favorite websites in one place, minimize your browser tabs, and stay updated on trending topics. It features a smooth user interface with a fixed navigation menu, interactive sections, and a dynamic pricing table.

## Features

- **Navigation Menu:** A responsive, fixed navigation menu that lets users navigate to different sections of the page.
- **Hero Banner:** A large banner with a call-to-action button and tab previews.
- **Productivity Tools:** Helps increase productivity by organizing your browsing experience.
- **Partner Logos:** Displays partner companies like Microsoft, Allianz, Upwork, and LinkedIn.
- **Icon Gallery:** Features interactive icons that reveal images when clicked.
- **Pricing Table:** A detailed pricing table with three plans: Personal, Regular, and Premium.
- **Subscription Section:** Allows users to join and receive updates via email.
- **Smooth Scrolling:** Enhances user experience with smooth scrolling navigation.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/BurdeyniyB/Findtrend-Cover.git
   
2. Navigate to the project directory:

   ```bash
   cd Findtrend-Cover

3. Install dependencies:

   ```bash
   npm install

4. Start the server:
   ```bash
   npm start

5. The application will be running on http://localhost:3000.

## Usage

Once the server is running, the application can be accessed through your web browser. The homepage will load with the following sections:

- **Hero Section:** Highlights the core message of the application, encouraging users to minimize their browser tabs and find trending topics in one place.
- **About Section:** Provides a brief description of the app's purpose, explaining how Findtrend helps to increase productivity by aggregating favorite websites.
- **Partners Section:** Displays logos of partner companies such as Microsoft, Allianz, Upwork, and LinkedIn.
- **Feature Icons Section:** Allows users to interact with icons, which when clicked, reveal images describing additional features of the application.
- **Pricing Section:** Lists the available pricing plans, including Personal, Regular, and Premium options, detailing the features and prices for each plan.
- **Subscribe Section:** Provides an option for users to subscribe to receive updates about the latest trends and application features.

## Technologies

### Frontend:
- **HTML**: Used for the structure of the webpage.
- **CSS**: Custom styles defined in `css/style.css` to design the layout and appearance of the webpage.
- **JavaScript**: Scripts for interactivity, with files such as:
  - `js/scroll.js`: Implements smooth scrolling when navigating through the page.
  - `js/menuBtn.js`: Controls the functionality of the hamburger menu for mobile view.
  - `js/icons.js`: Manages the feature icon interactions, revealing images when clicked.

### Backend:
- **Node.js**: JavaScript runtime for the server-side environment.
- **Express.js**: Web framework for handling static files and routing in the application.
