# Spotify Clone

Spotify Clone is a front-end music streaming UI just like Spotify. It features interactive song cards, a custom audio player, and a live search feature using the iTunes API to fetch and stream 30-second previews.  
This is a front-end-only project, built for learning and portfolio showcasing. It does not include any backend functionality or real-time integration with Spotify or Apple Music.

## Features

- Live music search using the iTunes API  
- Dynamic cards for Trending Songs and Best English Songs  
- Custom audio player with play/pause, progress bar, volume control, and mute toggle  
- Hamburger menu for mobile-friendly navigation
- Horizontal scroll for song sections with scroll buttons  
- Clickable artist names and song thumbnails  
- Built using pure HTML, CSS, and JavaScript (no frameworks)

## Project Structure

.
├── index.html              # Main HTML layout  
├── style.css               # Styling and responsive design  
├── script.js               # JavaScript logic, DOM handling, iTunes API calls  
└── README.md               # This documentation file

## How to Run

1. Clone the repository:  
   `git clone https://github.com/saurabhrai7/spotify-clone.git`

2. Navigate to the project folder:  
   `cd spotify-clone`

3. Open the project:  
   - Open `index.html` directly in any browser  
   - Or use Live Server in Visual Studio Code for the best experience

## API Used

**iTunes Search API**  
Endpoint: `https://itunes.apple.com/search?term={query}&entity=song&limit=10`  
- No API key required  
- Returns metadata along with a 30-second `previewUrl` for each track

## Tech Stack

- HTML5  
- CSS3  
- Vanilla JavaScript  
- Font Awesome (for icons)  
- iTunes API (for search and audio preview)

## Limitations

- Only 30-second previews are available (iTunes limitation)  
- CORS errors may occur depending on the browser and environment — use a proxy in production  
- No backend features like playlists, likes, or user login
- Not Responsive

## Author

**Saurabh Rai**  
BCA Student | Frontend Developer  

## License

This project is licensed under the MIT License.
