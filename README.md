# OmniText

A zero-build, client-side phrase board app built with plain HTML, CSS, and
JavaScript.

Designed for people who have difficulty speaking (e.g., when they are sick),
OmniText allows you to save your favorite words or sentences and display them
instantly in full screen for quick and easy communication.

## Features

- **Zero Build:** No complex build tools or frameworks needed. Just plan HTML,
  CSS (via Tailwind CDN and inline styles), and JavaScript.
- **Client-Side:** Runs entirely in the user's browser.
- **Local Storage:** Saved phrases are stored directly in your browser's
  `localStorage`, keeping your data private and readily available.
- **Full-Screen Display:** Tap a saved phrase to display it prominently in full
  screen, making it easy for others to read.
- **Progressive Web App (PWA):**
  - **Installable:** Add OmniText to your device's home screen for quick access,
    just like a native app.
  - **Offline Support:** Thanks to the Service Worker, the core application
    assets are cached, allowing you to access and use your saved phrases even
    without an internet connection.
- **Responsive Design:** Adapts to various screen sizes, from mobile phones to
  desktops.

## How to Use

1. Enter a phrase or sentence into the text input field.
2. Click "Add Text" or press Enter to save the phrase.
3. Saved phrases appear below as buttons.
4. Click any saved phrase button to display it in full screen.
5. Tap anywhere on the full-screen display to dismiss it.
6. Click the "✕" button next to a phrase to delete it (requires confirmation).
7. Click "Clear All Phrases" to remove all saved phrases (requires
   confirmation).
