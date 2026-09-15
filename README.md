<div align="center">

# Notes Taking Application

### Jot down quick notes that stay saved in your browser

A minimal sticky-notes app for capturing thoughts on the fly. Add as many notes as you like, type freely, and everything is saved automatically in your browser so it is still there when you return. Built with vanilla HTML, CSS, and JavaScript, with no dependencies and no build step.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?logo=javascript&logoColor=black)
![Storage](https://img.shields.io/badge/Storage-localStorage-orange)

</div>

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [How It Works](#how-it-works)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Data Storage](#data-storage)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

---

## Overview

Notes Taking Application is a front-end only app that runs entirely in the browser. Each note is a resizable card with its own text area and a small toolbar for saving and deleting. Notes are persisted to local storage as you type, so your content is restored automatically on your next visit.

## Features

- Create unlimited notes with a single button
- Automatic saving to the browser as you type
- Save and delete controls on every note
- Notes reload automatically when the page is reopened
- Clean card layout with a warm gradient background
- Zero dependencies beyond an icon font

## Tech Stack

| Technology | Role |
| --- | --- |
| HTML5 | Page structure and controls |
| CSS3 | Styling, layout, and card design |
| JavaScript | Note creation, persistence, and rendering |
| Web Storage API | Local storage of note content |
| Font Awesome | Toolbar icons |

## How It Works

Clicking the add button creates a new note card containing a text area and save and delete icons. Typing in any note triggers a save that serializes every note's text into local storage. Deleting a note removes its card and updates storage. On page load the app reads the saved notes and recreates each card with its content, or starts with a single empty note if none are saved.

## Project Structure

```
project36/
├── index.html
├── style.css
├── script.js
└── README.md
```

## Getting Started

No installation or server is required.

Clone the repository:

```bash
git clone https://github.com/Kumar44developer/Notes-Taking-Application-.git
```

Open `index.html` in any modern browser. For live reloading during development, the VS Code Live Server extension works well.

## Usage

1. Click Add Note to create a new note.
2. Type your content directly into the note, and it saves automatically.
3. Use the trash icon to delete a note you no longer need.

## Data Storage

Notes are stored under a single key in the browser's local storage as a JSON array of text values. The data stays on your device and is never sent anywhere. Clearing browser storage removes all saved notes.

## Roadmap

- Note titles and search
- Color labels and pinning
- Rich text formatting
- Export and import notes
- Cloud sync across devices

## Contributing

Contributions are welcome. Fork the repository, create a feature branch, commit your changes, and open a pull request with a clear description.

## License

This project is released under the MIT License.

## Author

Created by [Kumar44developer](https://github.com/Kumar44developer).
