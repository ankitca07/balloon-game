---

**Development Process:**

1. **Game Objective:**
   - Develop an interactive game where balloons inflate from a pump, float leftwards in a zig-zag motion, and burst upon mouse click or collision.

2. **Technologies Used:**
   - HTML5
   - CSS3 (Animations)
   - JavaScript (Game Logic & Collision Detection)

3. **Steps Followed:**
   - **Basic Layout:**
     - Created the pump structure (tank, handle, pipe) using positioned PNG assets.
   - **Balloon Generation:**
     - Programmed balloon inflation animation using `@keyframes` in CSS.
     - Balloons inflate from a small size to large (realistic effect) and float in zig-zag motion using custom animations.
   - **User Controls:**
     - Integrated mouse click and `Enter` keypress to trigger pump action and inflate a new balloon.
   - **Collision Detection:**
     - Implemented bounding box collision detection. Balloons burst when they collide or are clicked.
   - **Enhancements:**
     - Increased handle movement 3-4 times before inflating.
     - Fine-tuned balloon removal delay and realistic scale growth.
     - Adjusted the position and randomization logic for balloon placement.
   - **Responsive Design:**
     - Ensured the game scales well on various screen sizes.
  
4. **Challenges Faced & Solutions:**
   - Achieving smooth animation synchronization between pump handle and balloon inflation.
   - Fine-tuning collision logic to prevent false positives.

---
