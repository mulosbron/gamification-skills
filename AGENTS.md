# Gamification Skills — Agent Instructions

## Overview

This directory contains 5 specialized gamification skills designed for educational game design, encoding gamification theory, mechanics, and design methodologies for AI agent use.

## Available Skills

| Skill | Directory | Activate When |
|-------|-----------|---------------|
| **Card Game Design** | `skills/card-game-design/SKILL.md` | User asks to design card games, flash card activities, deck-building exercises, or card-based gamification |
| **Board Game Design** | `skills/board-game-design/SKILL.md` | User asks to design board/box games, tabletop experiences, or path-based learning games |
| **Escape Game Design** | `skills/escape-game-design/SKILL.md` | User asks to design escape rooms, puzzle chains, mystery-solving activities, or time-bound challenges |
| **Digital Gamification** | `skills/digital-gamification/SKILL.md` | User asks about gamification platforms (Kahoot, Classcraft), reward systems, XP/level systems, or digital motivation design |
| **Game Engineering** | `skills/game-engineering/SKILL.md` | User asks about motivation theory, player types, flow states, reward psychology, engagement loops, or why a game isn't working |

## How to Use These Skills

### Method 1: Automatic Context Loading

AI agents automatically read `AGENTS.md` in the project root. When starting a conversation about game design, the agent has immediate access to these skill definitions.

### Method 2: Direct Reference in Prompts

When asking an agent to design a game, reference the specific skill:

```
Using the card-game-design skill from skills/card-game-design/SKILL.md, 
design an educational card game for teaching fractions to 4th graders.
```

### Method 3: Auto-Activation by Topic

Agents will naturally activate the appropriate skill based on request keywords:

- "card game", "deck", "flash card", "playing cards" → `card-game-design`
- "board game", "box game", "tabletop", "path game" → `board-game-design`
- "escape room", "puzzle", "mystery", "code-breaking" → `escape-game-design`
- "gamification", "Kahoot", "points", "badges", "XP", "leaderboard", "Classcraft" → `digital-gamification`
- "motivation", "flow", "player types", "rewards", "engagement" → `game-engineering`

### Method 4: Combined Skill Usage

Many real-world projects require multiple skills. Example prompt:

```
Design a gamified 8-week unit on ecosystems for 7th graders.

Use the following skills:
1. game-engineering for the motivational architecture and player type accommodation
2. board-game-design for the weekly board game activity
3. escape-game-design for the unit culminating challenge
4. digital-gamification for the between-class digital engagement system

Reference all relevant SKILL.md files.
```

## Agent Execution Flow (IMPORTANT)

When a user requests assistance using these gamification skills, **DO NOT generate a complete design immediately**. Instead, follow this step-by-step flow:

1. **Information Gathering (Ask First):** Ask the user clarifying questions to understand their exact needs. Determine if they want to:
   - Create a brand new game/application from scratch.
   - Add gamification elements to an existing app, game, or curriculum.
   - Also ask about their target audience, primary learning/engagement objectives, and constraints.
2. **Context Scanning:** Use your available tools (like `list_dir`, `view_file`, or `grep_search`) to scan the user's workspace and folders. Investigate existing code, documentation, or assets to deeply understand the current state of their project before proposing changes.
3. **Analyze & Propose:** Based on the user's answers and the workspace context, use the appropriate `SKILL.md` files to formulate your gamification strategy and design.

## Skill Architecture

Each SKILL.md file follows a consistent structure:

- **Core Identity**: When to activate this skill
- **Knowledge Base**: Theoretical and practical expertise
- **Design Process**: Step-by-step methodology
- **Anti-Patterns**: Common mistakes to avoid
- **Output Format**: How to structure the response

## Key Universal Principles (Always Active)

Regardless of which skill is activated, these universal principles always apply:

1. **Chocolate-Covered Broccoli Principle**: Never paste learning content onto a game as an afterthought. The learning must be woven INTO the game mechanics.

2. **75% Psychology, 25% Technology**: Gamification is about motivational design, not about tools or platforms.

3. **Agile, Not Static**: Gamification systems must be continuously updated based on player response. A game is designed once, but gamification is iterated constantly.

4. **Intrinsic Over Extrinsic**: Design for internal motivation. External rewards are the weakest form. Status, access, and power are more sustainable.

5. **All Player Types Must Be Served**: Every design should have elements for Achievers, Explorers, Socializers, and Competitors.

6. **Flow Is the Goal**: Challenge must match skill level. Too easy = boredom, too hard = frustration.

7. **Voluntary Participation**: Forced gamification is not gamification. Players must choose to enter the Magic Circle.

8. **Narrative Is the Vehicle**: All game elements should be communicated through storytelling. The story makes mechanics meaningful.

## File Structure

```
gamification-skills/
├── AGENTS.md                          # Universal agent instructions
├── README.md                          # Project documentation
└── skills/
    ├── card-game-design/
    │   └── SKILL.md                    # Card Game Design Specialist
    ├── board-game-design/
    │   └── SKILL.md                    # Board Game Design Specialist
    ├── escape-game-design/
    │   └── SKILL.md                    # Escape Game Design Specialist
    ├── digital-gamification/
    │   └── SKILL.md                    # Digital Gamification Specialist
    └── game-engineering/
        └── SKILL.md                    # Game Engineering Specialist
```
