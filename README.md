# Interactive Audio

Download Pure Data: https://puredata.info/downloads/pure-data

## Step 1: Open the Pure Data file: `Midterm.pd`
- Turn on the DSP via Pure Data executable

## Step 2: Open the `Play Game` folder
- Execute the `Midterm.exe` executable to launch and play the game
- The Pure Data should supply sound to the game
- Controls:
  - Arrow keys to move the ball
  - Mouse to move the camera
  - Objective is to get all of the rotating floating cubes
  - Try not to fall off the edges

## Step 3:
- To exit the game, hold the keys `Alt-F4` on Windows or `Command-W` on Mac to force close the application then manually close the Pure Data window.

## How the Patch interacts with the Unity Scenes:
- **Trigger ping** when the game *starts*
- **Trigger noise** produced with ***volume change*** when *hitting against any wall*
- **Trigger notes** when *collecting cubes*
- **Sequence playback** a familiar song with ***tempo increasing*** whenever *cubes are collected*
