Quill
===

Quill is a small text editor utilizing the terminal, and built in C.


Usage: ./quill `<filename>`

Keys:

    CTRL-S: Save
    CTRL-Q: Quit
    CTRL-F: Find string in file (ESC to exit search, arrows to navigate)

Quill does not depend on any library (not even curses). It uses fairly standard
VT100 (and similar terminals) escape sequences, allowing for portability to almost any device.

# Roadmap

- ~~Search Functionality~~
- ~~Syntax Highlighting~~
- Undo and Redo
- Diff Viewer
- Sectional Undo and Redo
- Multi-user Editing

