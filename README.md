# Music-player
# 🎼 Neon Music Player 🎧

A sleek and stylish **Music Player Web App** with a futuristic neon UI, smooth animations, and essential music playback controls. Built entirely with **HTML, CSS, and JavaScript**, this music player is lightweight, responsive, and works offline!

![Screenshot (107)](https://github.com/user-attachments/assets/be53545d-b93e-4adb-93d8-b6c21671a05b)
![Screenshot (108)](https://github.com/user-attachments/assets/ae837516-f5a4-42a6-8994-71a62dde5302)

---

## ✨ Features

### ✅ Playback Controls
- Play / Pause
- Next / Previous
- Auto Play Next Track
- Loop / Shuffle (optional toggle)

### 🎨 User Interface
- Animated album art rotation
- Neon glowing buttons and dynamic background
- Responsive layout (mobile and desktop)
- Displays:
  - 🎵 Track Title
  - 🎤 Artist Name
  - 🕒 Duration and Time Left

### 📂 Playlist Support
- Playlist array (in JavaScript)
- Easily add/remove songs
- Supports local `.mp3` audio

---

## 🧰 Tech Stack

| Layer     | Technology Used         |
|-----------|--------------------------|
| Markup    | HTML5                    |
| Styling   | CSS3 (Flexbox, Animation)|
| Logic     | Vanilla JavaScript       |
| Audio API | HTML5 `<audio>` element  |

---

## 📁 Project Structure

```plaintext
📦 music-player/
├── index.html              # Main structure
├── style.css               # Visual styling and neon theme
├── script.js               # Functional logic for the player
├── music/                  # Folder for .mp3 files
│   ├── song1.mp3
│   └── song2.mp3
├── images/                 # Album artwork or icons
│   └── screenshot.png
└── README.md               # Documentation
🖥️ How to Use
Clone this repo
git clone https://github.com/your-username/music-player.git
Open in browser
Just open index.html in any modern browser.

Customize your playlist
Open script.js and modify the playlist array:
javascript
let playlist = [
  {
    title: "Song Name",
    artist: "Artist",
    file: "music/song1.mp3",
    cover: "images/art1.jpg"
  }
];
🛠️ Customization Tips
🎨 Change theme: Edit style.css for your own colors

🎵 Add your own songs: Place .mp3 files in the music/ folder

🎧 Add autoplay or loop: Use HTML5 <audio> attributes in JS

📌 Roadmap
 Volume control slider

 Upload local files via drag-and-drop

 Create playlists with localStorage

 Integrate lyrics API or Spotify metadata

🧑‍💻 Author
Developed by  V Dharani


📫 For feedback or contributions, feel free to open an issue or PR!

📄 License
This project is licensed under the MIT License.
