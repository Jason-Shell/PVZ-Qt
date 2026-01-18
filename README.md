# PVZ-Qt: Plants vs. Zombies Game Clone

## 🎓 Internship Project Overview

This project is a recreation of the popular tower defense game "Plants vs. Zombies" using C++ and the Qt framework. It was developed as part of a university C/C++ programming course to demonstrate advanced object-oriented programming concepts, GUI development, and software engineering practices.

## 📋 Project Description

PVZ-Qt is a tower defense game implementation that replicates the core gameplay mechanics of Plants vs. Zombies. Players strategically place plants to defend against waves of zombies trying to reach their house. This project serves as a comprehensive learning exercise in game development, event-driven programming, and cross-platform application design.

## 🎯 Learning Objectives

Through this internship project, the following skills and concepts were developed:

- **Object-Oriented Programming**: Implementing complex class hierarchies for game entities (plants, zombies, projectiles)
- **GUI Development**: Creating interactive user interfaces using Qt Framework
- **Event-Driven Architecture**: Managing game state, user input, and real-time updates
- **Memory Management**: Proper use of pointers, dynamic allocation, and resource cleanup in C++
- **Design Patterns**: Applying factory, observer, and state patterns in game development
- **Cross-Platform Development**: Building applications that run on multiple operating systems
- **Version Control**: Using Git and GitHub for project management and collaboration

## 🛠️ Technology Stack

- **Language**: C++11/14/17
- **Framework**: Qt 5.x/6.x
- **Build System**: qmake or CMake
- **IDE**: Qt Creator (recommended)
- **Version Control**: Git

## ✨ Key Features

- **Classic Gameplay**: Authentic Plants vs. Zombies tower defense mechanics
- **Multiple Plant Types**: Various defensive plants with unique abilities
- **Zombie Waves**: Progressive difficulty with different zombie types
- **Resource Management**: Sun collection and strategic spending system
- **Intuitive UI**: User-friendly interface built with Qt Widgets/QML
- **Animation System**: Smooth sprite animations and visual effects
- **Sound Effects**: Audio feedback for game events (if implemented)
- **Level Progression**: Multiple levels with increasing difficulty

## 📦 Installation & Setup

### Prerequisites

- **C++ Compiler**: GCC 7+, Clang 6+, or MSVC 2017+
- **Qt Framework**: Qt 5.12+ or Qt 6.x
- **CMake**: Version 3.16+ (if using CMake build)
- **Git**: For cloning the repository

### Building the Project

#### Option 1: Using Qt Creator (Recommended)

1. Clone the repository:
   ```bash
   git clone https://github.com/Jason-Shell/PVZ-Qt.git
   cd PVZ-Qt
   ```

2. Open Qt Creator and select "Open Project"

3. Navigate to the project directory and open the `.pro` file (qmake) or `CMakeLists.txt` (CMake)

4. Configure the project with your Qt kit

5. Build and run the project using the play button (Ctrl+R)

#### Option 2: Command Line Build

**Using qmake:**
```bash
git clone https://github.com/Jason-Shell/PVZ-Qt.git
cd PVZ-Qt
qmake PVZ-Qt.pro
make
./PVZ-Qt
```

**Using CMake:**
```bash
git clone https://github.com/Jason-Shell/PVZ-Qt.git
cd PVZ-Qt
mkdir build && cd build
cmake ..
make
./PVZ-Qt
```

## 🎮 How to Play

1. **Start the Game**: Launch the application and click "Start Game"
2. **Collect Sun**: Suns fall from the sky - click them to collect resources
3. **Plant Defenders**: Select plants from the menu and place them on the lawn
4. **Defend Your House**: Stop zombies from reaching the left side of the screen
5. **Strategy**: Choose the right plants for different zombie types
6. **Win Condition**: Survive all zombie waves to complete the level

## 📁 Project Structure

```
PVZ-Qt/
├── src/                    # Source code files
│   ├── main.cpp           # Application entry point
│   ├── game/              # Game logic and mechanics
│   ├── entities/          # Plant and zombie classes
│   ├── ui/                # User interface components
│   └── utils/             # Helper functions and utilities
├── include/               # Header files
├── resources/             # Game assets
│   ├── images/           # Sprites and graphics
│   ├── sounds/           # Audio files
│   └── data/             # Game configuration files
├── tests/                 # Unit tests (if applicable)
├── docs/                  # Documentation
├── CMakeLists.txt        # CMake build configuration
├── PVZ-Qt.pro            # qmake project file
└── README.md             # This file
```

## 🔧 Development Process

### Design Phase
- Analyzed original game mechanics and user experience
- Created UML diagrams for class structures
- Designed the game loop and state management system

### Implementation Phase
- Developed core game entities using OOP principles
- Implemented Qt-based GUI with event handling
- Created animation system for smooth gameplay
- Integrated resource management and game logic

### Testing Phase
- Performed unit testing on core components
- Conducted gameplay testing for balance and bugs
- Optimized performance for smooth frame rates

### Documentation
- Wrote inline code documentation
- Created user guide and developer notes
- Documented build and deployment processes

## 📚 Key Concepts Demonstrated

1. **Inheritance & Polymorphism**: Base classes for plants and zombies with specialized derived classes
2. **Encapsulation**: Private data members with public interfaces
3. **Qt Signal-Slot Mechanism**: Event handling and inter-object communication
4. **Scene Management**: Using Qt's graphics view framework for game rendering
5. **Timer-Based Game Loop**: QTimer for consistent game updates
6. **Resource Management**: RAII principles and smart pointers
7. **Collision Detection**: Checking interactions between game entities

## 🎓 Learning Outcomes

By completing this internship project, I have:

- ✅ Gained proficiency in C++ programming and modern C++ features
- ✅ Mastered Qt framework for cross-platform application development
- ✅ Understood game development fundamentals and game loop architecture
- ✅ Applied object-oriented design principles to complex systems
- ✅ Developed debugging and problem-solving skills
- ✅ Learned to structure large codebases for maintainability
- ✅ Enhanced version control and collaborative development skills

## 🚀 Future Enhancements

- [ ] Add more plant and zombie varieties
- [ ] Implement additional game modes (survival, puzzle)
- [ ] Create level editor for custom stages
- [ ] Add multiplayer functionality
- [ ] Improve graphics with modern Qt Quick/QML
- [ ] Implement achievement system
- [ ] Add localization support for multiple languages

## 🤝 Contributing

This is an educational project, but suggestions and improvements are welcome! Please feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is created for educational purposes. The original Plants vs. Zombies game is owned by PopCap Games/EA. This project is not affiliated with or endorsed by the original creators.

## 👨‍💻 Author

**Jason Shell**
- GitHub: [@Jason-Shell](https://github.com/Jason-Shell)
- Email: abovethestarryheavens@outlook.com

## 🙏 Acknowledgments

- **Course Instructor**: For guidance and support throughout the project
- **Qt Documentation**: Comprehensive framework documentation and examples
- **PopCap Games**: For the original Plants vs. Zombies game design
- **University C/C++ Course**: For providing the learning opportunity
- **Open Source Community**: For tutorials, resources, and inspiration

## 📞 Contact

For questions, suggestions, or internship opportunities, please reach out via:
- Email: abovethestarryheavens@outlook.com
- GitHub Issues: [Create an issue](https://github.com/Jason-Shell/PVZ-Qt/issues)

---

**Note**: This project is part of an academic curriculum and demonstrates skills in C++ programming, Qt framework, game development, and software engineering practices. It represents a comprehensive learning experience in object-oriented programming and application development.
