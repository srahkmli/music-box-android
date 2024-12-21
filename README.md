# MusicPlayer

MusicPlayer is a music player application with an interactive user interface, designed for easy access and control over your music collection. The app allows users to play MP3 songs, create playlists, and manage music in various ways. With intuitive features like searching and adding songs to playlists, it ensures a seamless music experience.

## Key Features

- **Fetch MP3 Songs from Local Storage**: The app can retrieve and display all MP3 songs stored locally on your device.
- **Favourites Playlist**: Users can create a permanent playlist of their favorite songs. The playlist will remain intact until the user manually deletes songs.
- **Temporary Playlist**: Users can add songs to the currently playing list temporarily, allowing for easy music queue management.
- **Search Functionality**: The app provides a powerful search feature to quickly find songs by title, artist, or album.
- **Interactive UI**: The app includes an intuitive user interface for easy song control, such as play, pause, skip, and volume adjustments.

## Technologies Used

The application’s core functionality and features are built with the help of:

- **Navigation Drawer**: For easy navigation between different sections of the app.
- **Fragments**: To manage different views and display the content dynamically.
- **ViewPager**: To implement swipeable pages for a smooth navigation experience.
- **SQLite Database**: For storing and managing user data, including playlists and song information.
- **Adapters**: Used to bind data between the app's UI and underlying data structures.

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/srahkmli/musicplayer.git
   ```

2. Open the project in Android Studio (or your preferred IDE).
3. Build and run the application on your device or emulator.

## Usage

- **View Songs**: Navigate to the "Songs" section to view all MP3 files fetched from local storage.
- **Create Favourites Playlist**: Add songs to your favourites playlist for easy access.
- **Search Songs**: Use the search bar to quickly find songs by name.
- **Control Playback**: Play, pause, skip, or adjust volume directly from the interactive UI.

## Contributing

Feel free to fork the repository, open issues, and submit pull requests to contribute to the project!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
