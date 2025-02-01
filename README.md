  # Weather Dashboard

  This project is a weather dashboard built with React.js. It fetches real-time weather data from the OpenWeatherMap API and updates every 30 seconds.

  ## Setup

  1. Clone the repository.
  2. Run `npm install` to install dependencies.
  3. Create a `.env` file and add your OpenWeatherMap API key.
  4. Run `npm start` to start the development server.

  ## Features

  - Search for a city and view current weather details.
  - Automatic data refresh every 30 seconds.
  - Error handling for network issues and invalid city names.
  - Local storage to remember the last searched city.
  - Optional 5-day forecast and temperature unit toggle.

  ## Approach

  The project uses React functional components and hooks for state management and side effects. The Context API is used for global state management, and styled-components are used for styling.
