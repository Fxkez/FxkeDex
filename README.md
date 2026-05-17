# ⚡ [FxkeDex](https://fxke.win/dex)
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
- **Theme Customizer** live-editable theme with 5 built-in presets (Dark, Light, Midnight, Solarized, HighContrast) and import/export
- **Instance Graph** visual relationship graph for any instance, showing parent chain, children, and reference properties (Adornee, PrimaryPart, ObjectValue.Value, etc.) with pan, zoom, and viewport culling
- **Call Stack Viewer** capture stack snapshots on demand, sample-based profiling to find hot functions, and one-click jump to the resolved script in the Script Viewer
- **Connection Tracer** list every active connection on an instance's signals (API-driven enumeration covers every event the class exposes); see which script and line each handler comes from and disable, fire, defer, or disconnect them in place
- **Change History** watch any instance and get a live, timestamped log of property changes with before/after values
- **Memory Inspector** find what's still holding a reference to a given instance (instance properties, Lua tables, function upvalues) plus heap stats and Lua memory totals

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
- [x] Instance relationship graph (visual node map)
- [x] Call stack / script trace viewer
- [x] Event connection tracer (signals → connections)
- [x] Change history tracker (what changed, when, and where)
- [x] Memory/reference inspector for instances

---

## 💡 Notes
FxkeDex is experimental. Some features may behave differently depending on runtime environment or game structure.

---

## 🤝 Credits
Original Dex++ Explorer:
https://github.com/AZYsGithub/DexPlusPlus/

All additional modifications and improvements by FxkeDex contributors.
