# Music Downloader

A Python script that enables you to download music from YouTube directly to your local machine. It provides a simple and efficient way to save your favorite tracks for offline use.

> [!NOTE]  
> This project is intended solely for **development and experimentation**. It is not meant to promote or endorse unauthorized music downloading or any other form of copyright infringement.

## Features

- **Search YouTube for Songs**: Automatically fetches the first video URL based on your search query using `yt_dlp`.
- **Audio Extraction**: Downloads the audio from YouTube videos in high-quality MP3 format.
- **Customizable Output**: Saves the downloaded songs in a specified directory with a user-friendly naming convention.
- **FFmpeg Integration**: Utilizes FFmpeg for audio extraction and conversion to ensure high-quality results.
- **Performance Tracking**: Measures and displays the time taken to download and process each song.

## Usage

To get started with the Music Downloader, follow these steps:

### Clone the Repository:
1. Clone the GitHub repository:
    ```bash
    git clone https://github.com/legelff/musicDownloader.git
    ```
2. Navigate to the project directory:
    ```bash
    cd musicDownloader
    ```

### Setup Songs Directory

1. Create a folder named `songs` in the `musicDownloader` directory. This folder will be used to store all the downloaded songs.
    ```bash
    mkdir songs
    ```
2. (optional) Ensure that the script has the necessary permissions to write files to the `songs` directory.

## Open and Run the Script

1. Open the `musicDownloader.ipynb` file in your preferred Jupyter Notebook environment.
2. Run the first cell to import all the necessary libraries and dependencies.
3. Whenever you want to download a song, simply run the main script cell. Follow the prompts to search for and download your desired track.

## Contact

If you have any questions, suggestions, or just want to have a chat, feel free to reach out:

- Email: business@l145.be
- LinkedIn: [Aryan Shah](https://www.linkedin.com/in/aryan-shah-l145)
- GitHub: [legelff](https://github.com/legelff)