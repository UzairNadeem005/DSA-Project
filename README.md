# ⚡ Tower Defence Game  

A strategic and engaging **tower defence game** built using **C++ and Data Structures**.  
Designed with dynamic gameplay and smooth logic, this project demonstrates the use of **OOP**, linked lists, vectors, and priority queues in a real-time defence environment.  

---
## ✨ Project Report  
**Course Code:** CT-159  
**Course Instructors:** Miss Samia Masood Awan and Miss Sahar  

**Group Members:**  
✔ Muhammad Taqi (Group Lead) — CT-24027  
✔ Uzair Nadeem  - CT-24037  
✔ Muhammad Abdullah — CT-24026   
✔ Muhammad Ibtissam Aslam — CT-24020  

---

## ✨ Project Description  
This is a Tower Defence game where the player defends their tower against waves of enemy units.

The game features:  
• Player and enemy towers with health and attack logic  
• Units (Knight, Archer, Giant, Wizard) spawning for both sides  
• A freeze ability to temporarily stop enemy units  
• Wave-based enemy progression  
• Elixir-based unit spawning for the player  
• A 2-minute game timer  
• Graphical representation using shapes and colors  

The game combines strategy, resource management, and real-time action.

---

## ✨ Data Structures Used  

### **a) Classes**  
Classes form the backbone of this game’s design, encapsulating attributes and behaviors for different entities.

**Tower**  
Manages position, health, damage, attack rate, and target selection.

**Unit**  
Represents Knights, Archers, Giants, and Wizards. Handles movement, health, damage, and freeze effects.

**Projectile**  
Tracks ranged attacks and visuals, storing start/end positions, color, and progress.

**GameWave**  
Manages enemy wave composition, spawn rates, cooldowns, and wave linking.

---

### **b) Linked List**  
Used to manage dynamic collections of units and waves.  
Efficient insertion and deletion without shifting elements.  
Supports smooth wave transitions and scalable enemy progression.

---

### **c) Vectors**  
Store projectiles and wave unit configurations.  
Allow dynamic resizing, fast iteration, and easy access.

---

### **d) Priority Queue**  
Used by towers to select targets based on proximity or priority.  
Provides efficient targeting without scanning the entire battlefield.

---

## ✨ Summary  
The Tower Defence game demonstrates the effective use of multiple data structures for 
gameplay. Classes provide design for towers, units, projectiles, and game logic, while linked 
lists efficiently handle dynamic unit management. Vectors store projectiles and wave 
templates for easy iteration, and priority queues ensure optimal targeting by towers. 
Constants, primitive variables, and strings support game state tracking, visual 
representation, and UI messages. Overall, the project integrates strategy, resource 
management, and object-oriented design to create a responsive and scalable game system.
