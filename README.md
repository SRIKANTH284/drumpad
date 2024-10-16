

# Drum Pad Project 🎶

A fun and interactive **Drum Pad** built using **HTML**, **CSS**, and **JavaScript**. This project allows users to play different drum sounds by pressing corresponding keys on their keyboard or clicking the buttons on the screen.

## Demo
[Link to Live Demo](https://srikanth284.github.io/drumpad/)   

## Features

- **Responsive Design**: Works on desktop and mobile devices.
- **Interactive Buttons**: Drum pads highlight when pressed, either via the keyboard or mouse click.
- **Audio Playback**: Each pad plays a unique sound using the freeCodeCamp drum sounds collection.
- **Recording Display**: Displays the last sound played on the screen.
- **Smooth Animations**: Drum pads scale down when pressed and reset after a short delay.

## Technologies Used

- **JavaScript (ES6)**: Used for handling events and controlling audio playback.
- **HTML & CSS**: For structuring and styling the app. Includes responsive design to make the app work on multiple screen sizes.
- **Font Awesome**: For the GitHub icon.

## How to Use

1. Open the application.
2. You can either:
   - **Click on the drum pads** using your mouse to play the sound.
   - **Press the corresponding keys** on your keyboard (Q, W, E, A, S, D, Z, X, C) to play the sound.
3. The name of the sound you played will be displayed in the "Drum Machine" display section.

## Key Bindings

Each key corresponds to a specific drum sound:

| Key | Sound ID        |
| --- | --------------- |
| Q   | Heater-1        |
| W   | Heater-2        |
| E   | Heater-3        |
| A   | Heater-4        |
| S   | Clap            |
| D   | Open-HH         |
| Z   | Kick-n'-Hat     |
| X   | Kick            |
| C   | Closed-HH       |

## Setup and Installation

1. Clone the repository:
   ```
   git clone https://github.com/SRIKANTH284/drumpad.git
   ```
2. Navigate into the project directory:
   ```
   cd drum-pad
   ```
3. Open the `index.html` file directly in your browser or use a live server:
   ```
   live-server
   ```

## Project Structure

```
/drum-pad
│
├── index.html         # Entry point of the project
├── index.js           # Contains the core JavaScript for audio control and interactions
├── styles.css         # Styling for the drum pad application
├── styles.scss.map    # Map file for styles
└── README.md          # Project documentation
```

## Future Enhancements

- **Add Volume Control**: Allow users to adjust the volume of the drum sounds.
- **Recording Functionality**: Enable users to record and playback their drum beats.
- **Custom Sounds**: Let users upload their own sounds for each pad.



- Drum sounds sourced from [freeCodeCamp](https://www.freecodecamp.org/).
- Background image from [Wallpapersafari](https://cdn.wallpapersafari.com/0/82/bCVUo4.jpg).

