# vocab-game-audio-image

A simple game for reviewing vocab using audio and images.

## Setup
![Screenshot 2025-07-04 4 47 00 PM](https://github.com/user-attachments/assets/a84fc62d-1a8b-475a-a156-f920f41ad4fc)
1. Open the index.html file
2. Select folder with media files (images and audios must have same filename, except for the file extension)
3. Specify max number of images to show and number of columns for images
4. Press Start Game

## Gameplay
![Screenshot 2025-07-04 4 44 33 PM](https://github.com/user-attachments/assets/3bcdc7a3-9e74-4169-b353-a0f1943db1a0)
1. Game selects a random audio file and plays it
2. At the same time, game loads a grid of images, one of which matches the played audio
3. User selects one of the images
   - if correct, green background shows and game advances to next round
   - if incorrect, red background shows and user try again until correct answer is selected
   
Note: the game keeps track of incorrect answers, and will load those incorrect audio/image pairs more often.
