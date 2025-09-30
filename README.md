# Ink & Heart 🎴🖤  

[![Build](https://github.com/ZeroGenesis-Chris/ink-heart/actions/workflows/build.yml/badge.svg)](https://github.com/ZeroGenesis-Chris/ink-heart/actions/workflows/build.yml)  
[![CI](https://github.com/ZeroGenesis-Chris/ink-heart/actions/workflows/ci.yml/badge.svg)](https://github.com/ZeroGenesis-Chris/ink-heart/actions/workflows/ci.yml)  
[![Daily Export](https://github.com/ZeroGenesis-Chris/ink-heart/actions/workflows/export_daily.yml/badge.svg)](https://github.com/ZeroGenesis-Chris/ink-heart/actions/workflows/export_daily.yml)  

**Ink & Heart** is a roguelite deckbuilder where your life is a deck — and every card is a tattoo.  
Built with **Godot 4.2**.  

---

## 📖 Overview  
- **Genre:** Roguelite Deckbuilder  
- **Core Loop:** Climb a collapsing tower, tattoo cards to your skin, fuse hybrids between runs.  
- **Target Session:** ~10 minutes per run  
- **Status:** Pre-Alpha (Prototype stage)  

See the full [Game Design Document](./docs/Game%20Design%20Document.docx) for details.  

---

## 🏗️ Project Structure  

.github/ → CI/CD workflows (build, balance, daily export)
csv/ → Content spreadsheets (cards, balance projections)
data/ → Save data, logs, analytics
docs/ → Game design docs, notes, planning
godot/ → Godot 4 project files (scenes, scripts, assets)
raw_art/ → Source art before import/processing
scripts/ → Helper scripts (exporters, validators, tools)


---

## 🚀 Getting Started  

### Requirements  
- [Godot 4.2](https://godotengine.org/download)  
- Git + LFS (for large art/audio assets)  

### Clone  
```
git clone https://github.com/ZeroGenesis-Chris//ink-heart.git
cd ink-heart/godot
Run
Open the godot/ folder in Godot 4.2 and press Play.
```

🔄 Development Workflow

main → stable, tagged releases only

dev → active development branch

feature/* → new features (e.g. feature/fusion-lab)

Pull requests must target dev

⚔️ Testing & Balance

Automated balance tests run via balance.yml using data in /csv.

RNG is seeded → deterministic bug reproduction.

Daily builds are exported automatically via export_daily.yml.

📦 Releases

Milestones (from design doc
):

Week 2 → Prototype

Week 4 → Alpha

Week 8 → Beta

Week 12 → Gold

Download builds from Releases
.

📜 License

TBD — currently private project.
(Options: MIT for code + CC-BY-SA/CC0 for art/audio.)

🖋 Credits
Engine: Godot 4.2
Special Thanks: Open-source tools & community



