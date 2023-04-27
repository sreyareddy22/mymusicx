Music Search and Playlist Web App
This web application allows users to search for music and create custom playlists. The app is similar to Spotify but uses the Music API to retrieve music data. Additionally, users must authenticate using Keycloak before being able to access the app's features.

Getting Started
To use this app, you will need the following:

A compatible web browser (Chrome, Firefox, Safari, or Edge)
An internet connection
A Keycloak account to authenticate
An API key for the Music API
Installing
Clone the repository to your local machine.
Install the required dependencies using npm install.
bash
Copy code
npm install
Create a .env file in the root directory of the project with the following variables:
bash
Copy code
REACT_APP_API_KEY=<your_music_api_key>
REACT_APP_AUTH_URL=<your_keycloak_auth_url>
Start the application using npm start.
bash
Copy code
npm start
Open your web browser and navigate to http://localhost:3000.
Usage
Authenticate with Keycloak using your credentials.
Search for music using the search bar.
Click on a song to add it to your playlist.
View your playlist by clicking on the "Playlist" button in the top right corner.
Remove songs from your playlist by clicking the "Remove" button next to the song name.
Add songs to your favorites by clicking on the heart icon next to the song name.
Built With
React - The web framework used
Axios - The HTTP client used for API requests
Keycloak - The authentication provider used
Music API - The music API used for retrieving music data
