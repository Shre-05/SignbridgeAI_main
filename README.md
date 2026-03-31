# SignBridge AI

SignBridge AI is a web-based accessibility tool that bridges communication gaps by converting between text, speech, and sign language — all within a single, minimalist interface.

---

## Features

### 1. Text to Speech
- Type any text and have it read aloud instantly.
- Uses the browser's built-in speech synthesis engine.
- No external APIs or internet dependency for this feature.

### 2. Text to Sign Language
- Converts typed text into Indian Sign Language (ISL) fingerspelling cards.
- Displays each letter of the input as a visual ISL hand sign card.
- Useful for learning ISL letter representations.

### 3. Sign Language to Text
- Uses your device's camera to recognize ISL hand signs in real time.
- Detects hand gestures and outputs the corresponding letter as text.
- Currently supports the following ISL letters: **A, B, C, D, I, U, V, W**

---

## Tech Stack

| Layer     | Technology                        |
|-----------|-----------------------------------|
| Frontend  | React, TypeScript, Tailwind CSS   |
| Backend   | Motoko (Internet Computer)        |
| Speech    | Web Speech API (browser-native)   |
| Camera    | WebRTC / MediaDevices API         |
| Platform  | Caffeine AI on Internet Computer  |

---

## How to Use

1. Open the app in a browser (Chrome or Edge recommended).
2. Choose a tab: **Text to Speech**, **Text to Sign**, or **Sign to Text**.
3. For Sign to Text, allow camera access when prompted and hold an ISL hand sign steady in front of the camera.

---

## Browser Requirements

- Chrome or Edge (latest version recommended)
- Camera permission must be granted for the Sign to Text feature
- Requires HTTPS (the live deployment URL satisfies this automatically)

---

## Project Status

- Text to Speech: Fully functional
- Text to Sign Language: Fully functional (A–Z fingerspelling)
- Sign to Text: Functional, supports A, B, C, D, I, U, V, W (expansion planned)

---

## Live at-
https://shorturl.at/NLqsE

https://signbridgeai-o7o.caffeine.xyz/#caffeineAdminToken=04d93fca25e58e2d54f3a87e4aadc2412b964ea6d7f25f43c0c04dba62aabb33
