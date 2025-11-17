#  Fun with Video Games and the First Steps of My Journey in UX Design

A C++ console program that collects information about a user’s favorite video game, evaluates how much value they got for their money, assigns a *game tier*, and summarizes everything in a nicely formatted report (both on screen and in a text file).

This project is built to practice:

- User input and validation  
- User-defined functions  
- Enumerations (`enum`)  
- Selection (`if/else`, `switch`)  
- Loops (`while`, `do-while`)  
- Console color changes  
- File I/O and formatted output with `setw`

---
# Class Information
**ITCS 2530**
**Raymond Bawal III**
**Professor Koss**
##  Features

**Intro banner with console color**  
  Uses `SetConsoleTextAttribute` (wrapped in `setConsoleColor`) to display a bright welcome banner.

**User input & validation**
  - Favorite video game (string, with spaces)
  - Favorite character (string)
  - Gaming platform (string)
  - Age (validated `int`, must be between 1 and 109)
  - Game price (`double`, must be ≥ 0)
  - Hours played (`int`, must be > 0)

 **Derived values**
  - Value per hour = `gamePrice / hoursPlayed`
  - Age difference compared to the creator’s nostalgia age (`childAge = 7`)

 **Enum-based game tier**
  ```cpp
  enum GameTier { LOW_TIER, GOOD_TIER, SUPER_TIER
---
