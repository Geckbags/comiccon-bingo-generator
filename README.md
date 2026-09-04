# ComicCon Bingo Generator 🎮🎲

An interactive web-based bingo game generator featuring 84 iconic characters from comics, video games, and anime. Perfect for ComicCon events, gaming conventions, or character-themed parties!

## ✨ Features

### 🎨 Sheet Generator
- **Customizable Branding**: Upload event logos and sponsor images
- **Bulk Generation**: Create up to 200 unique bingo sheets at once
- **Print-Ready**: Optimized print layout (2 sheets per page)
- **Smart Image Loading**: Character images with fallback avatars
- **Export Functionality**: Save game data as JSON for tracking

### 🎯 Game Caller & Tracker
- **Live Game Management**: Call characters one by one with visual tracking
- **Master Board View**: See all 84 characters with called/uncalled status
- **Sheet Tracking**: Real-time leaderboard showing completion progress
- **Call History**: Keep track of the last 5 called characters
- **Import/Export**: Resume games by loading previously saved data

### 🦸 Character Library
Includes 84 beloved characters from:
- Marvel & DC Comics (Spider-Man, Batman, Superman, etc.)
- Video Games (Mario, Sonic, Link, Master Chief, etc.)
- Anime (Goku, Naruto, Luffy, Sailor Moon, etc.)
- Modern Gaming Icons (Among Us, Minecraft Steve, etc.)

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, or Edge)
- Node.js 20+ and npm (for GitHub Spark-style local/dev workflow)

### Run as a Project (GitHub Spark-style Workflow)

1. Install dependencies
   ```bash
   npm install
   ```

2. Start local dev server
   ```bash
   npm run dev
   ```

3. Build production files
   ```bash
   npm run build
   ```

The production build is output to `dist/`, which is configured for GitHub Pages deployment.

### Usage

1. **Open the Application**
   ```
   Simply open Bingo.html in your web browser
   ```

2. **Generate Bingo Sheets**
   - Navigate to "Sheet Generator" tab
   - (Optional) Upload event logo and sponsor images
   - Set the number of sheets to generate
   - Click "Generate Sheets"
   - Click "Print Sheets" or "Export Game Data"

3. **Host a Game**
   - Switch to "Game Caller & Tracker" tab
   - Upload your exported game data JSON (if you have one)
   - Click "Call Next Character" to randomly select characters
   - Track which sheets are closest to winning on the leaderboard

## 🎨 Customization

### Branding Options
- **Event Logo**: Displayed at the top center of each sheet
- **Center Free Space**: Custom image for the center square
- **Sponsor Logos**: Left and right header positions

### Character Images
- Click any character image to cycle through different image variations
- Automatic fallback to generated avatars if images fail to load

## 📄 Print Settings

For best results when printing:
- Use portrait orientation
- Set margins to default or minimal
- Enable background graphics/colors
- The layout automatically fits 2 sheets per page

## 🔧 Technical Details

- **Core App**: Pure HTML/JavaScript single-page app
- **Tailwind CSS**: Styling via CDN
- **Responsive Design**: Works on desktop, tablet, and mobile
- **Local Storage Ready**: All game state can be exported/imported
- **Project Build Support**: Vite-based scripts for `dev` and `build`
- **GitHub Deployment**: `.github/workflows/deploy-pages.yml` publishes `dist/` to GitHub Pages on pushes to `main`

## 📱 Browser Compatibility

- ✅ Chrome/Edge (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Opera

## 🎯 Use Cases

- ComicCon and anime convention activities
- Gaming tournament ice-breakers
- Character trivia games
- Comic book shop events
- Virtual watch parties
- Classroom activities

## 🤝 Contributing

Feel free to fork this project and customize the character list, styling, or features to suit your event!

## 📝 License

This project is open source and available under the MIT License.

## 🎉 Credits

Character images are sourced from Bing Image Search API with fallback to UI Avatars. All character names and likenesses are property of their respective owners.

---

**Made with ❤️ for the gaming and comics community**
