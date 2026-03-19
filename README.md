# 🎵 Java Music Player (Console Based)

A simple **Music Player** built using **Java** that allows users to play, pause, reset, and stop audio files directly from the console. This project demonstrates how to work with audio handling in Java using the `javax.sound.sampled` package.

---

## 📌 Project Description

The Java Music Player is a console-based application developed to understand how audio processing works in Java. It allows users to control playback of a `.wav` audio file through simple keyboard inputs.

This project focuses on implementing core Java concepts such as file handling, exception handling, user input handling, and audio streaming using the Java Sound API.

It is a beginner-friendly project that demonstrates how to build an interactive system using Java without any GUI framework.

---

## 🚀 Features

- ▶️ Play audio  
- ⏸️ Pause audio  
- 🔄 Reset audio to beginning  
- ❌ Quit application  
- 🎧 Supports `.wav` audio format  
- 💻 Simple console-based interface  

---

## 🛠️ Technologies Used

- Java  
- Java Sound API (`javax.sound.sampled`)  
- Scanner (for user input)  

---

## 📂 Project Structure

MusicPlayer/
│
├── MusicPlayer.java  
├── crystal.wav  
└── README.md  

---

## ⚙️ How It Works

1. The program loads a `.wav` audio file using AudioSystem.  
2. A Clip object is created to control playback.  
3. The user is given options: Play, Pause, Reset, and Quit.  
4. Based on input, the audio is controlled accordingly.  

---

## ▶️ How to Run the Project

### Prerequisites
- Java JDK (Java 8 or above)

### Steps

1. Place your `.wav` file in the project folder (e.g., crystal.wav)

2. Compile the program:
   javac MusicPlayer.java

3. Run the program:
   java MusicPlayer

---

## 💻 Sample Output

P = Play  
S = Pause  
R = Reset  
Q = Quit  
Enter your choice :

P  
(Playing audio...)

S  
(Audio paused)

R  
(Audio reset)

Q  
(Program exited)

---

## ⚠️ Important Notes

- Only `.wav` audio files are supported  
- Ensure the file path is correct  
- The audio file must be in the same directory as the Java file  

---

## 🎯 What I Learned

- Java Sound API basics  
- Working with audio streams  
- Handling user input in loops  
- Exception handling  
- Building interactive console applications  

---

## 📌 Future Improvements

- Add GUI using Java Swing or JavaFX  
- Support MP3 files  
- Add volume control  
- Add playlist feature  
- Add progress bar  

---

## 👨‍💻 Author

Takunda Gorogodo  
CSE Student | Developer  

---

## 📄 License

This project is open-source and available for learning and educational purposes.
