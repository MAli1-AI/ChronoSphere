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

---

## 🎥 Demo Overview
The following screenshots demonstrate ChronoSphere’s complete workflow, from the main dashboard to advanced utilities such as world clock management, prayer times, task and event tracking, smart alarms, and time utilities.  
Each section follows the same order as the application’s menu flow for clarity.
Below are screenshots demonstrating the complete workflow and features of **ChronoSphere**.

### 🏠 Dashboard & Main Menu
- [Dashboard](screenshots/dashboard.jpg)
- [Main Menu](screenshots/main_menu.jpg)

---

### 🌍 World Clock
- [World Clock Menu](screenshots/world_clock/world_clock_menu.jpg)
- [Cities List](screenshots/world_clock/cities.jpg)
- [Custom City](screenshots/world_clock/custom_city.jpg)
- [Add City](screenshots/world_clock/adding_cities.jpg)
- [Delete City](screenshots/world_clock/deleting_cities.jpg)
- [Live Time Updates](screenshots/world_clock/live_times.jpg)

---

### 🕌 Prayer Times
- [Prayer Time Menu](screenshots/prayer_time/main_prayer_time_menu.jpg)
- [Prayer Times Example](screenshots/prayer_time/prayer_times_ex1.jpg)

---

### 📋 Tasks & Events Manager
- [Tasks & Events Main Menu](screenshots/tasks_events/main_menu_of_events_and_tasks.jpg)

**Tasks**
- [Task Manager Menu](screenshots/tasks_events/tasks_manager_menu.jpg)
- [Add Task](screenshots/tasks_events/adding_tasks.jpg)
- [View Tasks](screenshots/tasks_events/viewing_tasks.jpg)
- [Completed Tasks](screenshots/tasks_events/completed_tasks.jpg)

**Events**
- [Add Event](screenshots/tasks_events/adding_events.jpg)
- [View Events](screenshots/tasks_events/viewing_events.jpg)

**Records**
- [Tasks & Events Record](screenshots/tasks_events/tasks_and_events_manager_record.jpg)

---

### ⏰ Smart Alarms
- [Alarm Menu](screenshots/smart_alarm/alarms_menu.jpg)
- [Add Alarm](screenshots/smart_alarm/adding_alarms.jpg)
- [Alarm Status](screenshots/smart_alarm/alarms_status.jpg)
- [Alarm Ringing](screenshots/smart_alarm/alarms_ringing.jpg)
- [Missed Alarms](screenshots/smart_alarm/alarms_missed.jpg)
- [Delete Alarm](screenshots/smart_alarm/deleting_alarms.jpg)

---

### 🛠 Utilities
- [Utilities Menu](screenshots/utilities/utility_menu.jpg)
- [Stopwatch](screenshots/utilities/stopwatch.jpg)
- [Timer](screenshots/utilities/timer.jpg)


---

Author
[**Mohammad Ali Mughal**]

License
This project is for educational purposes.
MIT License