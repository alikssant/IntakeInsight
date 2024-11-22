ntakeInsight - Calorie Tracking Web App
Welcome to IntakeInsight, a calorie tracking web application that helps you monitor your daily calorie intake and expenditure. This project is built using JavaScript, leveraging a class-based structure, Bootstrap for styling, and Webpack for managing JavaScript files.


Project Overview
IntakeInsight is a JavaScript-based web app that tracks calories eaten and burned. It allows users to manage their meals and workouts easily. The app is structured using multiple JavaScript classes to ensure code modularity and maintainability.

Features
Meal Tracking: Add and manage meals, tracking calories consumed.
Workout Tracking: Track workouts, monitoring calories burned.
Real-time Updates: Calculate the total calorie balance based on your daily activities.
Responsive Design: Styled using Bootstrap for a responsive user interface.
Class-based Structure: The project uses JavaScript classes for better code organization.
Technologies Used
JavaScript (with ES6 Classes)
Bootstrap (for UI Styling)
HTML/CSS
Webpack (for bundling and module management)
npm (Node Package Manager)






Install dependencies using npm:


#npm install
Build the project with Webpack:


#npm run build


Open the index.html file in your browser to view the app.

Usage
Once the project is set up, you can:

Add new meals to track calorie intake.
Record workouts to monitor calories burned.
View your daily calorie balance.
Modify or delete existing entries.

The project is organized as follows:


/project-root
│
├── /dist               # Compiled output (Webpack)
├── /src                # Source files
│   ├── index.html      # Main HTML file
│   ├── style.css       # Custom CSS styles
│   ├── /js             # JavaScript files
│       ├── App.js      # Main App class
│       ├── Meal.js     # Meal class
│       ├── Workout.js  # Workout class
│       └── Tracker.js  # Tracker class
├── package.json        # Project configuration
├── webpack.config.js   # Webpack configuration
└── README.md           # This README file


