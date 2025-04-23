# University Timetable Scheduling with Genetic Algorithms

This project presents an AI-based solution to the **University Timetable Scheduling Problem (UTSP)**, an NP-hard optimization challenge. Using **Genetic Algorithms (GA)**, this system automates the creation of efficient, clash-free timetables for universities by respecting both hard and soft constraints such as room capacity, professor availability, and time slot distribution.

---



## 🎯 Project Goals

- Efficiently allocate classrooms, professors, and time slots.
- Avoid scheduling conflicts (professors, rooms, overlapping classes).
- Maximize utilization of available resources.
- Adhere to real-world constraints found in university scheduling.



## 🧠 Learnings & Results

### 🤖 Artificial Intelligence
- Applied **Genetic Algorithms** to solve complex NP-hard problems.
- Encoded **chromosomes** to represent timetable data:
  - Room assignment
  - Course-to-slot allocation
  - Professor schedules
- Designed a **fitness function** to:
  - Minimize clashes
  - Maximize resource usage efficiency

### 📐 Constraint Handling
- **Hard Constraints**:
  - No overlapping classes for the same professor
  - No room double-bookings
  - Adherence to room capacity
- **Soft Constraints**:
  - Minimize professor idle time
  - Reduce room switching between lectures
  - Optimize long teaching blocks

### 🔬 Algorithm Design
- Implemented:
  - **Selection** (e.g., tournament, roulette wheel)
  - **Crossover** (e.g., one-point, two-point)
  - **Mutation** operations
- Iteratively improved the population using generational evolution

### 📈 Optimization Achievements
- Reduced timetable conflicts by **80%**
- Successfully scheduled:
  - 20 Courses
  - 10 Sections
  - Multiple Professors
- Fully adhered to university scheduling constraints



## 🧩 Technologies Used

- **Language**: Python
- **Platform**: Jupyter Notebook




## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/mujtaba510/University-Timetable-Scheduling-with-Genetic-Algorithms.git


