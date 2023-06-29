# GPTPalette 

GPTPalette is a Google Chrome extension that allows users to change the visual theme of the ChatGPT app. Users can choose from pre-defined themes or create their own custom themes using CSS3.

## Contributions are welcome!⚡🙌
Contributions to this project are welcome! 🎉 If you find a bug 🐛 or have a feature request 💡, please open an issue or submit a pull request 🤝. We appreciate your help in making this project better for everyone. ✨

## Installation

To install the GPTPalette extension, follow these steps:

1. Download the latest release from the [GitHub repository](https://github.com/your-username/GPTPalette/releases).
2. Unzip the downloaded file.
3. Open Google Chrome and navigate to the extensions settings page (`chrome://extensions/`).
4. Enable developer mode by clicking the toggle switch in the top-right corner.
5. Click the "Load unpacked" button and select the unzipped folder for the extension.

The GPTPalette extension should now be installed and ready to use.

## Usage

To use the GPTPalette extension, follow these steps:

1. Open the ChatGPT app in Google Chrome.
2. Click the GPTPalette icon in the Chrome toolbar to open the extension.
3. Choose a pre-defined theme from the list or create your own custom theme using CSS3.
4. Click the "Apply" button to apply the selected theme to the ChatGPT app.

## How it works

When a user selects a theme using GPTPalette, the extension applies the selected CSS styles to the ChatGPT app by modifying the HTML and CSS of the page. The extension uses JavaScript to dynamically update the styles of the page based on the selected theme.

The extension first retrieves the user's selected theme from the options page and stores it in a variable. It then updates the CSS styles of the ChatGPT app by modifying the `style` attribute of the relevant HTML elements.

For example, if the user selected a theme that changes the background color of the app to blue, the extension would modify the `style` attribute of the `body` element to include the CSS rule `background-color: blue;`. Similarly, if the user selected a theme that changes the font size of the app to 14px, the extension would modify the `style` attribute of the relevant text elements to include the CSS rule `font-size: 14px;`.

Once the styles have been updated, the ChatGPT app will reflect the new theme selected by the user.

## Contributing

If you would like to contribute to the development of GPTPalette, feel free to submit a pull request or open an issue on the [GitHub repository](https://github.com/your-username/GPTPalette).

## License

GPTPalette is licensed under the [MIT License](https://opensource.org/licenses/MIT). See the `LICENSE` file for more details.
