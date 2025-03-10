# 🎵 Music Player Web Application

This is a **dynamic music player web application** built using **HTML, CSS, and JavaScript**. It allows users to play, pause, shuffle, and control music tracks from a predefined playlist. It also supports features like progress bars, volume control, and song lists.

---

## 📜 Features

### ✅ Play / Pause Music
- You can easily play and pause the music by clicking on the **play/pause button**.
- When music plays, the album image rotates, and a wave animation appears.

### ✅ Next / Previous Song
- Click **Next** to play the next song in the playlist.
- Click **Previous** to go back to the previous song.

### ✅ Shuffle / Repeat Mode
- The player has three modes:
    - **Repeat:** It will repeat the playlist.
    - **Repeat One:** It will keep playing the current song.
    - **Shuffle:** It will play songs randomly.

### ✅ Progress Bar
- The progress bar dynamically updates according to the current song's duration.
- You can also drag the progress bar to seek through the song.

### ✅ Volume Control
- You can increase or decrease the volume using the volume slider.
- There is also a **Mute** option to mute the audio.

### ✅ Song List (Dynamic Playlist)
- The playlist is dynamically generated from the `allMusic` array in the `script.js` file.
- Clicking on any song in the list will play that song.

### ✅ Song Duration
- It shows the **current duration** and **total duration** of the song.

### ✅ Auto Play Next Song
- When the current song ends, the next song automatically starts playing.

---

## 📁 Folder Structure

```
Music-Player-Project
│
├── 📁 images     --> Contains album cover images
├── 📁 songs      --> Contains audio files (.mp3)
├── index.html    --> Main HTML File
├── style.css     --> Styling for the player
├── script.js     --> Main JavaScript File
└── README.md     --> Project Documentation (this file)
```

---

## 🚀 How to Run the Project

1. **Download the project** or clone it using:
```bash
git clone https://github.com/mihraravi/SongWay/
```

2. Navigate to the project folder:
```bash
cd Music-Player-Project
```

3. Open the `index.html` file in any browser.

4. Enjoy the music! 🎶

---

## 📌 How to Add More Songs

If you want to add more songs to the playlist:

1. Go to the **script.js** file.
2. Find the `allMusic` array.
3. Add a new song in this format:
```js
{
    name: "Song Name",
    artist: "Artist Name",
    img: "music-10",
    src: "music-10"
}
```
4. Add the respective image in the `/images` folder.
5. Add the respective audio file in the `/songs` folder.
6. Refresh your browser to see the new song in the playlist.

---

## 💎 Future Enhancements

Here are some features you can implement in the future:

1. **Favorites Playlist** - Allow users to mark songs as favorites.
2. **Lyrics Display** - Display song lyrics in real-time.
3. **Download Option** - Allow users to download songs.
4. **Online Music API** - Fetch songs from an online API instead of manually adding files.

---

## 💻 Technologies Used

- **HTML5** - Structure of the application
- **CSS3** - Styling and animations
- **JavaScript (Vanilla JS)** - Core functionality of the music player

---

## 🎉 Credits

- **Music Player Created By:** [Ravi Prakash Mishra]
- **GitHub Repository:** [https://github.com/mihraravi/SongWay/]
- **Inspiration:** Open-source music player projects

---
Enjoy listening to mine favorite music! 🎶🥳


