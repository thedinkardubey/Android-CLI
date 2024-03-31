# Android CLI

Android CLI is a terminal emulator app built with React Native that allows users to execute various commands on their Android device's file system.

## Features

- **Command Execution**: Execute various commands such as `cd`, `ls`, `mkdir`, `rmdir`, `append`, `open`, `touch`, `cat`, `rm`, `echo`, `clear`, `date`, `whoami`, `exit`, and `help`.
- **Command History**: View and navigate through the command history.
- **Auto-Complete**: Basic auto-complete functionality suggests commands as users type.
- **File System Access**: Access and manipulate files and directories on the device.
- **Permissions Handling**: Requests necessary permissions (`READ_EXTERNAL_STORAGE` and `WRITE_EXTERNAL_STORAGE`) to access files.

## Installation

### Download Pre-built Executable

You can download the pre-built executable file from the [releases](https://github.com/thedinkardubey/Android-CLI/releases)  section. After downloading, simply run the executable file on your Android device.

### Build from Source

1. Clone the repository:

   ```bash
   git clone https://github.com/thedinkardubey/Android-CLI.git
   ```
2. Navigate into the project directory:
    
    ```bash
    cd Android-CLI
    ```
    
3. Install dependencies:
    
    ```bash
    npm install react react-native-fs react-native-file-viewer react-native-saf-x react-native-device-info @fortawesome/react-native-fontawesome
    ```
    
4. Run the app:
    ```bash
    npm start
    ```



## Usage

1. Launch the app on your Android device or emulator.
2. Use the terminal interface to input commands.
3. View the output in the terminal.

## Contribution

Thank you for considering contributing to this project! Here's how you can get involved:

- **Star the Project**: If you find this project useful or interesting, please give it a star on GitHub. It helps to show support and appreciation for the project.

- **Send Pull Requests**: Contributions via pull requests are welcome! If you see a bug, an opportunity for improvement, or have a new feature idea, feel free to submit a pull request.

- **Join Discussions**: Participate in discussions by opening or commenting on issues. Share your ideas, ask questions, or give feedback to help improve the project.

We appreciate your support and contributions to make this project better for everyone.

## License

This project is licensed under the MIT License.

## Acknowledgements

- React Native
- React Native FS
- React Native File Viewer
- React Native SAF
- React Native Device Info
- Font Awesome


Thank you for using Android CLI! Happy coding!
