# 📈 Growth Tracker

A personal growth and productivity tracker that helps you define your daily and weekly goals, track your consistency, and visually understand how you are growing over time.

---

## 🌟 Overview

**Growth Tracker** is a web-based personal productivity and self-improvement application designed to help users track the things they want to accomplish on a daily and weekly basis.

The core flow is simple:
$$\text{Set Goals} \longrightarrow \text{Track Progress} \longrightarrow \text{Build Consistency} \longrightarrow \text{Measure Growth}$$

Users can create goals for different areas of their lives, track their completion over days and weeks, and view a **Growth Report** that visually represents their progress and consistency over a selected period.

### Dual-Experience Design
- **Laptop & Tablet:** Use a shared responsive web interface that adapts naturally to larger screen sizes and split views.
- **Phone:** Uses a dedicated, mobile-first interface optimized specifically for smaller screens, single-handed use, and rapid touch interactions.

*The user does not need to choose which version to use—the application automatically detects the viewport/device and serves the optimized layout seamlessly under a single URL.*

---

## ✨ Core Concept

Most productivity applications focus primarily on task execution, to-do lists, reminders, and scheduling. Growth Tracker shifts the focus to **understanding personal progress over time**.

Instead of asking *"Did I complete today's task?"*, the application helps answer **"How consistently am I improving?"**

### Track Anything
* **Coding & Computer Science:** DSA practice, personal projects, system design.
* **Health & Fitness:** Exercise, hydration, meditation, sleep schedules.
* **Learning & Mindset:** Reading, language learning, skill development, course completion.
* **Daily Routines:** Habit stacking, morning routines, deep work sessions.

---

## 🎯 Main Objectives

* Allow users to define both daily and weekly goals.
* Make daily progress logging instantaneous and friction-free.
* Provide clear historical visibility into consistency.
* Calculate growth metrics using dynamic analytics.
* Render dedicated mobile vs. desktop/tablet layouts under one architecture.
* Maintain a scalable foundation capable of evolving into a full personal growth engine.

---

## 🖥️📱 Device Experience

Mobile is treated as a distinct experience rather than just a scaled-down desktop screen.

```python
                         USER
                          │
                          ▼
                    OPENS THE APP
                          │
                          ▼
               DEVICE / VIEWPORT CHECK
                          │
               ┌──────────┴──────────┐
               │                     │
               ▼                     ▼
             PHONE             LAPTOP / TABLET
               │                     │
               ▼                     ▼
           MOBILE UI               WEB UI
                                     │
                             Responsive Layout
                                     │
                             ┌───────┴───────┐
                             │               │
                             ▼               ▼
                          Laptop          Tablet
