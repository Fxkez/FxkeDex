# ⚡ FxkeDex
### *A refined fork of Dex++ Explorer.*

---

## ✨ Overview
FxkeDex is a modernized fork of the original Dex++ Explorer, redesigned with a focus on:
- 🧭 Cleaner navigation & UI flow
- ⚡ Faster exploration performance
- 🧠 Improved object inspection tools
- 🧩 Expanded developer utilities
- 🎯 More modular architecture

---

## 🧠 Features

### 🔍 Explorer Core
- Hierarchical instance tree browsing
- Real-time object inspection
- Smart property viewer

### 🧰 Developer Tools
- Remote/event monitoring utilities (RemoteSpy)
- Console output viewer
- **Script Sandbox** safe-eval Luau console with capability gating, persistent top-level environment, and live output
- **Environment Inspector** browse the executor's globals, services, and hooks; see which executor functions are available in your runtime
- **Command Palette** Ctrl+P fuzzy command launcher with recent history and built-in shortcuts for every app

### ⚙ Performance
- Reduced UI overhead
- Faster tree rendering
- Optimized update cycles

---

## 📸 Preview

### Explorer
![Explorer](/Images/explorer.png)

### RemoteSpy
![RemoteSpy](/Images/remotespy.png)

### Command Palette
![Command Palette](/Images/commandpalette.png)

### Script Sandbox
![Script Sandbox](/Images/scriptsandbox.png)

### Environment Inspector
![Environment Inspector](/Images/envinspector.png)

### Call Stack and Trace Viewer
![CallStack](/Images/callstack.png)

---

## 🧩 The Script
```lua
loadstring(game:HttpGet(""))()
```

---

## 🛠 Roadmap
- [ ] Plugin system for tools
- [x] Theme customization system
- [x] Script executor sandbox console (safe eval environment)
- [x] Runtime environment inspection
- [x] Command palette
- [ ] Instance relationship graph (visual node map)
- [x] Call stack / script trace viewer
- [ ] Event connection tracer (signals → connections)
- [ ] Change history tracker (what changed, when, and where)
- [ ] Memory/reference inspector for instances
- [ ] Export explorer data (JSON / text dump)

---

## 💡 Notes
FxkeDex is experimental. Some features may behave differently depending on runtime environment or game structure.

---

## 🤝 Credits
Original Dex++ Explorer:
https://github.com/AZYsGithub/DexPlusPlus/

All additional modifications and improvements by FxkeDex contributors.
