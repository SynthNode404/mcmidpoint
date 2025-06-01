# Minecraft Midpoint Calculator

This is a simple web-based tool to calculate the midpoint between two sets of Minecraft coordinates. Useful when building symmetrical structures or teleporting to the center between two points.

## 🌐 Live Demo
Hosted on GitHub Pages to use it in your browser with a UI. Input coordinates, and it will generate the midpoint and a `/tp` teleport command.

## 🔧 Features
- Input up to two sets of coordinates (X1, Y1, Z1 and X2, Y2, Z2)
- Leave fields blank to ignore specific axes (uses `~` in the command)
- Rounds coordinates to the nearest whole block
- Shows if the midpoint was uneven (i.e., ended in .5, adds +1 block)
- Generates a Minecraft Bedrock-compatible `/tp` command

## 🖥️ Usage
1. Open `index.html` in a browser OR upload to GitHub Pages
2. Enter the coordinates (or leave blank for skipped axes)
3. Click **Calculate Midpoint**
4. Copy the generated `/tp` command and paste it in Minecraft

## 📁 Example
**Input:**
- X1: 10, Y1: 64, Z1: 20
- X2: 31, Y2: 64, Z2: 42

**Output:**
```
Midpoint:
X: 21 (+1 block added)
Y: 64
Z: 31 (+1 block added)

Teleport Command:
/tp @s 21 64 31
```

## 🚀 Forking and Deployment on GitHub Pages
1. Fork the project to a GitHub repository
2. Go to **Settings > Pages**
3. Set the source to your `main` branch and root folder
4. Access your calculator at `https://your-username.github.io/your-repo/`

All rights reserved. You may:
- Use this project for personal or educational purposes
- Share or adapt it with **credit to the original author (Braxton)**

You **may not**:
- Claim the original code as your own
- Reupload or redistribute without providing credit

✅ If you heavily modify the project and make it your own, you may remove credit, but please mention it was based on this project.
---
