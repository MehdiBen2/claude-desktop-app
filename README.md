# Claude Desktop App

A simple Electron-based desktop application wrapper for Claude.ai. This app allows you to use Claude.ai in a native desktop window instead of a browser tab.

## Features

- Native desktop experience for Claude.ai
- Clean and minimal interface
- Windows support (can be expanded to macOS and Linux)
- Installer provided

## Installation

You can either download the pre-built installer or build it yourself from source.

### Using the Installer

1. Download the latest installer from the [Releases](https://github.com/MehdiBen2/claude-desktop-app/releases) page
2. Run the installer
3. Follow the installation wizard
4. Launch Claude Desktop from your Start Menu or Desktop shortcut

### Building from Source

Prerequisites:
- Node.js (version 14 or higher)
- npm (usually comes with Node.js)

Steps:
```bash
# Clone the repository
git clone https://github.com/MehdiBen2/claude-desktop-app.git

# Navigate to project directory
cd claude-desktop-app

# Install dependencies
npm install

# Start the app in development mode
npm start

# Build the installer
npm run build
```

The built installer will be available in the `dist` folder.

## Development

- `main.js` - Main Electron application file
- `package.json` - Project configuration and dependencies

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Disclaimer

This is an unofficial desktop application wrapper for Claude.ai. It is not affiliated with, officially connected to, or endorsed by Anthropic.

## Support

If you encounter any issues or have questions:
1. Check the [Issues](https://github.com/MehdiBen2/claude-desktop-app/issues) page
2. Create a new issue if your problem isn't already listed