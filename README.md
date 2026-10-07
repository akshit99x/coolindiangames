# Khel Bharat Arcade

Toys and games from India's civilisation, history and culture, built for Smart India Hackathon 2026,
Problem Statement 26208 (Student Innovation, Toys & Games, AICTE).

Four neon arcade games, each rebuilt from a real traditional Indian game or monument. Each one has its own
live-generated raga soundtrack, and the whole arcade is available in English, Hindi, Tamil, Bengali and Telugu.
Open `index.html` in any browser. It is a single file with no build step and no backend.

| Game | Where it comes from | How it plays | Soundtrack |
|------|---------------------|--------------|------------|
| **Konark Chakra** | Konark Sun Temple, Odisha (13th c.), built as Surya's chariot with 24 sundial wheels | Guard a diya's flame. Graze shadows for combos, collect lotuses, then fire a Konark-wheel shockwave | Raag Bhairav (a dawn raga), Teentaal |
| **Patang Yuddh** | Kite fighting on Makar Sankranti and Uttarayan, with glass-coated manjha string | Steer your kite across rival strings to cut them ("Bo kata!"). Ride wind gusts and switch on glass manjha | Raag Yaman (an evening raga), Keherwa |
| **Gilli Danda** | One of South Asia's oldest street games (viti-dandu, kitti-pullu, dang-guli, goti-billa) | Tap to flip the gilli, tap again to strike. Timing sets a low drive or a high lob past running fielders | Raag Khamaj, Dadra |
| **Moksha Patam** | Gyan Chaupar, the Indian original of Snakes & Ladders (ladders = virtues, snakes = vices) | Endless climber. Ladders of virtue lift you, snakes of vice drag you down, and Garuda gives a giant leap | Raag Kafi, Teentaal |

How history is built into the games:
- Each game opens with a **From history** card and a **How to play** card in the selected language.
- Ladder and snake labels in Moksha Patam are the virtues and vices themselves (Satya, Daya, Krodh, Lobh…).
- Each round ends with a **Did you know?** fact about that game's history.
- The soundtrack is synthesised live: a tanpura drone, tabla bols (dha, dhin, na, tin, ta, ge) in the game's taal, and a melody built
  from that raga's scale. It speeds up as play intensifies.

Arcade feel: canvas rendering, particles, screen shake, hit-stop and slow-motion, combo multipliers, risk-reward graze mechanics,
best scores saved in localStorage, mouse, keyboard and touch controls, and a layout that works on phones.

Controls: mouse, touch drag or WASD / arrow keys to move. Click, Space or the on-screen button for the power move. P pauses, M mutes.

`classic.html` is the earlier, simpler DOM version (five games with a quiz).

## Publish it

Settings > Pages > deploy from the `main` branch, root folder.
