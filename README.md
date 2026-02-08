🏎️ Racing Game (Raylib)
📌 Description

This is a racing game developed in C using Raylib.
The goal is to complete all laps as fast as possible while respecting checkpoints and staying inside the track.

The game saves the best lap time to a file so the player can try to beat their record.

🎮 Controls

⬆️ Up Arrow – Accelerate

⬇️ Down Arrow – Brake / Reverse

⬅️ Left Arrow – Turn left

➡️ Right Arrow – Turn right

SPACE – Start the race

ENTER – Return to menu after finishing

ESC – Go back / Exit screens

🏁 Game Rules

Complete 3 laps to finish the race

You must pass all checkpoints before the finish line

Leaving the track resets the car to the start position

Cutting the track or going backwards does not count

Time only runs while the race is active

⏱️ Time System

The timer starts when the race begins

The timer stops when the race ends

The best time is saved in record.txt

If no record exists, the first completed time is saved automatically

🧠 Game States

The game uses a state-based system:

MENU – Main menu

RULES – Game rules

READY – Preparation screen

RACING – Race in progress

(This structure makes it easy to add new tracks in the future.)

💾 Important Files

record.txt – Stores the best time

track.png – Track image

track_limits.png – Track collision limits

car.png – Car texture

🛠️ Technologies Used

Language: C

Graphics Library: Raylib

Math: math.h

File handling: stdio.h

🚀 Possible Future Improvements

Multiple tracks

Progressive difficulty

Car upgrade system

Time leaderboard

Sound effects and music

Better menus and animations

👤 Author

Developed by Rafael Oliveira
📍 Portugal
