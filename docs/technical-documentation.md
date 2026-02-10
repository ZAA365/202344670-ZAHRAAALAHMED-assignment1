# Technical Documentation

## Project Info
- **Name**: Personal Portfolio Website
- **Technologies**: HTML, CSS, JavaScript
- **Features**: Dark/Light mode toggle, responsive design

## File Structure
- `index.html` - Main page
- `css/styles.css` - All styling with theme support
- `js/script.js` - Theme toggle functionality
- `assets/images/` - Project screenshots

## Core Features

### 1. Theme Switching System
**HTML:** Button with `id="theme-toggle"`
**JavaScript:** Adds/removes `dark-mode` class on click
**CSS:** Different styles for `.dark-mode` class

### 2. Page Sections
- Header with name
- About me introduction
- Projects table with images
- Contact form

### 3. Color Themes
**Light Mode:**
- Background: white
- Text: black
- Header: lightblue

**Dark Mode:**
- Background: #121212
- Text: white
- Header: #0d47a1

## Setup Instructions
1. Keep all files in their folders
2. Open `index.html` in browser
3. Click "🌙 Switch Mode" to test

## Known Issues
- Inline styles (`style="color: green"`) may not change in dark mode
- Table borders need dark mode colors
- Form has no validation

## Browser Support
Works on Chrome, Firefox, Edge
Requires JavaScript enabled