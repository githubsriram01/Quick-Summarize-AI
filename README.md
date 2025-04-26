# Quick-Summarize-AI

# AI Summary for Articles Extension

**Developer**: P Sriram Yadav  
**Institution**: VIT Vellore (Vellore Institute of Technology)  
**Status**: Student Project  

A browser extension that generates AI-powered summaries of web articles using Google's Gemini API.

## Features

- Generate summaries in three formats:
  - Brief (2-3 sentences)
  - Detailed (comprehensive overview)
  - Bullet points (5-7 key points)
- Copy summaries to clipboard with one click
- Easy API key configuration
- Works on most article-based websites

## Installation

1. **Clone this repository** or download the source code
2. **Load the extension in your browser**:
   - Chrome/Edge:
     1. Go to `chrome://extensions`
     2. Enable "Developer mode"
     3. Click "Load unpacked"
     4. Select the extension folder
   - Firefox:
     1. Go to `about:debugging`
     2. Click "This Firefox"
     3. Click "Load Temporary Add-on"
     4. Select any file in the extension folder

## Configuration

1. After installation, click the extension icon
2. Click "AI Summary Settings" or navigate to the options page
3. Enter your [Gemini API key](https://makersuite.google.com/app/apikey)
4. Click "Save Settings"

## Usage

1. Navigate to any article or webpage
2. Click the extension icon in your browser toolbar
3. Select your preferred summary type:
   - Brief Summary
   - Detailed Summary
   - Bullet Points
4. Click "Summarize This Page"
5. When the summary appears, you can:
   - Copy it to clipboard with the "Copy Summary" button
   - Regenerate with different settings

## Files Overview

- `popup.html` - Main extension interface
- `options.html` - Settings page for API key configuration
- `popup.js` - Handles summary generation and UI interactions
- `options.js` - Manages API key storage
- `content.js` - Extracts article text from webpages
- `background.js` - Handles first-run setup
- `manifest.json` - Extension configuration file

## Dependencies

- Google Gemini API (requires API key)
- Modern browser with Manifest V3 support

## Limitations

- May not work perfectly on all websites (depends on article structure)
- Free Gemini API has usage limits
- Very long articles may be truncated

## Troubleshooting

- If summaries aren't generating:
  - Verify your API key is correct
  - Check your internet connection
  - Ensure the page has readable text content
- If the extension doesn't load:
  - Verify you're using a supported browser
  - Check for errors in the browser's extension console

## Future Improvements

- Add support for more summary formats
- Implement local caching of summaries
- Add dark mode support
- Include estimated reading time

## License

[MIT License](LICENSE) - Free for personal and commercial use
