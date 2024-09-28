# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

Spotify Clone using React

This project implements a simple yet functional music player using React's Context API and hooks like `useState`, `useEffect`, and `useRef`. It provides essential functionalities such as play, pause, track navigation, and seeking within a track. The music player uses a list of songs defined in the `songsData` array and supports a seamless user experience by managing state globally through context.

### Features

- **Play/Pause Control**: Users can play and pause the current track.
- **Track Navigation**: Users can switch to the next or previous track.
- **Seek Functionality**: Users can click on the progress bar to jump to a specific part of the song.
- **Dynamic Track Information**: Track duration and current time are dynamically updated and displayed as the song plays.
- **Global State Management**: The app uses React's `Context API` to manage and share music player state across components.

### Hooks and Refs Used

- **`useRef`**: For directly accessing DOM elements (audio element, progress bar).
- **`useState`**: For managing player state (play status, current track, track timing).
- **`useEffect`**: To set up event listeners for updating the seek bar and track timing during playback.

### Player Functions

- **`play()`**: Plays the current track and updates the play status.
- **`pause()`**: Pauses the current track and updates the play status.
- **`playwithId(id)`**: Plays a track selected by its ID.
- **`previous()`**: Switches to the previous track in the list.
- **`next()`**: Switches to the next track in the list.
- **`seekSong()`**: Allows seeking within a track by clicking on the progress bar.

### Installation and Usage

1. Clone the repository.
2. Install dependencies by running `npm install`.
3. Ensure the `songsData` array in `assets` contains your audio file data.
4. Start the application using `npm start`.

This component can be integrated into any React application where audio playback is required. The global context ensures easy state sharing between multiple components without prop drilling.

### Future Improvements

- Add shuffle and repeat functionalities.
- Improve the UI for the seek bar and controls.
- Implement a volume control feature.
- Implement a yt DL API extension which will help to play any song for your choice 

---

![spotify clone ](https://github.com/user-attachments/assets/175adf3b-8e22-4378-b9da-6aacbe0b96ef)


