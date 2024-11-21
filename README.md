# 2K7EVENTY7
# ⚔️ 2D Turn-Based RPG Battle Game

Play the game here : ( https://ciopialex.github.io/2077/ ) this is a link hosted by GitHub 

Welcome to my **2D Turn-Based RPG Battle Game**! This project is a simple, tactical RPG-style battle system with two player-controlled levels, where players face off against AI-controlled enemies in a turn-based combat sequence. The game includes a range of abilities, special moves, and effects to enhance strategy and keep the gameplay engaging. Built in Unity, this game uses C# scripts to manage everything from animations and sound to battle logic.

---

## 🎮 Gameplay Mechanics

- **Turn-Based Combat**: The game features a turn-based combat system with a series of actions that the player and enemies can choose from each turn.
- **Abilities**: The player can choose from a variety of attacks:
  - **Normal Attack** - A basic attack that deals standard damage.
  - **Spells** - Special attacks with unique animations and effects, including **Thunder Attack**, **Poison**, **Ice Lance**, **Shadow Strike**, and **Kamehameha**.
  - **Ultimate Attack** - Available once the player's limit gauge hits 100%, delivering a powerful attack with unique animations.
- **Hyper Mode**: Activates for 7 turns, increasing the damage of all attacks, adding a strategic boost.
- **Limit Gauge**: The gauge builds up over time, allowing access to the Ultimate Attack when full.
  
---

## 📂 Folder Structure

- **Scripts**
  - *Attacks* - Contains scripts for each unique attack type (e.g., `ThunderAttack`, `Kamehameha`, `IceLance`, etc.), managing their effects and animations.
  - *Battle Management* - Scripts to manage the turn-based logic and update the UI to reflect the state of battle (e.g., `Battle`, `UIBattle`).
  - *Player/Enemy Behavior* - Contains scripts to manage player and enemy actions.
- **Assets** - Includes all assets for visual and audio feedback in the game, such as sprites, animations, and sound effects.
  
---

## 💻 Scripts Breakdown

Each script is responsible for different aspects of the battle experience, from triggering animations to handling game logic. Here’s a quick look at some key scripts:

- **NormalAttack**: Manages basic attacks, triggering sound effects, applying damage, and updating HUD elements.
- **ThunderAttack**: Plays a sequence of animated thunder strikes, inflicting damage over time.
- **Kamehameha**: Aligns and charges a powerful energy attack, dealing damage after a charging period. This one uses DOTween to smoothly handle animations.
- **Poison**: Applies a poison effect with a gradual fade-in, followed by an explosive effect.
- **Ultimate**: The player’s strongest move, activated when the limit gauge is maxed. Plays a unique explosion animation and deals heavy damage to the enemy.

---

## 🔧 Technologies & Tools

- **Unity** (Version 2021.3.x or newer): The main game engine used for this project.
- **C#**: The primary language for scripting game logic and mechanics.
- **DOTween**: A tweening library used to animate game objects smoothly, particularly in attack effects.

---

## 🕹️ How to Play

1. **Launch** the game from the Unity Editor or build an executable.
2. **Start the Game**: Select your attacks strategically during your turn.
3. **Use Abilities**: Use a mix of Normal Attacks, Spells, and the Ultimate Attack when the limit gauge fills up.
4. **Plan Turns**: Watch the limit gauge and time Hyper Mode for maximum damage output.
5. **Win**: Defeat both enemies to proceed to the next level and ultimately win the game!

---

## 🔍 Key Features

- **Custom Animations**: Attack animations and particle effects make each move visually distinctive.
- **Audio Feedback**: Sounds for each move enhance gameplay and signal successful attacks.
- **Smooth Transitions**: DOTween handles animations and movement to keep the experience polished.

---

## 🎓 Learning Outcomes

I created this project to gain hands-on experience with Unity’s 2D tools, C# scripting for game development, and tweening libraries for smooth animations. It was a fun challenge to build and test a working turn-based combat system, giving me insights into handling game logic, character animations, and overall game design principles.

---

## 🚀 Future Improvements

- **Enhanced Enemy AI**: Add more strategic enemy responses based on player actions.
- **More Levels and Abilities**: Expand with additional levels, enemy types, and a wider array of player abilities.
- **Improved UI**: Implement a more polished interface for health bars, gauges, and animations.

---

## 🔗 Dependencies

- **DOTween** by Demigiant [GitHub link](https://github.com/Demigiant/dotween) - A robust tweening library for Unity animations.

---

## 📄 License

This project is open-source under the MIT License, so feel free to fork, experiment, and contribute!

Happy battling! 😊
