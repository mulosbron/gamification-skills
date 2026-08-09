# 🎮 Gamification Skills for AI Agents

> **Transform your LLM coding and design assistant into an expert educational game designer.**

A production-ready suite of 5 specialized AI agent skills encoding gamification theory, game mechanics, and educational design methodologies. Compatible with **Google Antigravity**, **Claude Code**, **Gemini**, **Cursor**, **Windsurf**, and any AI agent supporting project-level instruction files (`AGENTS.md`).

---

## 🌟 Key Features

- 🎲 **5 Specialist Domain Skills**: Card Games, Board Games, Escape Rooms, Digital Gamification, and Game Engineering.
- 🤖 **Universal Agent Integration**: Single `AGENTS.md` context file automatically loads and routes queries to the relevant skill.
- 🎓 **Pedagogical Alignment**: Integrates learning objectives directly into game mechanics—eliminating the "Chocolate-Covered Broccoli" anti-pattern.
- 🧠 **Motivational Psychology**: Engineered around core intrinsic motivation drives, player typologies, flow theory, and SAPS reward architecture.

---

## 📚 The 5 Specialized Skills

| Skill | Directory | Primary Use Cases | Key Mechanics & Frameworks |
|-------|-----------|-------------------|----------------------------|
| 🃏 **Card Game Design** | `skills/card-game-design/SKILL.md` | Educational card games, flashcards, deck-building, classroom feedback systems | Deck mechanics, power cards, set collection, challenge duels, feedback cards |
| 🎲 **Board Game Design** | `skills/board-game-design/SKILL.md` | Tabletop box games, path progression games, board layouts, cooperative classroom games | Linear/branching paths, Win conditions, custom dice, two-phase collective endings |
| 🔐 **Escape Game Design** | `skills/escape-game-design/SKILL.md` | Escape rooms, puzzle chains, time-bound challenges, mystery solving | Progressive puzzle chains, ciphers, lock systems, hint architecture, debrief guides |
| 💻 **Digital Gamification** | `skills/digital-gamification/SKILL.md` | Digital learning platforms (Kahoot, Classcraft), XP systems, D6 gamification model | Engagement loops, D6 design model, Multiplayer Classroom model, hybrid physical-digital |
| ⚙️ **Game Engineering** | `skills/game-engineering/SKILL.md` | Motivation analysis, flow optimization, player taxonomy, system balancing | MDA framework, 8 Core Drives, Flow theory, SAPS reward hierarchy, Juicy feedback |

---

## ⚡ Quick Start

### 1. Copy to Your Project

Clone or copy the `gamification-skills` directory into your project root:

```bash
cp -r gamification-skills/ my-project/
```

### 2. Prompt Your AI Assistant

Open your AI coding or design assistant (Antigravity, Claude Code, Gemini, etc.) in the project directory and ask directly:

```text
"Design an educational card game for teaching fractions to 4th graders."
```

```text
"Create a 30-minute escape room experience for high school chemistry."
```

```text
"Using skills/game-engineering/SKILL.md, analyze why my class XP system isn't engaging Explorers."
```

### 3. Multi-Skill Complex Unit Example

For comprehensive projects, combine skills in your prompt:

```text
Design a gamified 8-week unit on ecosystems for 7th graders.

Use the following skills:
1. game-engineering for motivational architecture and player type balance
2. board-game-design for weekly classroom board game activities
3. escape-game-design for the unit culminating challenge
4. digital-gamification for between-class digital engagement
```

---

## 🛠️ Architecture

```
gamification-skills/
├── AGENTS.md                          # Universal AI agent instructions & skill router
├── README.md                          # Project documentation
└── skills/
    ├── card-game-design/
    │   └── SKILL.md                    # Educational Card Game Specialist
    ├── board-game-design/
    │   └── SKILL.md                    # Board & Tabletop Game Specialist
    ├── escape-game-design/
    │   └── SKILL.md                    # Escape Room & Puzzle Chain Specialist
    ├── digital-gamification/
    │   └── SKILL.md                    # Digital System & Platform Specialist
    └── game-engineering/
        └── SKILL.md                    # Motivation Theory & Game Science Specialist
```

---

## 🎯 Core Design Principles

All 5 skills adhere strictly to 8 universal design principles:

1. 🥦 **No "Chocolate-Covered Broccoli"**: Educational content is woven **into** game mechanics, never tacked on as an afterthought quiz.
2. 🧠 **75% Psychology, 25% Technology**: Gamification is motivational design, not tool or software selection.
3. 🔥 **Intrinsic Over Extrinsic**: Design for internal motivation. Status, Access, and Power beat physical rewards ("Stuff").
4. 👥 **Serve All Player Types**: Accommodate Achievers, Explorers, Socializers, and Competitors in every design.
5. 🌊 **Flow State Optimization**: Dynamically balance challenge against skill level to prevent boredom or anxiety.
6. ⭕ **Voluntary Magic Circle**: Participation must feel chosen; forced gamification fails.
7. 📖 **Narrative as Vehicle**: Storytelling gives meaning and emotional weight to game mechanics.
8. 🔄 **Agile Iteration**: Games are designed once, but gamification systems evolve continuously based on player response.

---

## 📄 License

This repository is licensed under the [MIT License](LICENSE).
