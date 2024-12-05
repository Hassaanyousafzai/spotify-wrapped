# Spotify Wrapped App

This project allows users to view their Spotify Wrapped data, including their top tracks over different time ranges (short, medium, and long term). The app uses the Spotify API and the `spotipy` Python library to fetch user-specific data. The collected data is then stored in a Google Sheet for easy access and analysis.

## Features

- **OAuth Authentication**: Allows users to sign in with their Spotify account securely.
- **Top Tracks**: Fetches users' top tracks for three different time ranges: short-term, medium-term, and long-term.
- **Spotify Data**: Retrieves track details, such as name, artist, album, and album cover.
- **Google Sheets Integration**: Saves the user's Spotify Wrapped data into a Google Sheet for easy access and sharing.

## Requirements

- Python 3.x
- `spotipy` library (for interacting with the Spotify API)
- `gspread` library (for interacting with Google Sheets)
- Google Sheets API access (for saving the data)

## Installation

### 1. Clone the repository
Replace it with the right repository link
    ```bash
    git clone https://github.com/your-username/spotify-wrapped-app.git
    cd spotify-wrapped-app

### 2. Install the necessary libraries
Install the required Python libraries using pip:
    ```bash
    pip install -r requirements.txt

### 4. Spotify API Credentials
Visit the [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/applications) to create a new app and get your `CLIENT_SERVER_ID` and `CLIENT_SECRET_ID`.
Set the `REDIRECT_URI` in your app settings to match the redirect URI in the code.

### 5. Google Sheets API Setup
Follow the instructions in the [Google Sheets API](https://gspread.readthedocs.io/en/latest/) documentation to set up a Google Sheets API project.
Download the `credentials.json` file and rename it to whatever you want.

Share the Google Sheet you want to use with the service account email provided by Google Sheets API.

### 6. Run the app
After setting up the credentials, you can run the app:
    ```bash
    python spotify_wrapped.py

This will fetch your top tracks for the `short_term`, `medium_term`, and `long_term` time ranges and save them to the specified Google Sheet.
