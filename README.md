# CodeAlpha_Transnary

## Overview

**Transnary** is a browser-based language translation tool developed as part of the **CodeAlpha Internship – Language Translation Tool** task.

The application allows users to enter text, select source and target languages, translate the text using Google Translate, copy the translated result, and listen to the translation using browser text-to-speech.

## Features

* Source language selection
* Target language selection
* Interactive language globe
* Google Translate integration
* Real-time translation display
* Language swap functionality
* Copy translated text
* Text-to-speech
* Multiple available system voices
* Responsive interface
* Character counter
* Keyboard shortcut: `Ctrl + Enter` / `Cmd + Enter`

## Technologies Used

* HTML5
* CSS3
* JavaScript
* Google Translate public translation endpoint
* Browser Web Speech API
* Cobe Globe Library

## Translation API

The application uses Google's public web translation endpoint:

```text
https://translate.googleapis.com/translate_a/single
```

The implementation sends the selected source language, target language, and user input to the translation service and combines the returned translation segments correctly.

No personal API key is stored in the source code.

## Text-to-Speech

The application uses the browser's built-in `SpeechSynthesis` API.

Users can:

* Select an available voice
* Listen to the translated text
* Stop speech without changing the button label
* Automatically prefer a voice matching the selected target language

## Supported Languages

The current application includes languages such as:

* English
* Spanish
* French
* German
* Italian
* Portuguese
* Dutch
* Russian
* Chinese
* Japanese
* Korean
* Arabic
* Hindi
* Urdu
* Turkish
* Polish
* Swedish
* Greek
* Hebrew
* Vietnamese
* Thai
* Indonesian
* Bengali
* Persian
* Ukrainian

## How to Run

No backend or build process is required.

1. Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/CodeAlpha_LanguageTranslationTool.git
```

2. Open the project directory.

3. Open `index.html` in a modern web browser.

For the best experience, use a browser with support for the Web Speech API and modern JavaScript features.

## CodeAlpha Task Requirements

This project satisfies the assigned requirements:

| Requirement             | Implementation                    |
| ----------------------- | --------------------------------- |
| User enters text        | Text input area                   |
| Select source language  | Interactive source-language globe |
| Select target language  | Interactive target-language globe |
| Translation API         | Google Translate endpoint         |
| Send text to API        | JavaScript `fetch()`              |
| Display translated text | Translation output panel          |
| Copy button             | Included                          |
| Text-to-speech          | Included                          |
| Voice selection         | Included                          |

## Project Author

**Ahmad Emad**

Engineering Student

## Internship

Developed for the **CodeAlpha Internship Program**.

## License

This project is intended for educational and internship purposes.
