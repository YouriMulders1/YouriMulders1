A top-down pixel-art math racing game built in Unity. Answer math questions correctly to boost your car's speed and finish the race before time runs out.

---

## Requirements

- **Unity 6000.3.10f1** (Unity 6)
- Universal Render Pipeline (URP) — included via packages
- Windows, macOS, or Linux

---

## Setup Steps

### Step 1 — Clone or download the project

```
git clone <repo-url>
```

Or download and extract the ZIP to a local folder.

---

### Step 2 — Open in Unity Hub

1. Open **Unity Hub**.
2. Click **Add** > **Add project from disk**.
3. Select the `MathRacer` folder.
4. Make sure the editor version shown is **6000.3.10f1**. If not, install it via Unity Hub > Installs.
5. Click the project to open it.

---

### Step 3 — Wait for import

Unity will import all assets and compile scripts on first open. This may take a minute or two. Watch the progress bar at the bottom of the editor.

If you see compiler errors in the Console, try:
- **Assets > Refresh** (Ctrl+R)
- Closing and reopening the project

---

### Step 4 — Open the main scene

1. In the Project window, navigate to `Assets/Scenes/`.
2. Double-click **Main.unity** to open it.

---

### Step 5 — Configure Firebase

The game uses **Firebase Realtime Database** (via REST — no SDK needed) for questions and the leaderboard.

1. Go to your [Firebase Console](https://console.firebase.google.com/) and create a Realtime Database.
2. Open `Assets/StreamingAssets/config.json` and set your database URL:
   ```json
   { "firebaseUrl": "https://YOUR-PROJECT-default-rtdb.firebaseio.com" }
   ```
3. In the Firebase Console, go to **Database > Rules** and set:
   ```json
   {
     "rules": {
       "questions":   { ".read": true, ".write": true },
       "leaderboard": { ".read": true, ".write": true }
     }
   }
   ```
4. To manage questions in-editor, go to **Tools > Question Editor**, make changes, and click **Save** — this syncs to Firebase.

---

### Step 6 — Play the game

1. Press the **Play** button (▶) in the Unity toolbar.
2. Answer math questions that appear on screen — the car drives itself.
3. Correct answers boost speed, wrong answers or timeouts slow you down.
4. Reach 100% of the 500-unit race distance to win.

---

### Step 7 — Build (optional)

1. Go to **File > Build Settings**.
2. Make sure **Main** scene is in the scene list. If not, click **Add Open Scenes**.
3. Select your target platform (PC, Mac, etc.).
4. Click **Build** and choose an output folder.

---

## Project Structure

```
Assets/
  Scenes/          — Main.unity (only scene)
  Scripts/         — CarController.cs, RoadScroller.cs, etc.
  Sprites/         — Pixel-art sprites (cars, roads, props)
  Resources/       — Runtime-loaded UI sprites
  StreamingAssets/ — questions.json (editable via Tools > Question Editor)
```

---

## How to Play

There are no driving controls — the car moves automatically. Your only input is answering the math questions on screen. Answer fast and correctly to go faster.

---

## Notes

- The road theme changes every few tiles: Desert → Highway → Summer → Winter.
- All sprites use 16 PPU (pixels per unit).
- UI sprites are loaded from `Resources/Sprites/UI/` at runtime.

