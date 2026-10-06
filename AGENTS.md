# Gamification Skills

Five skills for designing educational games and gamification systems. Each skill is a single `SKILL.md` that carries the design stance, classroom rules, and anti-patterns the model cannot infer on its own. General game-design theory is intentionally left out.

## Skills

| Skill | Path | Use when |
|---|---|---|
| Card Game Design | `skills/card-game-design/SKILL.md` | Designing card games, flash card activities, deck-building, or card-based classroom systems. |
| Board Game Design | `skills/board-game-design/SKILL.md` | Designing board or tabletop games, path-based learning games, or physical game kits for a classroom. |
| Escape Game Design | `skills/escape-game-design/SKILL.md` | Designing escape rooms, puzzle chains, mystery or time-bound team challenges. |
| Digital Gamification | `skills/digital-gamification/SKILL.md` | Designing XP, level, badge or leaderboard systems, choosing platforms like Kahoot or Classcraft, or gamifying a whole unit or semester. |
| Game Engineering | `skills/game-engineering/SKILL.md` | Diagnosing why a game or gamification system is not working, designing motivation and reward architecture, or balancing an existing system. |

Read the matching skill before designing. Most real projects combine two or more: use game-engineering for the motivational backbone and one of the others for the format.

## Folder structure

```
gamification-skills/
├── AGENTS.md
├── README.md
└── skills/
    ├── card-game-design/SKILL.md
    ├── board-game-design/SKILL.md
    ├── escape-game-design/SKILL.md
    ├── digital-gamification/SKILL.md
    └── game-engineering/SKILL.md
```

## How to work

If the target audience, learning objective, or a hard constraint (time, group size, materials, platform) is missing, ask before designing. If the user has already given them, design directly. When the user has a project or curriculum folder, look at what exists before proposing changes.

## Principles that apply to every skill

1. Learning is woven into the mechanic, never pasted on afterwards (chocolate-covered broccoli). Pausing the game to deliver content breaks the learning.
2. Gamification is 75% psychology, 25% technology. Start from motivation, then pick tools.
3. A game is designed once; gamification is updated continuously based on how players respond.
4. Prefer status, access and power over stuff as rewards. External rewards are a bridge to intrinsic motivation, not the destination.
5. Serve all four player types: achievers, explorers, socializers, competitors.
6. Challenge must track skill. Too easy bores, too hard frustrates.
7. Participation is voluntary. Forced gamification is not gamification.
8. Narrative carries the mechanics. Every rule should make sense inside the story.
