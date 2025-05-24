---
layout: post
title: SER316 Group Project
tags: [academics, java, json, scrum, github, agile]
---

## 📚 Topics for the class include:
- Scrum as Agile Development methodology
- Software change management and source code control (Git/GitHub)
- Continuous Integration and Testing
- Unit Testing
- Code Reviews
- Design Patterns
- Refactoring
- Static and Dynamic Analysis
- Metrics and Measurements

This class focused on using Github and scrum. We had a group project that ran for the majority of the semester. The task was taking a legauy code base (~25k lines of code) and Refactoring it. The original code was an agenda system and we turned it into a gym membership scheduling system. It was a team of 7 people with varries level in skill. Some knew how to use git/github and others were just starting out. We used Tiaga as our task board and we had a scrum master and Git master that rotated every sprint. We had sprint planning meeting standups and retrospective meetings. We used checkstyle, spotbugs and unit test for measureing and testing the quality of our code.

## 💡 Project Features

We added support for:
- **4 available rooms** where classes can take place.
- **Public and private classes**, with public classes labeled as **beginner** or **advanced**.
- **Rank-based rules** for both trainers and students:
  - Students need at least a **blue belt** to join advanced public classes.
  - Trainers must be at least **black2 rank** to teach advanced classes.
  - In private classes, trainers can teach any student below their own rank.
- A **belt ranking system**, which includes:  
  white, yellow, orange, purple, blue, blue stripe, green, green stripe, brown1, brown2, brown3, black1, black2, black3.

Other functionality included:
- Students can **sign up for classes** (with a 20 student limit),
- Users can **view their schedule** and **see classes they’re eligible for**,
- Trainers can **set their availability** and are only assigned to classes that match it,
- Gym owners can **add/edit trainers and students**, and manage classes based on room and trainer availability,
- Each user can **view personal training notes**.

## 👩‍💻 My Contributions

On my side, I handled a mix of frontend, backend, and codebase improvements:

### 🧩 Legacy Code Understanding
- Created a **UML diagram** to better understand the structure of the legacy code.
- Added **comments** throughout the existing code to improve readability and help our team navigate it.

### 💻 Frontend Work
- Built a new **UI panel for student notes**.
- Created the **Gym Class UI Dialog** to simplify creating and viewing class info.
- Designed the **Login UI Dialog** to create role based access.

### 🔙 Backend Logic
- Developed the **backend for adding new gym classes**, including checks for room and trainer availability.
- Implemented the backend logic for the **belt and rank system**, which powers the rules for student and trainer eligibility.

### ✅ Code Reviews
- Participated in several **code reviews**, helping ensure quality and consistency across the project.

---

This project was a great opportunity to work with a legacy codebase, practice team collaboration, and learn how to integrate frontend and backend logic in a meaningful system. Even though it was a class project, it gave us a taste of what it’s like to work on a real software product—with user requirements, rules, and technical constraints.

