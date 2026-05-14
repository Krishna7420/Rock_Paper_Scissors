# 🎰 Rock Paper Scissors Casino

A sleek and animated **Rock Paper Scissors** game built with **SwiftUI** featuring a casino-inspired slot reel battle system.

Challenge the CPU, spin the reels, pick your weapon, and become the ultimate champion 🏆

---

## 📱 Features

- 🎰 Casino-style animated slot reels
- ✊ Rock / 📄 Paper / ✂️ Scissors gameplay
- 🤖 CPU opponent with random move generation
- 🏆 Best of 3 match system
- 💥 Winner popup announcement
- 🔄 Auto reset after match completion
- 🏠 Home screen navigation
- ⚙️ Settings screen
- 📘 How To Play screen
- 🌈 Animated gradient background
- ✨ Glassmorphism UI styling
- 📱 Fully SwiftUI based architecture

---

## 🛠 Tech Stack

- **Swift**
- **SwiftUI**
- **Combine**
- **MVVM Architecture**

---

## 📂 Project Structure

```bash
Rock_Paper_Scissors
│
├── Models
│   ├── Move.swift
│   └── GameSettings.swift
│
├── ViewModels
│   └── GameViewModel.swift
│
├── Views
│   ├── HomeView.swift
│   ├── GameView.swift
│   ├── SlotReelView.swift
│   ├── SettingsView.swift
│   ├── HowToPlayView.swift
│   ├── WinnerPopUpView.swift
│   ├── MenuButton.swift
│   └── FloatingBackgroundView.swift
│
├── ContentView.swift
└── Rock_Paper_ScissorsApp.swift

🎮 How To Play

1. Launch the game
2. Tap Start Game
3. Choose your weapon:
    * ✊ Rock
    * 📄 Paper
    * ✂️ Scissors
4. Watch the casino reels spin
5. CPU reveals its move
6. Round winner gets a point
7. First to 3 wins becomes champion 🏆
