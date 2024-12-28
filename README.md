# Home Assistant Custom Components Collection

A collection of enhanced custom components for Home Assistant.

## Components

### OpenAI Conversation Custom

An enhanced version of the OpenAI conversation integration that adds support for custom base URLs, allowing you to use OpenAI-compatible endpoints.

#### Features
- All features of the original OpenAI conversation integration
- Added support for custom base URLs (e.g., Azure OpenAI, self-hosted endpoints)
- Compatible with Home Assistant 2024.1.0 and newer

#### Installation
1. Install via HACS by adding this repository as a custom repository
2. Restart Home Assistant
3. Add the integration through the Home Assistant UI:
   - Go to Settings -> Devices & Services
   - Click "Add Integration"
   - Search for "OpenAI Conversation Custom"

#### Configuration
Configure through the UI with these options:
- API Key (required)
- Base URL (optional) - URL for your OpenAI-compatible endpoint
- Other standard OpenAI conversation options

#### Usage
Use exactly like the standard OpenAI conversation integration, but with the added ability to specify a custom base URL for API endpoints.

## Contributing
Feel free to submit issues and pull requests.

## License
Apache License 2.0

## Credits
Based on the official Home Assistant OpenAI conversation integration.