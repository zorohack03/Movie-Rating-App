## Movie Rating App

This is a ReactJS-based movie rating application that allows users to search for movies, view detailed information ,add movies to mylist. The app leverages the OMDB API to fetch movie data and provides a seamless user experience with an intuitive interface.

### Features

1. **Search for Movies**:
   - Users can search for movies using the search bar in the navigation bar.
   - The app fetches movie data from the OMDB API and displays search results in a grid format.

2. **Movie List Display**:
   - The search results are displayed as a list of movie cards, showing the movie poster, title, and year of release.
   - Clicking on a movie card navigates to the detailed view of the selected movie.

3. **Movie Details View**:
   - Detailed information about the selected movie, including the poster, title, year, rating, release date, runtime, genre, director, writer, actors, plot, language, country, awards, metascore, IMDb rating, and IMDb votes.
  

4. **User Authentication**:
   - A simple login page for user authentication.
  
5. **My Movie List Display**:
   - Users can add their liked movies in my movie list .
   - Users can also remove movies from my movie list.

6. **Comment Section**:
   - Users can comment any movie in a anonymous manner(Username won't be displayed).

### File Structure

- **`App.js`**: Main component that sets up routing and state management.
- **`NavBar.js`**: Navigation bar with links to Home, My List, and Login pages, including a search bar.
- **`SearchBox.js`**: Component for the search bar used in the navigation bar.
- **`MovieList.js`**: Component to display a list of movies based on the search query.
- **`MovieDetails.js`**: Component to display detailed information about a selected movie.
- **`Login.js`**: Component for user login.
- **`MyList.js`**: Component to display and manage the user's personal movie list.
- **`MovieListContext.js`**: Context to manage the global state of the movie list.
- **CSS File**: Styling for various components (`App.css`).

### Getting Started

1. **Clone the repository**:
   ```sh
   git clone https://github.com/yourusername/movieratingapp.git
   cd movieratingapp

2. **Install dependencies:**:
   ```sh
   npm install -g npm@10.7.0
   npm fund
3. **Run the app:**:
   ```sh
   npm start

4. **Open your browser:**:
   ```sh
   http://localhost:3000

## Dependencies

- React
- React Router DOM
- OMDB API

## Usage

- Search for movies using the search bar.
- Click on a movie to view its details.
- Login using the login page.
- Add movies to mylist.
- Comment any movies .


## Acknowledgments

- OMDB API for providing the movie data.
