# Bottle of Water

## Overview
Bottle of Water is a lightweight, single‑page web app to track your daily water intake. It features a delightful animated bottle that fills up as you log drinks, a progress ring, quick‑add buttons, custom amounts, undo/reset, a daily goal, optional hydration reminders, dark/light theme, and a simple intake log with export.

Everything runs locally in your browser and persists using localStorage.

## Setup
- No build steps required.
- Download the repository or save the provided index.html file.
- Open index.html in any modern browser (Chrome, Edge, Firefox, Safari).

Permissions:
- If you enable reminders, the app may request notification permission to show native notifications. In‑app nudges still work without permission.

## Usage
- Set your daily goal: enter a value in “Daily goal (ml)” and click “Save goal”. Default is 2000 ml.
- Add water:
  - Quick add buttons: +50, +100, +250, +500 ml.
  - Custom amount: enter an amount and click Add.
  - Hotkeys: 1 = +50, 2 = +100, 3 = +250, 4 = +500, U = Undo.
- Undo: removes the last logged drink.
- Reset: clears today’s intake and log (today only).
- Theme: toggle light/dark with the switch in the header.
- Reminders: toggle to receive hydration nudges every ~45 minutes since your last drink. If allowed, a native notification appears; otherwise an in‑app hint shows.
- Export log: downloads a JSON snapshot of today’s goal, consumption, and entries.
- Daily reset: the app automatically resets at local midnight while it’s open, or on next open.

Tips:
- The animated bottle reflects your progress; the progress ring shows percentage and updates live.
- Your data (goal, intake, log, theme, reminder setting) is stored locally in your browser.