# Improve responsiveness and theme toggle

This PR updates index.html and style.css to improve responsiveness, clean up HTML/CSS, and add a theme toggle button that remembers the user's choice using localStorage.

Changes:
- Add <!doctype html> and meta viewport
- Fix link typo (약력.html)
- Replace inline JS theme toggles with centralized script and localStorage
- Remove <style> tags from CSS file and refactor styles
- Improve responsive grid for mobile

Testing:
- Open index.html locally and resize the browser to confirm responsive behavior
- Click the theme toggle (night/day) and refresh to ensure the selection persists
