# Beatify

Beatify is a responsive front-end music streaming UI inspired by Spotify. It features interactive song cards, a custom audio player, and a live search powered by the iTunes API to fetch and play 30-second previews.

This is a frontend-only clone, made for learning and portfolio purposes. No backend or real-time music streaming services like Spotify are used.

## Features

- Live music search using iTunes API
- Dynamic cards for Trending Songs and Best English Songs
- Custom audio player with play, pause, progress bar, volume control
- Responsive design with mobile navigation
- Horizontal scroll for song sections
- Clickable artist names and thumbnails
- Modern UI using pure HTML, CSS, and JavaScript

## Project Structure

.
├── index.html              # Main layout
├── style.css               # Styling and responsiveness
├── script.js               # JavaScript logic and iTunes API calls
├── requiredMedia/          # Local thumbnails and images
└── README.md               # This file

## How to Run

1. Clone the repository:
   git clone https://github.com/YOUR_USERNAME/beatify.git

2. Open the project folder:
   cd beatify

3. Run the project:
   - Open index.html in any browser
   - OR use Live Server in VS Code

## API Used

iTunes Search API  
Endpoint: https://itunes.apple.com/search?term={query}&entity=song&limit=10  
- No API key required  
- Returns track metadata and previewUrl for 30-second playback

## Tech Stack

- HTML5
- CSS3
- JavaScript (Vanilla)
- Font Awesome for icons
- iTunes API for data and previews

## Limitations

- Only 30-second previews are available via iTunes
- CORS errors may occur depending on browser and environment
- No backend functionality (no playlists, likes, or accounts)

## Author

Yashwant Kumar Rai  
BCA Student | Frontend Developer  
GitHub: https://github.com/YOUR_USERNAME

## License

This project is licensed under the MIT License.
