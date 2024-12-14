# Kahoot! Helper Extension

Kahoot! Helper is a browser extension that enhances your Kahoot! gameplay experience. It uses AI-powered suggestions to help answer questions accurately and efficiently.

## Features

- **AI-Powered Answer Assistance**: Leverages the Gemini API to provide intelligent answer suggestions.
- **Confidence Display**: Shows a confidence score for the AI’s recommendation, along with a visual indicator.
- **Floating Panel**: Displays questions, answers, and suggestions in a draggable panel on the Kahoot! game page.
- **User-Controlled Functionality**: Easily toggle the extension on or off.
- **Secure API Key Management**: Enter and securely store your Gemini API key directly in your browser.
- **Modern Design**: Clean and responsive interface with a futuristic look.

## How It Works

1. The extension detects Kahoot! questions and answer options in real-time.
2. It sends the data to the Gemini API for analysis.
3. AI suggestions, including a confidence score, are displayed in the floating panel.
4. Users can interact with the panel to view or dismiss suggestions.

## Prerequisites

- A Gemini API key (available from [Google AI Studio](https://aistudio.google.com/app/apikey)).
- A modern web browser (e.g., Chrome, Brave).
- Access to a Kahoot! game for testing.

## Installation

1. **Download the Extension**:
   - Visit the [Releases](https://github.com/xtle0o0/kahoothelper/releases) section of the GitHub repository.
   - Download the latest `.crx` file (extension package) from the releases.

2. **Go to Extensions Page**:
   - Open your browser and navigate to `chrome://extensions`.

3. **Enable Developer Mode**:
   - Toggle the "Developer mode" switch at the top-right corner.

4. **Install the Extension**:
   - Drag and drop the downloaded `.crx` file into the `chrome://extensions` page.

5. **Use the Extension**:
   - The extension will activate automatically on `kahoot.it`.

## Usage

1. **Enter API Key**:
   - When using the extension for the first time, enter your Gemini API key.
   - The key is securely stored in your browser and will persist unless the extension is uninstalled.
   
2. **Join a Kahoot! Game**:
   - Open `kahoot.it`, join a game, and start playing.

3. **AI Suggestions**:
   - When questions appear, the extension will provide AI-powered suggestions for answers.

4. **Toggle Functionality**:
   - Use the "Enable/Disable" button in the panel to control the extension.

## Troubleshooting

- **Invalid API Key**: Ensure your Gemini API key is correct.
- **Extension Not Working**: Reload the Kahoot! page or the extension.
- **Console Errors**: Check the browser console for error messages and report them if needed.

## Contributing

Contributions are welcome! Submit issues or pull requests via the GitHub repository.

## License

This project is licensed under the [MIT License](LICENSE).
