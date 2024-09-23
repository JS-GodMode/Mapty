

![ezgif com-optimize(1)](https://github.com/user-attachments/assets/15961d9e-ba27-4fe2-b155-86ea8651b4f5)

# Mapty

**Mapty** is a JavaScript-based web application that allows users to track their cycling and running workouts on a map. It leverages geolocation to pinpoint the user's position and allows for the visualization of workout data such as distance, time, and workout type.

## Features

- **Track Workouts**: Users can log cycling and running data.
- **Map Integration**: The app displays the workout location using a map.
- **Geolocation**: Automatically fetches the user's current location for easier tracking.
- **Workout Visualization**: Workout data, including distance, duration, and type (cycling/running), is presented neatly on the map.
- **API Integration**: Uses the [Geocode.xyz](https://geocode.xyz/) API for reverse geocoding to obtain location details.

## Technologies Used

- **JavaScript**: Core functionality of the app.
- **HTML/CSS**: For building the structure and styling the interface.
- **Geolocation API**: Fetches the user's current position.
- **Geocode.xyz API**: Fetches location details such as address based on geographic coordinates.

## Getting Started

### Prerequisites

- A modern web browser (e.g., Chrome, Firefox, etc.) that supports JavaScript and the Geolocation API.
- Basic knowledge of using Git and GitHub.

### Installation

1. Clone the repository to your local machine:
   ```bash
   git clone 'https://github.com/JS-GodMode/Mapty.git`
   ```

1.  Navigate to the project directory:
    ```bash
     cd mapty
    ```
2.  Open the `index.html` file in your browser.

### Usage

1.  **Grant Location Access**: Upon loading the app, it will request permission to access your location. Grant access so the app can center the map on your current location.
2.  **Log Workouts**: Once the map is displayed, click anywhere on the map or use your current location to log a workout. Enter details such as distance, duration, and select whether it is a cycling or running workout.
3.  **View Workouts**: Each logged workout will appear on the map with the location and details. You can view, track, and analyze your activities directly on the map.

API Information
---------------

This app uses the [Geocode.xyz](https://geocode.xyz/) API to obtain address details based on latitude and longitude. You can sign up for an API key and follow their usage limits as specified in their documentation.

### How It Works:

-   **Geolocation**: The app uses the browser's built-in Geolocation API to fetch the user's current coordinates (latitude, longitude).
-   **Reverse Geocoding**: These coordinates are then sent to the Geocode.xyz API to retrieve human-readable address details for the logged workouts.

Project Status
--------------

This project is currently in development. Planned future enhancements include:

-   Editing and deleting workouts.
-   Filtering workouts by type (cycling/running).
-   User authentication and saved workout history.

Contributing
------------

Contributions, issues, and feature requests are welcome! Feel free to check out the [issues page](https://github.com/JS-GodMode/mapty/issues).

To contribute:

1.  Fork the repository.
2.  Create a new branch for your feature or bugfix.
3.  Submit a pull request explaining your changes.

License
-------

This project is licensed under the MIT License. See the LICENSE file for more details.

* * * * *

### Author

**Your Name**

-   GitHub: [Anonav0](https://github.com/Anonav0)
-   LinkedIn: [Swarnavo Khanra](https://in.linkedin.com/in/swarnavo-khanra)
