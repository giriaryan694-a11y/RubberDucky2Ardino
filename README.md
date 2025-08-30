# RubberDucky2Ardino

## RubberDucky Script → Arduino C Converter

![Made by Aryan Giri](https://img.shields.io/badge/Made%20By-Aryan%20Giri-brightgreen)

A **simple and powerful web-based tool** to convert **Rubber Ducky scripts** into **Arduino C code** compatible with Digispark or Arduino devices using the DigiKeyboard library
link : https://giriaryan694-a11y.github.io/RubberDucky2Ardino/
---

## Features

- Convert standard Rubber Ducky payloads into Arduino C automatically.
- Supports:
  - `DELAY`
  - `STRING`
  - `ENTER`, `TAB`
  - `GUI`, `CTRL`, `ALT`, `SHIFT` combos
- Multi-key combinations (e.g., `CTRL-ALT-DELETE`, `GUI r`) handled properly.
- Multi-line typing supported.
- Copy, Paste, and Download `.ino` functionality.
- Fully client-side — no server required.

---

## Usage

1. Open the **index.html** file in a modern browser.
2. Paste your **Rubber Ducky script** into the textarea.
3. Click **Convert to Arduino C**.
4. The generated Arduino code appears below.
5. Use the **Copy** button to copy it, **Paste** button to paste into the Duck script area, or **Download** button to save as `.ino`.
6. Upload the `.ino` to a Digispark/Arduino using Arduino IDE.

---

## Notes

Make sure you have the DigiKeyboard library installed in Arduino IDE.

Delays can be adjusted depending on the speed of the target system.

The CTRL+V command simulates pasting from clipboard, so make sure content is copied beforehand.

Always test in a safe environment.

---

Made By

Aryan Giri – Aiming to make cybersecurity tools simple and accessible.
Check out more projects on my GitHub.


