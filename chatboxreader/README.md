# Chatbox Reader – View & Speak Transcribed Text

**Chatbox Reader** is a lightweight companion to the Chatbox Editor.  
It is optimized for reading text from ChatGPT "copy text" field.

## 🔧 Features

- 🎙️ **Voice Playback**: Uses the Web Speech API to read aloud the transcribed text
- 📋 **Clipboard Ready**: Automatically copies the latest transcript for fast sharing
- 🖱️ **Auto-Paste Mode**: (Planned) Automatically pastes text into active input fields on left click
- 💡 **Simple UI**: Clean, distraction-free layout optimized for listening or quick review
- 📱 **Responsive Design**: Works on mobile, tablet, and desktop
- 🧩 **Modular Architecture**: Easily integrates with other chatbox tools or host pages

## 🚀 Getting Started

1. Install dependencies:
   npm install


2. Start the development server:
   npm run dev


3. Build for production:
   npm run build


Usage
1. Copy text from ChatGPT "copy" icon below response.
2. Clicking in the text input field will auto-paste the clipboard contents.
3. The Web Speech API will read the content aloud using your system voice. 
4. Use "Pause" and "Play" for additional playback control.

Browser Compatibility
Requires browsers that support the Web Speech API (Chrome, Edge, Safari).
