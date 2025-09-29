# Trivia Master (React Native / Expo)

A simple 10-question trivia app built with React Native using Expo. Questions are randomized from a fixed pool each run. Tracks score, shows per-question feedback, and a final results screen.

## Run locally
1. Install Node.js (LTS).
2. Install Expo CLI:
   ```bash
   npm install -g expo
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the dev server:
   ```bash
   npm start
   ```
5. Open the project in Expo Go (iOS/Android) or press `w` for web preview.

## Project structure
```
trivia-app/
  App.js
  package.json
  app.json
  .gitignore
  assets/
```

## Notes
- Code is a cleaned version of the CodeHS snippet (removed merge-conflict markers).
- No backend; all questions are local.
