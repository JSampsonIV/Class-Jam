# SHRINKAGE: The 35-to-1 Word Collapse
> Built for the **Shrinking** Game Jam  
> **100% Single File HTML Game** • **Strict 5-Minute Time Limit**

---

## 🎮 How to Play

1. Open [`index.html`](./index.html) directly in any web browser (Chrome, Firefox, Safari, Edge). No web server, dependencies, or installations needed!
2. Select your game mode on the title screen (defaults to the full **35 → 1 Titan Shrink**).
3. Press **SPACE**, **ENTER**, or click **START SPELLING**.
4. Type the highlighted letter for the active word.
5. Each time you finish a word, the next word shrinks down by **exactly 1 letter** (from **35 letters** all the way down to a solitary **1-letter word**).
6. You have a **single 5:00 countdown clock** that **does not reset** when you get a word right. Type all words before the clock hits `00:00.00` to achieve the singularity!

---

## 🤏 Theme Integration: "Shrinking"

The game expresses the theme on multiple layers:
1. **The Lexical Shrink**: Every stage reduces the target word length by 1:
   - Stage 1: 35 letters (`HIPPOPOTOMONSTROSESQUIPEDALIOPHOBIA`)
   - Stage 2: 34 letters (`SUPERCALIFRAGILISTICEXPIALIDOCIOUS`)
   - Stage 3: 33 letters (`CYCLOPENTANOPERHYDROPHENANTHRENES`)
   - Stage 4: 32 letters (`CYCLOPENTANOPERHYDROPHENANTHRENE`)
   - Stage 5: 31 letters (`DICHLORODIPHENYLTRICHLOROETHANE`)
   - Stage 6: 30 letters (`PSEUDOPSEUDOHYPOPARATHYROIDISM`)
   - Stage 7: 29 letters (`FLOCCINAUCINIHILIPILIFICATION`)
   - Stage 8: 28 letters (`ANTIDISESTABLISHMENTARIANISM`)
   - Stage 9: 27 letters (`HONORIFICABILITUDINITATIBUS`)
   - Stage 10: 26 letters (`RADIOIMMUNOELECTROPHORESIS`)
   - Stage 11: 25 letters (`SUPERINCOMPREHENSIBLENESS`)
   - ...
   - Final Stages: 2 letters (`GO`), 1 letter (`A` / `I` — The Singularity!)
2. **The Physical Compactor Chamber**: The mechanical arena borders physically compress inward as the words get shorter, narrowing from `980px` down to `340px` with hydraulic steam and clank audio.
3. **The Shrinking Timer**: A high-precision 5-minute countdown clock and master gauge bar that constantly drains from 100% to 0%. Below 60 seconds, red emergency vignette pulses and heartbeat thuds activate.

---

## ⚡ Game Modes

- **The Titan Shrink (35 → 1)** *(Recommended for the 5-minute rush)*:
  - 35 words • 630 letters total.
  - At 30 WPM, takes ~4 minutes and 12 seconds, leaving a tense ~45-second buffer before the 5:00 clock expires!
- **The Mega Shrink (30 → 1)**:
  - 30 words • 465 letters total.
  - At 30 WPM, takes ~3 minutes and 10 seconds.
- **The Behemoth 45 (Prologue Boss)**:
  - Starts with the 45-letter dictionary king `PNEUMONOULTRAMICROSCOPICSILICOVOLCANOCONIOSIS`, then plunges immediately into the 35 → 1 shrink ladder! (36 words • 675 letters • ~4:30 at 30 WPM).
- **The Classic Shrink (25 → 1)**:
  - 25 words • 325 letters total.
  - At 30 WPM, takes ~2 minutes and 15 seconds.
- **The Micro Sprint (15 → 1)**:
  - 15 words • 120 letters total.
  - Quick 1:00 warmup speedrun.

---

## ⌨️ Controls

| Action | Control |
|---|---|
| Type letter | Physical keyboard keys `A-Z` (including `P`) or virtual on-screen keys |
| Start / Retry | <kbd>SPACE</kbd> / <kbd>ENTER</kbd> / Click button |
| Pause / Resume | <kbd>ESC</kbd> |
| Mute / Unmute | Speaker icon in header |
# Class-Jam
