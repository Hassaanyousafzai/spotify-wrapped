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

    ```bash
    git clone https://github.com/your-username/spotify-wrapped-app.git
    cd spotify-wrapped-app

### 2. Install the necessary libraries
Install the required Python libraries using pip:

    ```bash
    pip install -r requirements.txt
