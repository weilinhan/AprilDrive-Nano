# AprilDrive-Nano
An intelligent autonomous vehicle featuring automatic path planning and cruising, utilizing the RRT algorithm and Voronoi diagrams.

# 🚀 Project Overview

This project showcases the development of an **AI-driven JetBot** powered by the **NVIDIA Jetson Nano**. The JetBot is designed to perform **autonomous navigation, object detection, obstacle avoidance, and object sorting** in dynamic environments. The project integrates advanced algorithms such as **RRT (Rapidly-Exploring Random Tree)** and **Voronoi diagrams** for efficient path planning and decision-making.

## 🗂️ Task Summary

### 1. Task 1: Mapping
The JetBot autonomously explores the arena without touching any objects, detects and identifies the position and color of various objects (spheres and colored cubes), and creates a **2D map** with the objects’ coordinates. After completing the mapping, the JetBot must return to the **Start-Goal Base**.

### 2. Task 2: Obstacle Course
Based on the input positions of **three red and three blue cubes**, the JetBot calculates an optimal trajectory within a limited time frame. It must **circumnavigate the red cubes clockwise** and the **blue cubes counterclockwise**, while avoiding **unknown wooden spheres** placed in the arena. The JetBot must complete the course and return to the **Start-Goal Base** without colliding with any objects.

### 3. Task 3: Object Sorting
The JetBot detects and identifies **colored cubes** randomly distributed in the arena. It must **push each cube to its corresponding color base** and place it correctly. Full points are awarded if the cube is entirely within the designated base’s circle, partial points if it's correctly placed but outside the circle, and no points for misplaced or unsorted cubes. The JetBot must return to the **Start-Goal Base** after sorting all objects.

---

## 🎯 Key Features
- **Autonomous Navigation & Path Planning** (RRT, Voronoi diagrams)  
- **Real-time Object Detection & Classification**  
- **Dynamic Obstacle Avoidance**  
- **Precise Object Sorting Mechanism**
