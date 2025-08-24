# Contact Form Project

A modern, responsive contact form built with React and Vite. Features a beautiful UI with background video support, form validation, and Formspree integration.

## Features

- 🎥 Background video with fallback gradient
- 📱 Fully responsive design
- ✅ Form validation (email, phone, required fields)
- 🔒 Privacy policy and terms & conditions checkboxes
- 📧 Formspree integration for form submission
- 🎨 Modern glassmorphism design
- 📱 Mobile-first responsive layout

## Getting Started

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn

### Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:5173`

## Project Structure

```
src/
├── App.jsx          # Main app component
├── homescreen.js    # Contact form component
├── assets/
│   └── Videos/     # Video assets
└── ...
```

## Configuration

### Formspree Setup

The form is configured to submit to Formspree. To use your own endpoint:

1. Sign up at [Formspree](https://formspree.io/)
2. Create a new form
3. Replace the endpoint URL in `homescreen.js`:
   ```javascript
   const response = await fetch('YOUR_FORMSPREE_ENDPOINT', {
   ```

### Video Background

Place your background video file at `src/assets/Videos/one.mp4`. The component includes a fallback gradient background if the video fails to load.

## Customization

### Colors
The primary accent color is `#00d4aa` (teal). You can modify this throughout the component to match your brand.

### Styling
All styles are inline using React's style prop for easy customization. The component includes responsive breakpoints for mobile devices.

## Build for Production

```bash
npm run build
```

## Technologies Used

- React 19
- Vite
- Formspree
- CSS-in-JS (inline styles)

## License

This project is open source and available under the MIT License.
