# 🎲 Dice Game

A sleek and interactive two-player dice game built with **HTML**, **CSS**, and **JavaScript**. Roll, hold, and race to 100 in this dynamic browser-based game.

## 🚀 How to Play

1. Click **"🎲 Roll Dice"** to roll the dice.
2. If you roll anything but a 1, the number adds to your current score.
3. Rolling a 1 resets your current score and switches turns.
4. Click **"📥 Hold"** to save your current score and switch turns.
5. First to reach 100 points wins the game!
6. Click **"🔄 New Game"** to start over.

## 🔧 Features

- Two-player game with alternating turns
- Roll the dice to accumulate points
- Hold your score to avoid losing it
- First player to reach 100 points wins
- Stylish and responsive UI

## 📱 Responsive Design

The game layout has been enhanced to support a fully responsive design using media queries. This ensures an optimal experience across different screen sizes:

### 🧱 Container Adaptability
- The main container (`main`) dynamically adjusts its width from `100rem` down to `24rem` based on the viewport size (from `>1030px` to `≤340px`).

### 🔄 Layout Shift
- Layout switches from horizontal to vertical on smaller devices (`max-width: 520px`), improving usability on mobile phones.

### 🔡 Scalable Typography & Spacing
- Typography and spacing for key elements like `.score`, `.name`, and `.player` are scaled appropriately for better readability.

### 🎮 Adaptive Button Design
- Button positions (`.btn--roll`, `.btn--hold`, `.btn--new`) and sizes are adjusted to remain accessible and visually consistent on smaller screens.

### 🎲 Dice Responsiveness
- The dice’s position and size adapt to maintain visual balance across devices.

### 🌟 Visual Enhancements
- Shadows and padding are optimized for performance and aesthetics on low-resolution displays.

## 🎯 Goal
Ensure the game remains fully playable, readable, and visually appealing on desktops, tablets, and smartphones alike.
