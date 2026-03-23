# SETUP Instructions

## 1. Start up your local server

1. Ensure you have [Node.js](https://nodejs.org/en) installed as we will being `npx` to serve the project locally (required as using our webcam). 
2. From the root of the repo, first run `npm install` and then run `npx serve -p 3000` to start a local server (e.g., `npx serve -p 3000` will serve the project at `http://localhost:3000/` if port 3000 is available). The following steps will assume port 3000 is used.
3. To navigate to each HTML file/page, add it after the link 
    1. trainer.html —> `http://localhost:3000/trainer`
    2. index.html —> `http://localhost:3000`

## 2. Train Your Gesture Model
### ( its alr trained now BUT if u want to do custom poses then you can follow below :) )

1. In Chrome ( NOT BRAVE BROWSER PLS ;-; ) , navigate to the trainer page (ex. `http://localhost:3000/trainer`) 
2. Record samples of your chosen hand sign (both hands visible)
3. Record negative samples (random hand positions, edge cases)
4. Click train → this generates `gesture-model.json` and `gesture-model.weights.bin`
5. Place the exported files in the project root (same folder as the main app)

## 3. Run the App

1. In Chrome, navigate to the home/index page (ex. `http://localhost:3000/`) 
2. Allow camera access
3. Perform your trained hand sign and your clones will appear!


