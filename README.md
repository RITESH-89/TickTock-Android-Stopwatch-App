# ⏱ TickTock – Android Stopwatch App

## 📌 Overview

TickTock is a simple Android Stopwatch application built using Java and XML in Android Studio.  
The app allows users to start, stop, and reset a stopwatch while maintaining state during screen rotations and activity lifecycle changes.

This project demonstrates Android fundamentals including Activity lifecycle handling, state persistence, and UI interaction.

---

## ✨ Features

- ▶ Start stopwatch
- ⏸ Stop stopwatch
- 🔄 Reset stopwatch
- ⏱ Displays time in HH:MM:SS format
- 💾 Maintains state during rotation
- 📱 Clean and centered UI

---

## 🛠 Technologies Used

- Java
- XML
- Android Studio
- Android SDK
- Handler & Runnable
- Activity Lifecycle Methods

---

## 📂 Project Structure

TickTock/
│
├── app/
│   ├── java/
│   │   └── com/example/stopwatch/
│   │       └── StopwatchActivity.java
│   ├── res/
│   │   ├── layout/
│   │   │   └── activity_stopwatch.xml
│   │   └── values/
│   │       └── strings.xml
│   └── AndroidManifest.xml

---

## ⚙ How It Works

1. The app uses a Handler and Runnable to update time every second.
2. Seconds are converted into hours, minutes, and seconds.
3. onSaveInstanceState() preserves stopwatch state.
4. onPause() and onResume() manage running state.

---

## 🚀 How to Run

1. Install Android Studio.
2. Clone this repository:
   git clone https://github.com/yourusername/TickTock.git
3. Open in Android Studio.
4. Sync Gradle.
5. Run on emulator or device.

---

## 📈 Future Improvements

- Add Lap functionality
- Add Material UI design
- Add Dark Mode
- Add sound effects
- Convert to AndroidX with ViewBinding

---

## 👨‍💻 Author

Developed by Ritesh  
Android Developer | Java Programmer  

---

## 📜 License

This project is developed for educational purposes.
