# Hooked-Autofisher
A 2D sidescroll idle fishing game.

[Play now on the Google Play Store!](https://www.bluetorchgames.com/hooked)

Welcome to Hooked! Autofisher, an idle clicker fishing game with a charming side-view twist.
Control your hook, reel in exotic fish, and earn money to upgrade your rod, unlock new areas, and even sail out into the deep ocean!
Watch your fishing empire grow automatically.

Designed and Developed by: <br>
Liam Kade <br>
Timothy Johnson <br>

Date: February 2021 to November 2023

## Overview

&nbsp;&nbsp;&nbsp;&nbsp;Hooked! Autofisher is a Unity 2D idle clicker game with a fishing twist.
Players drag the fishing hook around the screen, position it above fish, and try to catch them automatically.
Each catch brings in coins used for upgrades, unlocking new fishing rods and exploring further into the ocean.
The game evolves into a satisfying loop of passive income, upgrades, and discovery.


🧩 Features

    🎣 Drag-and-drop hook mechanic to manually help the autofisher

    🐠 Dozens of fish types with different values and behaviors

    🪙 Money system with persistent upgrades and income multipliers

    🚤 Unlockable boat system to explore further into the sea

    🛠️ Upgrade system for fishing rods, hook speed, depth range, and more

    🔓 New zones with unique fish and environments

    📱 Mobile-friendly design and idle-friendly mechanics

🎮 Gameplay

The world is shown in 2D side view. Move your hook by dragging it horizontally or vertically to try and catch a fish. Once caught, you earn money automatically. Use that money to upgrade your gear and unlock new ocean areas. Progress even when you're away!

### Controls:

| Key   | Action     |
| ------------ | ---------------- |
| Touch Drag   | Move Hook        |
| UI Buttons   | Shop / Settings  |


📁 Code Structure

. <br>
├── Main.java &nbsp;&nbsp;&nbsp;---&nbsp;&nbsp;&nbsp; Main <br>
├── res/ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;---&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Resources folder (sprites, backgrounds, AI.txt) <br>
│   ├── Down.png <br>
    
🖼️ Screenshots / Visuals

![hookbanner](https://github.com/user-attachments/assets/e93d0a96-7d43-477e-801e-cd1d0af52550)

⚙️ How It Works

Hook Movement:

    The hook follows the player's drag input

    Collision with a fish triggers a "catch" attempt based on rarity

Fish System:

    Each fish type has a value and rarity

    Fish swim randomly and can be caught when in range

Economy and Upgrades:

    Every fish earns coins

    Upgrades increase catch speed, fish value, depth, and hook size

Zone Progression:

    Unlock the boat to visit new ocean zones

    Each new zone includes unique fish and challenges

Idle Mechanics:

    Fish are auto-caught while idle (if hook is over a fish)

    Progression and income continue over time

🧰 Technologies Used

    🧠 Unity 2D

    🎨 Custom pixel art and sprite animation

    💾 Save/load system for upgrades and progression

    🎮 Mobile touch controls

    🔄 C# Scripting for game logic

🚀 Getting Started

    To run this project locally:

    1. Clone the repository:

        git clone https://github.com/MrTimmyJ/hooked-autofisher.git
        cd hooked-autofisher

    2. Open with Unity
    
    3. Launch the game scene
    
    4. Run the main entry point in Main.java.

🪪 License

Hooked! AutoFisher is a proprietary product. All rights reserved.
© 2025 Blue Torch Games. Unauthorized distribution or reproduction is prohibited.
