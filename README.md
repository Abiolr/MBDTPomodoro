
# 🎧 My Beautiful Dark Twisted Pomodoro

<img width="1470" alt="Screenshot 2025-05-08 at 8 17 28 PM" src="https://github.com/user-attachments/assets/9e4b29b0-5514-4832-bbbd-8732845bae6c" />

_A Pomodoro Timer meets ambient sound therapy with Kanye flair_

**Authors:** Abiola Raji, Patrick Dang, John Galang, Jacky On  
**Built for:** COMP 3659 Hackathon  
**Tech Stack:** Python, Tkinter, PIL, Pygame

---

## 🧠 Overview

**My Beautiful Dark Twisted Pomodoro** is a productivity-enhancing desktop application that fuses time management with a calming, customizable user experience. Designed using the Pomodoro technique, it guides users through focused work and break intervals—paired with ambient soundscapes or a Kanye West greeting track to enhance motivation and focus.

---

## ⚙️ Features

- ⏱ **Pomodoro Timer**: 25-minute work sessions, 5-minute short breaks, and 15-minute long breaks
- 🛑 **Pause & Resume**: Flexible control of ongoing sessions without losing progress
- ✅ **Task Tracker**: Built-in checklist for up to 3 tasks, with visual feedback when completed
- 🖼 **Visual Themes**: Image-based cues to distinguish between work and break sessions
- 🔊 **Ambient Sound Player**: Toggle background sounds like rain, waves, or campfire for focus
- 🎵 **Motivational Sound**: Kanye’s “Good Morning” plays at the start of breaks

---

## 🖥️ Screenshots

> 📸 _Include images of the UI here (timer view, task checklists, sound buttons)_

---

## 📦 Installation

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/pomodoro-hackathon.git
   cd pomodoro-hackathon
   ```

2. Install dependencies:
   ```bash
   pip install pygame pillow
   ```

3. Add required assets:
   - Place music files in a folder called `music/`:
     - `beep.mp3`
     - `kanye_good_morning.mp3`
     - `campfire_sound.mp3`
     - `waves_sound.mp3`
     - `rain_sound.mp3`
   - Place the following images in an `images/` folder:
     - `download.png` (work mode image)
     - `break.png` (break mode image)
     - `campfire.png`, `waves.png`, `rain.png`, `no_music.png` (sound toggle buttons)

4. Run the app:
   ```bash
   python main.py
   ```

---

## 🚧 Known Limitations

- Music/sound file paths must remain static (`music/` directory)
- UI layout optimized for large displays (2560x1664 resolution)
- Only supports 3 task entries—future versions could scale dynamically

---

## 🚀 Future Improvements

- Add user-configurable session durations and task list size
- Include more sound options and dynamic volume controls
- Persist task history and productivity stats between sessions

---

## 📜 License

This project is licensed for educational and portfolio purposes. All sound and image assets used must respect their original copyright.

---
