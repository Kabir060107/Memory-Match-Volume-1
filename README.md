Project Overview

Team Name: Ballerina Cappuccina

This is a C++ implementation of the classic Memory Match Game (Concentration) using STL containers and modern C++ features. The game challenges players to find matching pairs of cards on a grid by remembering their positions.

STL Library Usage

This project extensively utilizes the C++ Standard Template Library (STL) for efficient data management and operations:

Containers

std::vector → Dynamic storage of cards and game state
std::pair → Managing card pairs and coordinates
std::map → Configuration and score tracking
std::unordered_map → Fast lookup for card matching
Algorithms

std::shuffle → Randomizing card positions
std::sort → Sorting leaderboard scores
std::find → Checking for valid card selections
Utilities

std::chrono → Tracking game time
std::thread → (Future: Delayed card flip animations)
std::function → (Future: Callbacks for game events)
Key Features of the Game Engine

1. Core Game Logic (Kartik)

Card matching mechanics
Turn-based gameplay
Win/loss condition checks
STL-based game state management
2. Input/Output & User Interaction (Madhav)

Terminal-based card selection
Input validation to prevent crashes
Smooth UI flow for gameplay
3. Console UI Design (Aryaveer)

Visually appealing card layouts
Text-based animations (flipping, delays)
Clear screen transitions
4. Score Tracking & Documentation (Kabir)

Move counter
Accuracy tracking
Scoreboard using STL containers
In-code comments & user guide
5. Overall Architecture & Integration (Aryan)

Class structure design
Logic-UI coordination
Final demo & presentation
Development Team

Team Member	Role	Key Contributions
Aryan	Team Lead	Game architecture, UI-logic integration, final demo
Kartik	Game Logic Developer	Card matching, STL-based game state, win/lose conditions
Madhav	I/O & User Interaction	Input handling, console display, UX optimization
Aryaveer	UI Designer & Tester	Card visuals, animations, bug testing
Kabir	Documentation & Score Tracker	Score system, comments, user guide
How to Build & Run

Requirements

C++17 compatible compiler (GCC, Clang, MSVC)
CMake (optional)
Build & Run

bash
g++ -std=c++17 main.cpp -o memory_game  
./memory_game  
Future Enhancements

✅ Graphical UI (if time permits)
✅ Multiplayer mode (hotseat or network)
✅ Sound effects & advanced animations

License

This project is open-source under the MIT License.

Special Thanks

✨ Ballerina Cappuccina team for their hard work!
🚀 Mentors and hackathon organizers for guidance.

Happy Matching! 🎮🃏
