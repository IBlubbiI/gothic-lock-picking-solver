# Gothic Remake – Lock Picking Solver

Thanks for checking out this tool! 🏰

---

## About

Gothic Remake's lock picking minigame requires you to move 6 bolts to a specific position. The tricky part: bolts are often connected to each other and will shift when you move another one, which makes it easy to lose track of what you're doing. This tool calculates the optimal move sequence for any chest automatically.

Enter each bolt's starting position and how the bolts are connected, and it tells you exactly what to press, step by step.

**What it does:**
- Visual bolt position display with a 7-hole indicator per bolt
- Connection matrix for all relationship types you'll encounter in the game (none / opposite direction / same direction)
- Two solving modes: minimum moves (BFS – minimises the raw number of bolt presses) and minimum keystrokes (Dijkstra – recommended, as it's more intuitive and optimised for actual gameplay)
- Step-by-step solution table showing exactly which bolt to press and which key to use

---

## Installation & Usage

The tool runs as a single HTML file directly in your browser – nothing to install.

**Step 1 – Open the file**
Download `index.html` and double-click it. It will open automatically in your browser (Chrome, Firefox, Edge – any browser works).

**Step 2 – Enter starting positions**
Look at the lock in the game and note which hole (1–7) each of the 6 bolts is currently sitting in. Use the ◀ ▶ buttons to enter them. The middle hole (4) is always the goal and is highlighted in green.

**Step 3 – Configure connections**
Some bolts move other bolts when pressed – you can see this in the game when you move a bolt. Click the cells in the connection matrix to set the relationship type. Each click cycles through the three options:
- **–** no connection
- **≠** the connected bolt moves in the opposite direction
- **=** the connected bolt moves in the same direction

*(Row = the bolt you're moving, column = the bolt that gets affected)*

**Step 4 – Find the solution**
Choose a mode – **Min. keystrokes** is recommended – and click **Find solution**. The tool will output a table with the best solution.

---

Hope this makes the lock picking a little less frustrating! ⚔️

If you'd like to support this project, I'd really appreciate a coffee:
https://ko-fi.com/iblubbii – thank you! ☕

---

## License

MIT
