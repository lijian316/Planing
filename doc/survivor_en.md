# 🎮 Survivor - Game Design Document

---

## 🧩 Basic Project Information

- **Game Name**: Survivor
- **Game Type**: Multiplayer Online Survival Challenge (Competition + Psychological Strategy)
- **Platforms**: iOS / Android / PC
- **Engine**: Unity
- **Target Audience**: 16~35 years old, players who enjoy challenges, strategy, and psychological games
- **Monetization**: Free to play + In-app purchases (skins/revive/pass)

---

## 🎯 Core Game Design

### 🌐 Core Loop

- Character Selection → Challenger → Matchmaking → Stage Challenge → Elimination → Payment → Character Selection
- Character Selection → Challenger → Matchmaking → Stage Challenge → Advancement → Final Victory → Reward: 100 coins → Character Selection
- Character Selection → Spectator → Deduct 100 coins → Bet on Challenger → Bet Challenger Eliminated → Lose all bet coins
- Character Selection → Spectator → Deduct 100 coins → Bet on Challenger → Bet Challenger Advances → Bet Challenger Wins → Get same reward as challenger + all other spectators' bet coins

### 🔥 Core Fun

- Survival competition + strategic decision-making + psychological pressure
- Diverse stages and elimination mechanisms
- Social interaction (cooperation, deception, betrayal)

### 🏆 Game Objective

- Survive to the final stage
- Win the final prize (in-game currency)

---

## 🎮 Stage Design (V1.0)

| No. | Stage Name      | Brief Description                        | Operation Details & Presentation |
| --- | -------------- | ---------------------------------------- | -------------------------------- |
| 1   | Red Light Green Light | Avoid moving during "Red Light" period, tests reaction and rhythm | Swipe up to start moving forward (like skating), swipe down to stop (with delay, not instant), requires prediction |
| 2   | Glass Bridge   | Players jump in turn, judge which is reinforced glass, with probability | Swipe to move forward, tap to jump |
| 3   | Tug of War     | Team cooperation, losing team eliminated  | Tap quickly |
| 4   | Cliff Jump Rope| Cross the cliff without being tripped    | Tap |
| 5   | Maze Brawl     | Two teams in maze, red team chases, blue team escapes | Move |

> Plan to add 1 new stage each month to enrich the pool.

---

## 🎮 VIP Betting Gameplay


## 👤 Player System & Social

- **Matchmaking**: Solo only
- **Social Interaction**: Emojis, chat
- **Character Appearance**: Skins, actions, badges, titles
- **Progression System**: Visual rewards and identity only, no stat impact
- **Character Attribute System**: Players can freely set intelligence, stamina, cunning, and profession at the start (different professions have advantages/disadvantages in different stages)
- **Spectator Betting System**: Watch other challengers' games, bet and win rewards

---

## 🎨 Art Style

- **Characters**: Chibi cartoon / minimalist realistic
- **Stages**: Industrial closed scenes (refer to Squid Game)
- **Color Scheme**: Mainly cool tones + strong contrast (red, white, black)
- **UI Style**: Intense oppression, minimalist flat icons

---

## 🔊 Sound & Music

- Electronic synth background music + suspenseful atmosphere
- NPC voice broadcast (start/countdown/elimination)
- Impactful sound effects for key events (elimination/victory)

---

## 🛒 In-App Purchases & Monetization

- **Appearance System**: Costumes/emotes/actions (no combat impact)
- **Revive Character**: Pay to revive after each elimination

---

## 📈 Operations & Update Plan

### 🎯 Event Rhythm

- Each match randomly combines 5 stages, initial player count: 50
- Limited-time events: festivals/challenge modes/collaborations
- New themed maps and mechanics every month

### 🏁 Leaderboard & Data Stats

- Number of clears
- Number of revives
- Number of spectates
- Betting win rate

---

## ⚠️ Project Risk Control

| Risk Point                | Countermeasures                        |
| ------------------------- | -------------------------------------- |
| Repetitive gameplay       | Add randomness, rhythm stages, diverse themes |
| Player churn              | Lower frustration, add "fun/relaxed" rounds |
| Technical bottleneck (sync/physics) | Use mature solutions like Photon, Mirror, etc. |

---

## ✏️ Prototype Sketches (Illustrations)

### 1. Red Light Green Light Stage Prototype (Diagram)

Player Start ———————→→→→→→→

[Giant Doll View]

Note: Players must move during green light, stay still during red light, or be eliminated.

---

### 2. Glass Bridge Stage Prototype (Diagram)

Spaces are reinforced glass, X is normal glass

[ ]   [ ]   [ ]   [ ]   [ ]
[X]   [ ]   [X]   [ ]   [X]

Players jump from left to right, must judge each time.

> These diagrams can also be converted to Figma prototypes or SVG diagrams for further design.

---

## ✅ Summary & Next Steps

- Core gameplay complete, supports continuous content updates
- Strong social drive, combines elimination and cooperation
- Light stat system + immersive experience

**Next Steps:**

- Figma UI prototype design
- Core 6 stages development & testing
- SDK integration (matchmaking/ads/payment)
- Build user community + collect feedback from open beta 