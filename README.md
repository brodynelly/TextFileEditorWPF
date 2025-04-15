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
<img width="789" alt="Screenshot 2025-04-14 at 11 03 50 PM" src="https://github.com/user-attachments/assets/939ccd95-36bb-4c6d-9e6f-6289f195c823" />
<img width="1437" alt="Screenshot 2025-04-14 at 11 04 11 PM" src="https://github.com/user-attachments/assets/6e984423-6376-4d05-859a-34d9ada6b15d" />
<img width="790" alt="Screenshot 2025-04-14 at 11 04 27 PM" src="https://github.com/user-attachments/assets/9eb0da90-de28-4674-9e95-69293de2f274" />
