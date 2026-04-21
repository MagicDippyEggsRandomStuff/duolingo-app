# Duolingo Desktop App

This project provides a dedicated Duolingo desktop app that wraps the `https://www.duolingo.com/` web interface in a standalone Electron window.

## Features

* Dedicated desktop window for Duolingo.
* Uses `https://www.duolingo.com/` for the core experience.
* Automated builds for 32-bit and 64-bit Windows executables via GitHub Actions.

## Installation

You can find the latest releases (including `.exe` installers and `.zip` portable versions) on the [Releases page](https://github.com/MagicDippyEgg/duolingo-app/releases) of this repository.

1.  Go to the [Releases page](https://github.com/MagicDippyEggsRandomStuff/duolingo-app/releases).
2.  Download the latest `Duolingo.Setup.X.X.X.exe` for a standard installer, or the `Duolingo-X.X.X-win.zip` for a portable version.
3.  Run the installer or extract the zip file to your desired location.

## Important Notes

Please be aware of the following behaviors and limitations:

* **Login Data Sharing:** This Duolingo client may share login-related Electron session data with other builds that use the same app ID and profile location. Running multiple wrappers at once may affect session persistence.
* **Camera and Screen Sharing:** At present, camera and screen sharing functionalities within this client may not work reliably in all environments.

## Contributing

Feel free to open issues or submit pull requests if you have suggestions or improvements!
