# FRC Pre-match Checklist

A dynamic, interactive robot pre-match checklist for FRC teams — built with HTML, CSS, and JavaScript.

### 🛠 Created by Wilson Chen, Team 5924

## 🔍 Overview

This web-based checklist tool helps FRC drive teams perform thorough pre-match inspections of the robot and driver station before each match. It guides users through grouped checklist items one at a time, tracks progress, and prompts for battery information at the end.

Designed for use on tablets, laptops, or pit computers — no backend or internet connection needed after initial load.

---

## 🚀 Features

- ✅ Grouped checklist by subsystem (e.g., Drive, Electrical, Climber, etc.)
- 📊 Real-time progress bar and percentage indicator
- 📋 Smooth transitions as items are checked off
- 🔄 Back and Next buttons to navigate between items
- 🔢 Battery number prompt after checklist completion
- 📄 Summary screen showing progress, battery used, and any unchecked items

## 💻 Usage

- To use on tablet or iphone, download an HTML reader and paste the HTML code into the reader.
- To use on computer, it's best to use jsfiddle.net or CodePen.io. Opening about:blank and modifying the page with inspect doesn't work because the font's can't be imported
- To update checklist items, just update the ```checklistGroups``` object and items within it.
