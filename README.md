# NotebookLM Content Adder

A clean Chrome extension for adding web content to Google NotebookLM notebooks.

## ✨ Features

- **Direct Integration**: Add current page to NotebookLM with one click
- **Notebook Management**: Create new notebooks or select existing ones
- **Smart Suggestions**: Auto-generates notebook names from page titles
- **Paywall Detection**: Warns about potentially paywalled content
- **Clean UI**: Modern, accessible interface

## 🔒 Privacy & Security

- **No Tracking**: Zero analytics or data collection
- **No Third-Party Services**: Direct integration with NotebookLM only
- **Local Storage Only**: Settings stored locally in browser
- **Open Source**: Full transparency, no hidden code
- **Clean Implementation**: No remnants from other extensions

## 🚀 Installation

1. Download or clone this repository
2. Open Chrome and go to `chrome://extensions/`
3. Enable "Developer mode" (top right toggle)
4. Click "Load unpacked" and select the extension folder
5. Make sure you're logged into NotebookLM in your browser

## 💻 Technical Details

- **Manifest V3**: Modern Chrome extension architecture
- **Direct API Integration**: Uses NotebookLM's internal endpoints
- **Dynamic Authentication**: Extracts session tokens automatically
- **No External Dependencies**: Self-contained implementation

## 🛠️ Usage

1. Navigate to any webpage you want to save
2. Click the extension icon
3. Select an existing notebook or create a new one
4. Click "Add to NotebookLM"
5. Optionally click "Open Notebook" to view in NotebookLM

## 📱 Supported Content

- **Articles & Blog Posts**: Clean text extraction
- **YouTube Videos**: Video metadata and links
- **PDF Documents**: Direct URL linking
- **Any Webpage**: Universal content support

## ⚖️ License

This is a clean, independent implementation created for educational purposes. 

**Important**: This extension contains no third-party tracking, analytics, or remnants from other extensions. It's built from the ground up with privacy in mind.

## 🔧 Development

The extension consists of:
- `background/service-worker.js` - Core functionality and API integration
- `popup/` - User interface components  
- `manifest.json` - Extension configuration

Built with vanilla JavaScript, HTML, and CSS. No frameworks or external libraries.

## 🛡️ Code Integrity

- **No Analytics**: No Mixpanel, Google Analytics, or tracking
- **No External URLs**: No third-party service calls
- **No Hidden Features**: All functionality is transparent
- **Clean Codebase**: Original implementation without copied tracking code