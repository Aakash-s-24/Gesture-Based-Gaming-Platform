                                                                            Project Title: INTERACTIVE GESTURE BASED GAMING
PLATFORM USING COMPUTER VISION(CV)
Team Name: GESTURE-TECH INNOVATORS
Introduction:
This project focuses on developing two interactive games, Snake and Rock-Paper-Scissors, leveraging
Python, OpenCV, and the cvzone library for hand gesture recognition. The goal is to explore computer
vision technologies to create engaging and intuitive game experiences. Through hand gestures, players
can control game actions in real-time, offering a unique and accessible gaming interface. The project
showcases the potential of computer vision in enhancing user interaction within digital environments.
**********************************************************************************************
Overview:
Our platform offers two games:
 Snake Game: A modern twist on the classic snake game, where the player controls the snake
using hand gestures. The objective is to eat food that randomly appears on the screen, which
increases the snake's length. The game ends if the snake hits itself.
 Rock-Paper-Scissors Game: An interactive version of the traditional rock-paper-scissors
game, where the player's hand gesture is recognized by the computer to play against an AI
opponent. The game keeps score and displays the winner after each round.

*********************************************************************************************
Technical Discription:
 Tkinter is used to create the main application window, buttons, and other GUI
elements, allowing the player to choose between the Snake Game and the RockPaper-Scissors Game. The interface is designed to be simple and user-friendly, with
clear instructions and feedback provided to the player.

 OpenCV and cvzone are pivotal for the gesture recognition part of the games.
OpenCV captures video from the webcam and processes the images to detect the
player's hand gestures in real-time. The HandDetector module from cvzone is
specifically used for detecting hand landmarks and gestures, which are then mapped
to game controls.

 The Snake Game involves real-time image processing to detect hand gestures, which
control the movement of the snake on the screen. The game dynamically updates the
snake's length and checks for collisions with the food and itself. A scoring system
increases the game's challenge and engagement.

 The Rock-Paper-Scissors Game leverages gesture recognition to determine the
player's choice of rock, paper, or scissors. The game pits the player against a simple
AI that randomly selects its move. A timer ensures each round is played within a
specific timeframe, and scores are updated after each rou
