# 🔍 OmegleHappy v3.0

## 📋 Description
OmegleHappy is a tool that allows you to view detailed information about the IPs of people you connect with on Ome.tv, including their location, time zone, and more.

## 🚀 Features
- 🌍 Shows detailed information of the connected user's IP
- 📍 Displays country, city and time zone
- 📜 History of the last 10 connections
- 🙈 Option to censor IP
- 🖱️ Draggable window
- 🔄 Real-time updates

## 💻 How to Use
1. Go to [Ome.tv](https://ome.tv)
2. Open Developer Tools (F12 or right click -> Inspect)
3. Go to 'Console' tab
4. Copy and paste the following code:
```javascript
fetch("https://raw.githubusercontent.com/JollyJolli/omeglehappy/refs/heads/main/codigo.txt")
    .then(res => res.text())
    .then(code => eval(code));
```

## 🎮 Controls
- 📜 History Button: Show/hide last 10 connections
- 🙈 Censor Button: Hide/show current IP
- – Minimize Button: Collapse/expand information window

## ⚠️ Notes
- The tool only works while you keep the Ome.tv page open
- History is saved locally in your browser
- Use this tool responsibly and ethically

## 👨‍💻 Created by
Made with 💻 by Jolly