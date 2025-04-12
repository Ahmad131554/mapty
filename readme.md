# Mapty

**Mapty** is a workout tracking application that allows users to log their running and cycling activities, map their routes using their geographical position, and track workout details such as distance, duration, cadence, and elevation gain. The app features an interactive map powered by Leaflet to visualize workout locations and provides the ability to store and view previous workouts.

---

## Table of Contents

1. [Project Description](#project-description)
2. [Project Preview](#project-preview)
3. [Features](#features)
4. [Technologies Used](#technologies-used)
5. [Installation Instructions](#installation-instructions)
6. [Usage Instructions](#usage-instructions)
7. [License](#license)

---

## Project Description

**Mapty** is a web-based workout tracker that integrates mapping features to visualize the routes of running and cycling activities. It allows users to enter workout details such as type, distance, duration, cadence, and elevation gain. The app uses the Leaflet library to render maps and store workouts in the browser's local storage, making it easy to view and track past workouts.

---

## Project Preview

You can view a live demo of the project here: [Mapty Demo](https://your-demo-link.com)

---

## Features

- **Geolocation Integration**: Automatically detects and maps the user's current location to add workout details.
- **Map Integration**: Uses Leaflet to plot workout routes on an interactive map.
- **Workout Types**: Allows users to log running and cycling workouts with relevant details.
- **Workout Logging**: Users can input and store workout data, including distance, duration, cadence, and elevation gain.
- **Local Storage**: Workouts are saved locally in the browser, making them available even after the page is refreshed.
- **Responsive Design**: The app is designed to be mobile-friendly, providing a smooth user experience across devices.
- **Interactive Form**: The app displays a form to input workout data and toggle visibility based on the selected workout type.

---

## Technologies Used

- **HTML**: Provides the structure and content of the workout tracker.
- **CSS**: Used to style the page and provide an intuitive user interface.
- **JavaScript**: Handles the logic for tracking workouts, calculating metrics, and interacting with the map.
- **Leaflet**: A JavaScript library used for embedding interactive maps on the page.
- **Local Storage**: Stores workout data in the browser's local storage to retain information across sessions.

---

## Installation Instructions

1. **Clone this repository** to your local machine using the following command:

   ```bash
   git clone https://github.com/yourusername/mapty.git
   ```

2. **Navigate to the project folder:**

   ```bash
    cd mapty

   ```

3. **Open the index.html file** in your preferred browser to start using the app.

   You can open it locally by double-clicking the index.html file, or you can serve it using a local server.

---

## Usage Instructions

- **Log a Workout:** Open the app and click on the map to add a workout. Fill out the form with the workout details (distance, duration, cadence, etc.).

- **View Past Workouts:** All logged workouts will be displayed on the map and in the workout list.

- **Map Navigation:** You can zoom in/out and navigate the map to view workouts from different locations.

- **Input Toggle:** The form allows toggling between "Running" and "Cycling" inputs, with fields specific to each type.

- **Refresh the Page:** Your workouts will be saved in the browser's local storage and can be accessed even after refreshing the page.

---

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more information.
