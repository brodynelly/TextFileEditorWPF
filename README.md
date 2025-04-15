# Plain Text Editor – M8 Assignment

This application is a lightweight plain text editor built using C# and WPF (or UWP) for Module 8 of the course. The project demonstrates essential file I/O, dynamic UI scaling, and stateful document handling following the MVC architecture pattern.

## Features

- **Resizable TextBox**: The text input area scales with the window and wraps long lines. Vertical scrollbars appear when content overflows.
- **Multiline Input**: Supports line breaks, tab characters, and continuous typing without horizontal scroll.
- **Menu Bar**:
  - **File**:
    - **New**: Start a new, blank document.
    - **Open**: Open existing `.txt` files using a file dialog.
    - **Save**: Save to the current file, or prompt if unsaved.
    - **Save As**: Save the current content to a new file.
    - **Exit**: Closes the application.
  - **Help**:
    - **About**: Displays application and developer information.
- **Dynamic UI**: No components disappear or break when resizing the window.
- **File Validation**: Only `.txt` files can be opened and saved.
- **Contextual Menu States**: Menu items are enabled/disabled based on document state (e.g., Save is disabled when there’s nothing to save).
- **File Change Tracking**: Users are prompted to save unsaved changes before destructive actions.
- **File Path Intelligence**: Save dialogs default to the last used location and pre-fill file names
