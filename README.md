# MusicSphere 🎶 - Online Music Library

MusicSphere is a Spotify-inspired online music library that allows users to browse and filter songs by language. It features an interactive UI with YouTube video integration for seamless music playback.

## 📌 Features
- 🎵 **Multi-Language Support:** Filter songs by Hindi, English, Tamil, Telugu, and Punjabi.
- 🎬 **YouTube Integration:** Embedded video player for instant playback.
- 💡 **Dynamic Filtering:** Load songs from an XML file and filter them dynamically.
- 🎨 **Modern UI:** A sleek, dark-themed design inspired by Spotify.

## 🚀 Technologies Used
- **HTML, CSS, JavaScript** for front-end development.
- **XML** for storing song data.
- **YouTube Embed URL** for video playback.

## 📂 File Structure
```
MusicSphere/
│── index.html         # Main webpage, includes CSS and JS
│── songs.xml          # XML file containing song data
│── README.md          # Documentation
```

## 🎥 XML File Structure (songs.xml)
```xml
<MusicLibrary>
    <Language name="Hindi">
        <Song>
            <VideoURL>https://www.youtube.com/embed/0zFoHrvbRu4?si=tlL41-0Ynuh3ougS</VideoURL>
            <SongName>Dhaakad</SongName>
            <Movie><Dangal</Movie>
            <Actor>Aamir Khan</Actor>
            <Actress>Sanya Malhotra, Fatima Sana Shaikh</Actress>
            <Singer>Raftaar</Singer>
            <Lyricist>Amitabh Bhattacharya</Lyricist>
            <Year>2016</Year>
            <Ratings>4.8</Ratings>
        </Song>
    </Language>
</MusicLibrary>
```

## 📜 How to Run
1. Clone this repository:
   ```sh
   git clone https://github.com/Vidhi-bhutia/MusicSphere.git
   ```
2. Open `index.html` in your browser.
3. Enjoy browsing and listening to songs! 🎶

## 🛠️ Future Enhancements
- 🎚️ **Search Functionality** to find songs quickly.
- 📱 **Mobile Responsiveness** for a better experience on all devices.
- 🌐 **Database Integration** to store and fetch song data dynamically.

## 📌 Credits
Developed by **Vidhi Bhutia** 🎵✨
