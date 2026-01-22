# ChronoSphere 🌍⏰

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue.svg)

**A Java-based console application providing global time insights and smart utility features for time management**


## Features
- 🌍 **World Clock System** - Track time across multiple cities globally
- 🕌 **Prayer Times (Pakistan)** - Accurate prayer timings for major Pakistani cities
- 📅 **Calendar & Task Planner** - Manage your schedule , tasks and events
- ⏰ **Alarm System** - Set and manage alarms with status tracking
- ⏱️ **Utilities** - Stopwatch and Timer functions
- 🎨 **Colorful Console Interface** - ANSI-colored terminal UI

---

## Project Structure

ChronoSphere/
├── ChronoSphere.java       # Main application file
├── data/                   # Data storage directory
│   ├── WorldClock.txt      # Saved world clock cities
│   ├── PrayerTimesPAK.csv  # Prayer time database
│   ├── TasksManager.txt    # Task storage
│   ├── Events.txt          # Event storage
│   └── Alarm.txt           # Alarm storage
├── .gitignore
└── README.md

---

## Modules
1. **World Clock** – Allows users to add or delete cities and view their current local times. Supports multiple time zones and provides a global perspective on time management.
2. **Prayer Times** – Provides accurate prayer timings for major cities in Pakistan. Includes live countdowns to the next prayer, helping users stay organized with religious schedules.
3. **Calendar, Tasks & Events** – Enables task and event management with file-based persistence. Users can create, update, and track tasks or events, ensuring nothing is missed in their schedule.
4. **Alarms** – Lets users set multiple alarms with status tracking and notifications. Alarms can be customized and are persistent between program runs.
5. **Utilities** – Includes stopwatch and timer functions. Useful for tracking time intervals or setting temporary countdowns for productivity or daily routines.

---

## How to Run
1. Ensure you have Java JDK installed (version 8 or higher)
2. Compile the program:
   ```bash
   javac ChronoSphere.java
3. Run the application:
   java ChronoSphere

---

## Requirements
- Java Runtime Environment (JRE) 8+
- Terminal supporting ANSI colors
- Windows, Linux, or macOS

---

## Data Files
All user data is stored in the data/ directory:

- Persistent storage of cities, alarms, tasks, and events
- CSV format for prayer times
- Text files for simple data storage
---

## Notes / Tips
- 💻 *Recommended Terminal:* Run the application in *VS Code Terminal* (or any terminal that supports ANSI colors). The default Windows CMD may not display colors properly.  
- 🗂️ *File Paths:* All data files are referenced using absolute paths. To run the application successfully, update the file paths in the code to match your local system. For example:  
  ```java
  "C:\\Users\\User\\OneDrive\\Desktop\\ChronoSphere\\data\\WorldClock.txt"
Make sure to adjust the path in all 7–8 locations where files are referenced. Once these paths are correctly set, the program will work as intended.
✅ Following these steps ensures that all modules (World Clock, Prayer Times, Calendar, Alarms, Utilities) function correctly.




Author
[**Mohammad Ali Mughal**]

License
This project is for educational purposes.
MIT License