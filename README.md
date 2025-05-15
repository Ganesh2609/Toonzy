# Toonzy - Manga & Comics Website

[View Live Demo](https://ganesh2609.github.io/Toonzy/)

## Overview

Toonzy is a modern, responsive web application for reading manga and comics online. Built with vanilla JavaScript, HTML5, and CSS3, it offers a clean, intuitive interface for users to browse, search, and read comic content across various genres.

## Key Features

### 🎨 Reader Experience
- **Vertical Scrolling Reader**: Smooth, continuous manga-style reading experience with PDF.js integration
- **Responsive Design**: Optimized for all devices - mobile, tablet, and desktop
- **Touch Gestures**: Double-tap to zoom, swipe navigation for mobile devices
- **Chapter Navigation**: Seamless transition between chapters with keyboard shortcuts

### 📚 Content Management
- **Dynamic Library**: Browse comics by genres, daily updates, or trending content
- **Search Functionality**: Find comics quickly by title, genre, or keywords
- **Favorites System**: Save and organize your favorite comics
- **User Profiles**: Personal profile page with reading history and preferences

### 👨‍💻 Creator Dashboard
- **Publishing Tools**: Upload and manage comic content
- **Analytics**: Track reads, rankings, and user engagement
- **Growth System**: Level up with achievements and unlock benefits
- **Creator Guide**: Comprehensive help for content creators

## Technical Architecture

### Core Technologies
- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **PDF Rendering**: PDF.js for high-quality comic viewing
- **Styling**: Modern CSS with Flexbox and Grid layouts
- **Font**: Poppins for clean, readable typography

### Key JavaScript Components
- `main.js`: Core application logic and navigation
- `pdf-viewer.js`: Advanced manga reader with continuous scrolling
- `mobile-menu.js`: Responsive mobile navigation implementation

### Page Structure
```
├── index.html          # Homepage with featured comics
├── genres.html         # Browse by genres
├── daily.html          # Daily updates
├── comic-detail.html   # Individual comic information
├── reader.html         # Manga/comic reading interface
├── profile.html        # User profile management
├── library.html        # Personal comic library
└── publish.html        # Creator dashboard
```

## Performance Optimizations

- **Lazy Loading**: Images load on-demand for better performance
- **Responsive Images**: Different sizes served based on device
- **CSS Optimization**: Minified stylesheets with efficient selectors
- **JavaScript Bundling**: Modular code structure for maintainability

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/Ganesh2609/Toonzy.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Toonzy
   ```

3. Open `index.html` in your browser.

4. Access the site at `http://localhost:8000`
