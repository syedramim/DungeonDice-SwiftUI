# Dungeon Dice

A SwiftUI project that simulates dice rolls with different sided dice (d4, d6, d8, d10, d12, d20, d50, d100). Inspired by classic tabletop RPGs like Dungeons & Dragons, this app lets you quickly generate random dice rolls, all within a simple and user-friendly interface.

---

## Table of Contents
1. [Overview](#overview)
2. [Features](#features)
3. [Code Structure](#code-structure)
4. [Screenshots (Optional)](#screenshots-optional)
5. [How to Run](#how-to-run)
6. [Credits](#credits)
7. [License](#license)

---

## Overview

- **Name**: Dungeon Dice  
- **Type**: SwiftUI iOS App  
- **Purpose**: Provide a quick and easy way to roll various dice sizes for games, simulations, or fun.  

Dungeon Dice uses SwiftUI’s `LazyVGrid` layout to adapt button placement based on available screen width. When the user taps a button for a specific dice size, the app randomly generates and displays a result.

---

## Features

1. **Multiple Dice Sizes**: Roll dice with 4, 6, 8, 10, 12, 20, 50, or 100 sides.  
2. **Responsive Layout**: Buttons auto-adjust for different screen sizes using SwiftUI’s adaptive grid.  
3. **Simple UI**: Minimalistic design with large, clear buttons and results.  
4. **SwiftUI Basics**: Demonstrates `@State`, `@Binding`, and a custom layout approach to handle dynamic content.  

---

## Code Structure


**Key Components**:  
- `ContentView`:  
  - Displays the main title (“Dungeon Dice”)  
  - Shows the rolled result (`resultMessage`)  
  - Contains a child view (`ButtonLayout`) that handles all dice buttons  

- `ButtonLayout`:  
  - Defines dice options using an enum `Dice` with various cases (4, 6, 8, etc.)  
  - Uses a `LazyVGrid` to lay out the dice buttons, adapting based on screen width  
  - When a button is tapped, `resultMessage` is updated with the roll result  

---

## How to Run

1. **Clone or Download** this repository.  
2. Open the project in **Xcode (Version 12 or later)**.  
3. Select an iOS Simulator or a connected iPhone, then **Run** the project.  
4. Enjoy rolling dice of various sizes in the Dungeon Dice app.

---

## Credits

- **SwiftUI Course Reference**:  
  - [YouTube Playlist by Your Professor](https://www.youtube.com/playlist?list=PL9VJ9OpT-IPSM6dFSwQCIl409gNBsqKTe)  
    - Some concepts in this project are based on the demonstrations and teachings from these videos.

- **Author**:  
  - Your Name (Syed or any other name you’d like to display)

---

## License

This project is released under the [MIT License](https://opensource.org/licenses/MIT). Feel free to use and modify the code for personal or commercial projects.

