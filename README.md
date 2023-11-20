# Movie Trailer App

## Overview

This React application showcases a list of movie trailers, allowing users to filter movies based on language and genre. When a movie card is clicked, the corresponding trailer opens above the card. The project follows modular and reusable component-based architecture.

## Getting Started
Folder Structure
src
components
Header.js: Component for the application header.
FilterDropdown.js: Reusable dropdown component for filtering options.
Home.js: Main component containing the movie list and trailer functionality.
Trailer.js: Component to display the movie trailer.
App.css: Global styles for the app.
index.js: Entry point for the React application.
index.css: Global styles for the entire application.
home.css: Styles specific to the Home and other component.

Components
Header
The Header component displays the title, buttons for "Coming Soon" and "Now Showing," and dropdowns for filtering movies by popularity, language, and genre.

FilterDropdown
The FilterDropdown component is a reusable dropdown that accepts options and an onSelect callback. It is used in the Header component for language and genre filtering.

Home
The Home component is the main container that fetches movie data, renders the movie list, and handles trailer display logic. It utilizes the Header, FilterDropdown, and Trailer components.

Trailer
The Trailer component is responsible for displaying the movie trailer. It receives the trailer URL, position information, and a callback to close the trailer.

Features
Filtering: Filter movies by language and genre.
Trailer Display: Click on a movie card to view its trailer.
Modular Components: The application is built with reusable and modular components.
Responsive Styling: The CSS is structured to provide a responsive and visually appealing layout.
