# flutter-started
Getting started for Flutter

## Multi-platform
Flutter transforms the app development process. Build, test, and deploy beautiful mobile, web, desktop, and embedded apps from a single codebase.

## Installation
### macOS
```
## Install homebrew
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

## Brew flutter
brew install flutter
```

## Setup with Doctor
```
## Check for missing dependencies
flutter doctor

## Install android studio
brew install --cask android-studio

## Install vscode
brew install --cask visual-studio-code

## Keep checking with doctor to complete remaining steps for android and iOS requirements
```

## Setup vscode
### Install the Flutter and Dart plugins
- Start VS Code.
- Invoke View > Command Palette….
- Type “install”, and select Extensions: Install Extensions.
- Type “flutter” in the extensions search field, select Flutter in the list, and click Install. This also installs the required Dart plugin.

### Validate your setup with the Flutter Doctor
- Invoke View > Command Palette….
- Type “doctor”, and select the Flutter: Run Flutter Doctor.
- Review the output in the OUTPUT pane for any issues. Make sure to select Flutter from the dropdown in the different Output Options.

### Create the app
- Invoke `View > Command` Palette.
- Type “flutter”, and select the `Flutter: New Project`.
- Select Application.
- Create or select the parent directory for the new project folder.
- Enter a project name, such as `my_app`, and press Enter.
- Wait for project creation to complete and the `main.dart` file to appear.

### Run the app
- Locate the VS Code status bar (the blue bar at the bottom of the window)
- Select a device from the Device Selector area. If no device is available, and you want to use a device simulator, click No Devices and click Start iOS Simulator to launch a simulator.
- Invoke Run > Start Debugging or press F5
- Wait for the app to launch—progress is printed in the Debug Console view.

### Try hot reload
Flutter offers a fast development cycle with Stateful Hot Reload, the ability to reload the code of a live running app without restarting or losing app state. Make a change to app source, tell your IDE or command-line tool that you want to hot reload, and see the change in your simulator, emulator, or device.
- Open lib/main.dart.
- Change the string __'You have ~~pushed~~ the button this many times'__ to __'You have clicked the button this many times'__
- Save your changes: invoke Save All, or click Hot Reload

