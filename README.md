# ProfileBrowser

Portable Chrome browser launcher with isolated profiles.

## Description

ProfileBrowser is a lightweight Windows application that launches Google Chrome with isolated user profiles. Each executable creates and manages its own separate Chrome profile, allowing you to maintain multiple browsing environments without interference.

## Features

- **Isolated Profiles**: Each executable maintains its own Chrome profile
- **Uses System Chrome**: Leverages your existing Chrome installation
- **Profile from Filename**: Profile name is automatically extracted from the executable filename
- **Portable**: No installation required - just download and run
- **Clean Separation**: Keep work, personal, and other browsing completely separate

## Usage

1. **Download**: Get the latest `PythonBrowser.exe` from the [Releases](https://github.com/AhmedCemil/ProfileBrowser/releases) section
2. **Rename**: Rename the executable to `ProfileBrowser_YourProfileName.exe`
3. **Run**: Double-click to launch Chrome with your isolated profile

### Examples

- `ProfileBrowser_Work.exe` → Creates "work" profile
- `ProfileBrowser_Personal.exe` → Creates "personal" profile  
- `ProfileBrowser_Development.exe` → Creates "development" profile
- `ProfileBrowser_Shopping.exe` → Creates "shopping" profile

## Requirements

- **Operating System**: Windows 10 or Windows 11
- **Browser**: Google Chrome must be installed
- **No Additional Dependencies**: Uses only built-in Windows and Chrome functionality

## How It Works

1. The application detects the profile name from its own filename
2. Creates a `profiles` folder in the same directory as the executable
3. Launches Chrome with `--user-data-dir` pointing to the isolated profile folder
4. Each profile maintains separate cookies, bookmarks, extensions, and settings

## Download

Visit the [Releases](https://github.com/AhmedCemil/ProfileBrowser/releases) page to download the latest version.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

If you encounter any issues or have questions, please open an issue on this repository.
