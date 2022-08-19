# Emotions Detection App

AI powered hybrid app which uses Tensorflow.js to detect face and recognize emotions.

Technologies used: 
- Frontend: React and Framework7.
- AI: Tensorflow.js ([face-api](https://github.com/vladmandic/face-api)).
- Hybrid deployment: Monaca.

## How to start
1. Download the project.
2. Run `npm install` in the directory.
3. Run `npm run dev` to start the project.
4. If the browser opens url `0.0.0.0:8080`, change it to `localhost:8080`.

## Important files
#### JS
- hybridFunctions.js - includes functions to recognize desktop/mobile device
- routes.js - defines routes in app

#### React
- home.jsx - main page displaying camera and predicting emotions
- settings.jsx - page for modifying app settings (FPS, vibrations, prediction interval, front/back camera)
