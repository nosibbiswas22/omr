# OMR Sheet

[![Live Demo](https://img.shields.io/badge/Live%20Demo-OMR%20Sheet-d13a31?style=flat-square)](https://nosibbiswas22.github.io/omr/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white&style=flat-square)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white&style=flat-square)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black&style=flat-square)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-2ea44f?style=flat-square)](LICENSE)

## Overview

OMR Sheet is a lightweight, browser-based exam answer sheet for multiple-choice tests. Configure the number of questions and exam duration, then use a clean, responsive interface to answer, navigate, and submit without a backend or build step.

It is designed for quick practice sessions, classroom demonstrations, and small exams where a simple digital OMR experience is all that is needed.

## Features

- Generate a custom answer sheet with any number of questions
- Set a countdown timer for each exam session
- Answer multiple-choice questions from A to D
- Lock answers after selection to mirror a traditional OMR workflow
- Navigate questions with the mouse or keyboard
- Use number keys `1` to `4` to select answers quickly
- Reset the sheet and timer for a fresh attempt
- Run locally or deploy as a static GitHub Pages site

## Live Demo

Try OMR Sheet at [nosibbiswas22.github.io/omr](https://nosibbiswas22.github.io/omr/).

## Built With

- HTML5
- CSS3
- Vanilla JavaScript

## Getting Started

### Run Locally

Clone the repository:

```bash
git clone https://github.com/NOSIBBiswas22/omr.git
cd omr
```

Open `index.html` in a browser. No package installation or build process is required.

### Use the App

1. Enter the number of questions and exam duration in minutes.
2. Select **Start Exam**.
3. Choose an answer for each question. Selected answers are locked automatically.
4. Use `Arrow Up` and `Arrow Down` to move between questions, or use the mouse.
5. Select **Reset** to start over or **Done** to finish the session.

## Project Structure

```text
omr/
├── index.html   # Application markup
├── style.css    # Layout and visual styles
├── script.js    # Timer, navigation, and answer logic
└── LICENSE      # MIT License
```

## Contributing

Suggestions and improvements are welcome. Fork the repository, create a feature branch, make your changes, and open a pull request with a clear description of the update.

## Author

Created by [Nosib Biswas](https://github.com/NOSIBBiswas22).

- [Personal website](https://nosibbiswas22.github.io/nosibbiswas/)
- [Facebook](https://www.facebook.com/nosib.biswas.227)

## License

This project is licensed under the [MIT License](LICENSE).
