# XPF-TrueStart
XPF TrueStart is a retro-style new tab extension that includes a customizable YouTube-based music player

## Installation (local testing)
1. Download the ZIP and extract 
2. Go to the extension settings of your browser ( manifest.json writed for Chromium Based Browsers)
3. Enable dev mode
4. Select 'Load Unpacked' and select extracted folder of the extension
5. Enjoy 

Feel free to help yourself and contribute to improving this project

## Repository structure
- options.html — Index Page
- options-script.js — Scripts
- background.js — Background scripts 
- manifest.json — Manifest 
- video_ids.json — YouTube video ids


Background image files are handled via the UI widget and stored using the extension's storage (check options-script.js).
If adding new music categories, update video_ids.json to include arrays of YouTube IDs.
Remove or update third-party libraries only if you understand compatibility requirements.



