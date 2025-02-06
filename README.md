# 🪨📄✂️ Real-Time Rock Paper Scissors Game with YOLOv8

This project implements a real-time Rock-Paper-Scissors game using **YOLOv8** for hand gesture detection. The game runs in Google Colab and utilizes a webcam for player input.

## How to Play
1. Both players must start by showing "Rock".
2. Move your hands for 3 seconds. If a player does not move their hand within this time, they lose 1 point.
3. Show your move (Rock, Paper, or Scissors).
4. YOLOv8 detects the moves and determines the winner.
5. Bounding boxes are drawn around detected moves for visualization.

## Running the Game in Google Colab
1. Open [this Colab notebook](https://github.com/RozhanMk/Real-time-rock-paper-scissor/blob/master/RPS-webcam-Yolo8-colab.ipynb).
2. Replace the `API_KEY` with your own from Roboflow.
3. Run all cells to start the game.
4. Allow camera access in Google Colab.

## Dataset
- The [dataset](https://app.roboflow.com/reyhane2525/final-v2-kpqgq) was created using Roboflow.
- It contains labeled images of hands showing Rock, Paper, and Scissors.
- The dataset was made with the help of many students from Shahid Beheshti University (*I don't take that university seriously, but their computer engineering students are quite helpful!*).
- To use the dataset, **you must generate your API key** from Roboflow and replace it in the notebook.

## Bonus point
-  For anyone interested, the notebook for detecting Rock Paper Scissors using mediapipe library is added to this repository.

## Sources
- https://github.com/Gholamrezadar/yolo11-rock-paper-scissors-detection
- [Great code for detecting objects using Yolo in Google Colab with webcam](https://youtu.be/ebAykr9YZ30?si=2Tx_HlV_r4EsBPxi)
- https://youtu.be/k2EahPgl0ho?si=U-R9ZZeoq7Fx8G0b
- https://github.com/cvzone/cvzone/blob/master/cvzone/HandTrackingModule.py

## Tech Stack
- **YOLOv8** (Ultralytics) for real-time hand gesture detection
- **Google Colab** for running the game
- **OpenCV** for image processing
- **Roboflow** for dataset management

## Fine tuning
![](https://github.com/RozhanMk/Real-time-rock-paper-scissor/blob/master/imgs/history.jpg)
![](https://github.com/RozhanMk/Real-time-rock-paper-scissor/blob/master/imgs/confusion%20matrix.jpg)
![](https://github.com/RozhanMk/Real-time-rock-paper-scissor/blob/master/imgs/PR%20curve.jpg)


