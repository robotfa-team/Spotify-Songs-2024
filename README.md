# Spotify Songs 2024

## Overview
This dataset presents a comprehensive compilation of the most streamed songs on Spotify in 2024. It provides extensive insights into each track's attributes, popularity, and presence on various music platforms, offering a valuable resource for music analysts, enthusiasts, and industry professionals. The dataset includes information such as track name, artist, release date, ISRC, streaming statistics, and presence on platforms like YouTube, TikTok, and more.

---

## Key Features

- **Track Name**: Name of the song.
- **Album Name**: Name of the album the song belongs to.
- **Artist**: Name of the artist(s) of the song.
- **Release Date**: Date when the song was released.
- **ISRC**: International Standard Recording Code for the song.
- **All Time Rank**: Ranking of the song based on its all-time popularity.
- **Track Score**: Score assigned to the track based on various factors.
- **Spotify Streams**: Total number of streams on Spotify.
- **Spotify Playlist Count**: Number of Spotify playlists the song is included in.
- **Spotify Playlist Reach**: Reach of the song across Spotify playlists.
- **Spotify Popularity**: Popularity score of the song on Spotify.

---

## How to Access the Dataset

### Prerequisites
- A RapidAPI account
- An API token (available through RapidAPI)

### Steps to Get Started

1. **Sign Up on RapidAPI**
   - Visit [RapidAPI](https://rapidapi.com/robotfa-robotfa-default/api/spotify-songs-2024) and create an account if you don’t already have one.

2. **Subscribe to the API**
   - Search for the "Spotify Songs 2024" API and subscribe to it.

3. **Get Your API Token**
   - After subscribing, navigate to the API's "Endpoints" section and copy your unique API token.

4. **Integrate the API**
   - Use the token to authenticate your requests. Here’s a basic example in cURL:
     ```bash
     curl -X GET "https://spotify-songs-2024.p.rapidapi.com/list" \
     -H "X-RapidAPI-Key: YOUR_API_KEY" \
     -H "X-RapidAPI-Host: spotify-songs-2024.p.rapidapi.com"
     ```

---

## Example Endpoints

### 1. Get Song Details
Retrieve detailed information about a specific song:
```bash
GET /list
```


---

## Contribution
If you have suggestions or would like to contribute to this project, feel free to open an issue or submit a pull request.

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

