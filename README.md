# Movie Collection Manager

A modern web application for managing and organizing your movie collection. Built with vanilla JavaScript, HTML, and CSS.

## Features

- 📽️ View and manage your movie collection
- 🔍 Real-time search functionality
- 📊 Sort movies by year, rating, or title
- ✏️ Add and edit movie entries
- ⭐ Star rating system
- 🎭 Cast member management
- 🖼️ Movie poster support

## Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- Basic understanding of HTML, CSS, and JavaScript

### Installation

1. Clone or download the repository
2. Ensure you have all required files:
   - `index.html`
   - `style.css`
   - `script.js`
   - Image files in an `img` folder
3. Open `index.html` in your browser

## Usage Guide

### Viewing Movies

The application automatically displays all movies on page load. Each movie card includes:

- Movie poster image
- Title
- Year and runtime
- Plot summary
- Cast members
- Star rating
- Edit button

### Searching Movies

- Type in the search bar at the top
- The list filters in real-time to show only matching titles

### Sorting Movies

Use the sort dropdown menu to organize movies by:

- Year (ascending)
- Rating (descending)
- Title (alphabetical)

### Adding a New Movie

1. Click the "Add new Movie" button
2. Fill out the form with:
   - Movie title
   - Year
   - Runtime (minutes)
   - Rating (0-10)
   - Plot summary
   - Cast members (at least one required)
   - Movie poster image (optional)
3. Click "Add Movie" to submit

### Editing a Movie

1. Click the "Edit" button on any movie card
2. Modify the information in the form
3. Click "Update Movie" to save changes

## Technical Implementation

### Key Functions

- `renderMovies()`: Displays all movies in the UI
- `renderMovieCard()`: Creates HTML for a single movie card
- `generateStarRating()`: Converts numeric rating to star display
- `handleNewMovieSubmit()`: Processes new movie form
- `handleUpdateMovie()`: Processes movie edit form
- `searchMovieByTitle()`: Filters movies based on search input
- `sortMoviesByYear()`: Sorts movies chronologically

### Event Handling

The application uses event delegation for efficient handling of:

- Form submissions
- Button clicks
- Search input
- Sort selection
- Modal interactions

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is open source and available under the MIT License.
