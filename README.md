<div align="center">
 <img src="./logo.jpg" alt="Logo" width="120" height="120">
  <h1 align="center">🎶 Universal Song Player & Lyrics Finder 🎶</h1>
  <p align="center">
    Your personal gateway to the world of music.
    <br />
    <a href="https://github.com/codedbyaditi/My-Youtube-"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/codedbyaditi/My-Youtube-/issues">Report Bug</a>
    ·
    <a href="https://github.com/codedbyaditi/My-Youtube-/issues">Request Feature</a>
  </p>
</div>

## About The Project

This project is a simple yet powerful tool for all music lovers. It provides a clean graphical interface to search for any song, play it instantly on YouTube, and get its lyrics in English, all in one place.

### Features

-   **Instant Search & Play**: Find any song on YouTube and play it with a single click.
-   **Lyrics on Demand**: Get English lyrics for the songs you play, powered by Genius.
-   **Sleek UI**: A modern and creative user interface built with Tkinter.

## Getting Started

Follow these simple steps to get the application up and running on your local machine.

### Prerequisites

-   Python 3.8 or higher
-   A [Genius API Token](#genius-api-token-for-lyrics) for fetching lyrics.

### Installation

1.  **Clone the repository**
    ```sh
    git clone https://github.com/codedbyaditi/My-Youtube-.git
    cd My-Youtube-
    ```
2.  **Create and activate a virtual environment**
    ```powershell
    python -m venv .venv
    .\.venv\Scripts\Activate.ps1
    ```
3.  **Install the required packages**
    ```sh
    pip install -r requirements.txt
    ```

### Genius API Token (for lyrics)

To fetch lyrics, you need an API token from Genius.

1.  Create an account at [genius.com](https://genius.com) if you don't have one.
2.  Go to the [API Clients page](https://genius.com/api-clients) and create a new API client.
3.  Generate an "Access Token" and copy it.

Set the token as an environment variable in PowerShell:

```powershell
$env:GENIUS_API_TOKEN = "YOUR_TOKEN_HERE"
```

To set it permanently, you can use:

```powershell
[Environment]::SetEnvironmentVariable('GENIUS_API_TOKEN', 'YOUR_TOKEN_HERE', 'User')
```

## Usage

Run the application with the following command:

```powershell
python search_and_play.py
```

Enter a song name (e.g., "Tum Hi Ho Arijit Singh") and click "Search & Play". The song will open in your browser, and the lyrics will be displayed in the app.

## Troubleshooting

-   **No Lyrics?**: Ensure your `GENIUS_API_TOKEN` is set correctly and `lyricsgenius` is installed.
-   **Song Not Found?**: The YouTube scraping might have failed. Try a different search query.
-   **Audio Issues?**: For in-app audio, make sure `python-vlc` is installed and VLC is available on your system.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Project Link: [https://github.com/codedbyaditi/My-Youtube-](https://github.com/codedbyaditi/My-Youtube-)
