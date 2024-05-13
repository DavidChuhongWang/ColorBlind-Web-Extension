# ColorBlind Friendly Chrome Extension

ColorEyes project is a Chrome extension designed to enhance web accessibility for colorblind users by dynamically altering web page colors. It provides a customizable experience where users can replace certain colors that are typically difficult to distinguish, thus making the web more accessible.

## Features

- **Dynamic Color Replacement**: Automatically adjusts colors on web pages based on user-defined settings to enhance visibility for colorblind users.
- **User Customization**: Allows users to specify which colors should be replaced and what they should be replaced with.
- **Accessibility Focus**: Designed specifically to aid colorblind users, making it easier to navigate and understand web content.

## Installation

To install ColorEyes as a Chrome extension, follow these steps:

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/DavidChuhongWang/ColorBlind-Web-Extension.git
   ```
2. Open Chrome and navigate to `chrome://extensions/`.
3. Enable Developer Mode by toggling the switch at the top right.
4. Click on "Load unpacked" and select the `ColorBlind Web Extension` directory from your local machine where you have cloned the repository.
5. The extension should now appear in your list of Chrome extensions and is ready to use.

## Usage

Once installed, `ColorEyes` will automatically begin to replace colors on all web pages according to the default settings. To customize these settings:

1. Click on the ColorEyes icon in the Chrome toolbar.
2. The popup (`popup.html`) will allow you to enable or disable the extension and configure your color replacement preferences.
3. Alternatively, you can access more detailed settings by navigating to the options page (`diagnosis.html`) through the extension's popup menu.

## Configuration

ColorEyes offers a variety of configuration options accessible via the options page:

- **Enable/Disable**: Toggle the extension on or off globally.
- **Color Settings**: Configure specific colors that should be replaced and define their replacements.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
