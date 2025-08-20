# Project-95

Project-95 is a lightweight, browser-based project built entirely with **HTML** (and supporting static assets).  
It showcases a mix of creative web experiments, including a simple interactive game and themed mockups of popular platforms.

---

## Project Structure

```
Project-95/
├── assets/          # Supporting assets (images, CSS, JS, etc.)
├── index.html       # Main landing page
├── flappy.html      # Flappy Bird–style game
├── facebook.html    # Facebook-inspired page
├── insta.html       # Instagram-inspired page
└── reddit.html      # Reddit-inspired page
```

---

## Branches

```
Project-95/
├── main             # main branch
├── Social           # Added social media clones and portfolios
└── Features         # Added snake game and other features
```

---

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/stha-prasun/Project-95.git
   cd Project-95
   ```

2. **Open in Browser**
   - Launch `index.html` in your preferred browser.
   - Alternatively, right-click the file and select **Open With → Browser**.

No additional setup or dependencies are required.

---

## Features

- **Static & Lightweight** – Works in any modern browser with no installation needed.  
- **Interactive Game** – A Flappy Bird–inspired mini-game (`flappy.html`).  
- **UI Mockups** – Facebook, Instagram, and Reddit–themed demo pages.  
- **Portfolio-Ready** – `index.html` can serve as a simple landing or showcase page.  

---

## Usage

- Open `index.html` → Entry point / home page  
- Open `flappy.html` → Play the mini-game  
- Open `facebook.html`, `insta.html`, `reddit.html` → Explore themed mockups  

---

## Applications Instructions

### Flappy Bird Game  
**Introduction**  
Flappy Bird is a side-scrolling arcade-style game where players control a bird attempting to fly between vertical pipe obstacles without colliding. Our implementation faithfully recreates the addictive gameplay of the original with Windows 95 styling.  

**Game Instructions:**  
1. **Objective:** Guide the bird through gaps between pipes without touching them.  
2. **Controls:**  
   - **Desktop:** Press SPACEBAR to make the bird flap upward.  
   - **Mobile:** Tap anywhere on the screen to make the bird flap upward.  
3. **Scoring:**  
   - +1 point for each successfully passed pipe.  
   - Game ends if the bird hits a pipe or the ground.  
4. **Game Mechanics:**  
   - Gravity continuously pulls the bird downward.  
   - Each flap provides upward momentum.  
   - Pipe gaps are randomly generated for variety.  
5. **Restarting:** Click/tap anywhere after game over to play again.  

---

### Snake Game  
**Introduction**  
Snake is a classic arcade game where players control a growing snake that must consume food while avoiding collisions with walls and itself. Our implementation features responsive design and progressive difficulty.  

**Game Instructions:**  
1. **Objective:** Control the snake to eat food and grow as long as possible.  
2. **Controls:**  
   - Use Arrow Keys or WASD to change direction.  
   - **Desktop:** Keyboard controls only.  
   - **Mobile:** On-screen directional buttons.  
   - Space bar to pause/resume the game.  
3. **Game Mechanics:**  
   - Snake continuously moves in the current direction.  
   - Each food item increases length and score.  
   - Game ends if snake hits wall or itself.  
4. **Additional Features:**  
   - Pause/Resume: Press P/space key.  
   - Restart: Press R key.  
   - Adjustable speed settings (Slow to Insane).  

---

### Cortana Chatbot  
**Introduction**  
Cortana is a simple conversational agent modelled after Microsoft's digital assistant. It provides responsive interaction within the Windows 95 environment.  

**Usage Instructions:**  
1. **Accessing Cortana:**  
   - Click the Start Menu.  
   - Select "Cortana" from the menu options.  
2. **Interaction:**  
   - Type messages in the input field at the bottom.  
   - Click "Send" to submit your message.  
   - Cortana will respond with pre-programmed replies.  
3. **Features:**  
   - Conversation history maintained during session.  
   - Scrollable message window.  
   - Classic Win95 dialog styling.  

---

### Camera & Gallery Application  
**Introduction**  
The Camera and Gallery applications provide webcam capture functionality with local image storage, mimicking a basic digital camera experience within the Windows 95 environment.  

**Camera Instructions:**  
1. **Accessing Camera:**  
   - Click the Camera icon on the desktop.  
   - Grant browser permissions when prompted.  
2. **Capturing Photos:**  
   - Position yourself within the camera view.  
   - Click "Capture" to take a photo.  
   - Images are automatically saved to local storage.  

**Gallery Instructions:**  
- Click on Gallery icon to view the captured photos.  

**Management:**  
- Photos persist between sessions using browser storage.  
- No deletion functionality in current implementation.  

## Roadmap / Future Improvements

- Add responsive CSS for better mobile support  
- Enhance game logic and scoring in `flappy.html`  
- Apply consistent styling across all pages  
- Optionally deploy via GitHub Pages for easy sharing  

---

## Contributing

Contributions are welcome!  

1. Fork the repo  
2. Create a new branch (`feature/your-feature`)  
3. Commit changes and push  
4. Open a Pull Request  

---

## Authors

**[Prasun Shrestha](https://github.com/stha-prasun)**
**[Pramish Devkota](https://github.com/101rohan)**
**[Rohan Shrestha](https://github.com/PramishDevkota)**
**[Shreejan Shrestha](https://github.com/Shreejan2000s)**
