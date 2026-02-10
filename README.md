Car World React Landing Page
A sleek, responsive landing page built with React JS. The project features a dynamic background (auto-sliding images and video playback), a custom navigation bar, and interactive UI components.

🚀 Features
Dynamic Backgrounds: Automatically cycles through three high-quality BMW X5 images every  seconds.

Video Integration: Toggle between background images and a background video.

State Management: Uses React useState and useEffect hooks to manage image counts and play/pause status.

Smooth Animations: CSS Keyframes for fade-in transitions. 

Interactive UI: Custom dots navigation to jump to specific slides.

🛠️ Tech Stack
Framework: React JS (Vite)

Styling: CSS3 (External stylesheets per component)

Icons: Custom PNG assets

Fonts: Google Fonts (Outfit & Poppins)

📂 Project Structure
Plaintext

src/
├── assets/             # Images and Video files
├── components/
│   ├── background/     # Background image/video logic
│   ├── hero/           # Text overlay and slide controls
│   └── navbar/         # Navigation menu
├── App.jsx             # Main application state and data
└── index.css           # Global resets and fonts
