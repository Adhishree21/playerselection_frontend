# 🎮 Card Dealing Interface

A smooth, animated card dealing simulator built with pure HTML, CSS, and JavaScript. Watch cards being dealt from a central deck to players positioned around a virtual casino table with realistic animations and visual effects.



## ✨ Features

- **🎯 Interactive Setup**: Choose 2-6 players with an intuitive interface
- **🎪 Smooth Animations**: Realistic card dealing with rotation and scaling effects
- **🎨 Casino Aesthetics**: Green felt table design with gold accents
- **📱 Responsive Design**: Works seamlessly on desktop and mobile devices
- **⚡ Real-time Feedback**: Progress bars, player highlighting, and status updates
- **🔄 Game Controls**: Reset and deal again functionality
- **🎲 Pure Frontend**: No backend required - runs entirely in the browser



## 🛠️ Installation & Usage

### Quick Start
1. Clone the repository:
   ```bash
   git clone https://github.com/Adhishree21/playerselection_frontend.git
   ```

2. Navigate to the project directory:
   ```bash
   cd playerselection_frontend
   ```

3. Open `index.html` in your web browser:
   ```bash
   
   
   # On Windows
   start index.html
   
   

### Or Run with Live Server
If you have VS Code with Live Server extension:
1. Right-click on `index.html`
2. Select "Open with Live Server"

## 🎮 How to Use

1. **Setup**: Select the number of players (2-6) from the dropdown
2. **Start Dealing**: Click the "Start Dealing" button to begin
3. **Watch Animation**: Cards are dealt one by one to each player with smooth animations
4. **Game Controls**: Use "New Game" to restart or "Deal Again" for another round

## 🏗️ Technical Architecture


### Core Technologies
- **HTML**: Semantic structure and layout
- **CSS**: Styling, animations, and responsive design
- **JavaScript**: Game logic and DOM manipulation

### Key Features Implementation

#### Animation System
- **CSS Keyframes**: Smooth card movement with rotation effects
- **Transform Properties**: Scale, rotate, and translate for realistic motion
- **Transition Timing**: Coordinated animations using `setTimeout()`

#### Responsive Design
- **Flexbox Layout**: Flexible positioning and alignment
- **Media Queries**: Mobile-optimized layouts
- **Viewport Units**: Scalable dimensions

#### Game State Management
- **Centralized State**: Single `gameState` object tracks all variables
- **Event-Driven**: User interactions trigger state changes
- **Dynamic DOM**: Real-time updates to player cards and progress


## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

### Ideas for Contributions
- [ ] Add sound effects for card dealing
- [ ] Implement different card deck designs
- [ ] Add player name customization
- [ ] Create different table themes
- [ ] Add card game rules integration


## 🙏 Acknowledgments

- Inspired by classic casino card games
- Card animations inspired by real-world dealing techniques
- Responsive design patterns from modern web development

⭐ **If you found this project helpful, please give it a star!** ⭐