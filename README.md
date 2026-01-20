# SpaceWar: WPF Arcade Shooter

![Language](https://img.shields.io/badge/language-C%23-green)
![Framework](https://img.shields.io/badge/.NET%208-WPF-purple)
![License](https://img.shields.io/badge/license-MIT-blue)

**SpaceWar** is a classic arcade-style space shooter game developed using **C#** and **WPF (Windows Presentation Foundation)**.

It demonstrates core Object-Oriented Programming (OOP) principles, custom collision detection logic, and dynamic UI management in a .NET environment.

## Key Features

* **Custom Game Engine:** Logic loop and rendering built entirely within WPF.
* **Object-Oriented Design:** Modular structure with distinct classes for `Enemy`, `Bullet`, `SpaceShip`, and `Physics`.
* **Collision Detection:** Custom algorithms to handle hitboxes and interactions between entities.
* **Customizable Controls:** Players can rebind movement keys to their preference via the settings.
* **Dynamic Difficulty:** Progressive gameplay mechanics.
* **Sound Effects:** Integrated audio for shooting and explosions.

## How to Play

* **Controls:** Key bindings for movement are **fully customizable**. You can configure your preferred keys (e.g., Arrow Keys, WASD) in the game settings.
* **Shoot:** Press `Space` to fire lasers.
* **Objective:** Destroy incoming enemy ships and survive as long as possible!

## Tech Stack

* **Language:** C#
* **UI Framework:** WPF (XAML)
* **IDE:** Visual Studio

## Installation & Run

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/aergen29/SpaceWar.git
    ```
2.  **Open the project:**
    Double click on `SpaceWar.sln` to open in Visual Studio.
3.  **Build & Run:**
    Press `F5` to start the game.

## Project Structure

```
SpaceWar/
├── Resources/       # Images and Sound assets
├── enemy/           # Enemy AI and logic classes
├── bullet/          # Projectile physics
├── settings/        # Game configuration & Key mapping
├── CollisionDetector.cs  # Physics engine logic
└── Game.cs          # Main game loop
```

## Documentation

For detailed architecture and class diagrams, you can view the full project documentation:
[View Documentation (PDF)](https://github.com/aergen29/SpaceWar/blob/master/documentation.pdf)

## Author

**Abdullah Ergen**
* GitHub: [@aergen29](https://github.com/aergen29)
* Email: abdullahergeni@yandex.com

## License

This project is open-source and available under the MIT License.
