# 🎵 music-player-ui 🎵

This repo is a frontend task to build a **Music Player UI** using **React JS**. The interface matches the provided Figma design and includes various interactive features and animations.

## 🎨 Project Details

- **Design Link**: [🎨 Figma Design](https://www.figma.com/file/RtKhzEeeuD2FtRsg2dxSe
p/Front-end-Assessment?type=design&node-id=1-2&
mode=design&t=zEkwOdYyaeNx0z7m-4)
- **API Endpoint**: [🎧 Songs API](https://cms.samespace.com/items/songs)

> **Note**: The API returns different titles, artists, cover images, and durations, but the URL of every song is the same.

## ✨ Features

1. **Responsive Design**: 📱 The application is responsive. For smaller screens, the player component can be the main interface with a menu button to show a list of songs.
2. **REST API Integration**: 🔗 Loads list data from the API.
3. **Dynamic Images**: 🖼️ Fetches images based on the "cover" key from the API (e.g., `https://cms.samespace.com/assets/{COVER_IMAGE_ID}`).
4. **Persistent Music Playback**: 🎵 Music continues to play even if the user navigates to another tab.
5. **Dynamic Background**: 🌈 The background gradient color changes according to the cover image of the song.
6. **Fluid Interface**: 💧 Includes animations and transitions, such as list loading animations and background color change animations.
7. **Music Controls**: 🎚️ Features play/pause, next, and previous controls.
8. **Tab Change**: 🔄 Allows switching between tabs (e.g., "For You" to "Top Tracks").
9. **Search Functionality**: 🔍 Users can search for songs.
10. **Seeker Control**: ⏩ Allows controlling music via a seeker.

## 🚀 Hosting on GitHub

This project is hosted on GitHub.

## 🛠️ Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

### `npm run eject`

**Note**: This is a one-way operation. Once you `eject`, you can't go back!

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point, you're on your own.

## 📚 Learn More

To learn React, check out the [React documentation](https://reactjs.org/).