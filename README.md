# IdeaVault Note Taking App

IdeaVault Note Taking App is a desktop application built with Java Swing. This application provides an intuitive and straightforward interface for note-taking.

## Features

- Create, Edit, and Delete Notes: The application provides a simple text area where users can write down their thoughts and ideas. You can add new notes to the list and remove existing notes at any point.
- Attach Files and Images: You can attach files and images to your notes. The files are read and encoded to base64, which is then appended to the note.
- Save Notes to Disk: The application allows you to save all your notes into a text file ("notes.txt") on your disk for future reference. Each note is saved on a new line in the text file.
  
## Usage

To start the application, simply run the `NoteTakingApp.java` file in a Java environment. Once the GUI opens, you can start adding your notes, deleting them, and even attach files or images.

Please note that when attaching files or images, they are saved into the note as base64 strings, so large files will result in very long strings appended to your note.

For any issues or suggestions, please raise an issue in the GitHub repository.
