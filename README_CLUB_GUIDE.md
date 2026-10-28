# OPERATION: THREE WISE MONKEYS
## Complete Game Setup, DIY Build Guide & Event Handbook

---

## 1. HOW THE GAME WORKS (THE 60-SECOND PITCH)

**Operation: Three Wise Monkeys** is a 5-minute real-life cooperative bomb defusal game for **3 Players + 1 Game Master (GM)**. Each player loses one sense, forcing the team into a strict communication triangle:

| Role | Sensory Handicap | Where They Are | What They Can Do |
| :--- | :--- | :--- | :--- |
| **1. THE MUTE** (*Speak No Evil*) | **Mouth Taped Shut** (Cannot speak or make any vocal sound). | Stands across the room (~3 meters away) holding the **Defusal Manual**. | Can **hear** both teammates and **see** the Deaf player. Reads the manual rules and acts out instructions using **pure charades** (no sign language, no air-spelling). |
| **2. THE DEAF** (*Hear No Evil*) | **Noise-Cancelling Headphones** (Plays loud white/brown noise) + **Handcuffed behind chair**. | Sits right next to the bomb table, looking at the bomb and at the Mute player. | Can **see the bomb** and **speak out loud**. Shouts the bomb clues to Mute, watches Mute's charades, and yells spoken instructions to Blind. |
| **3. THE BLIND** (*See No Evil*) | **Blackout Sleep Mask** (Zero vision). | Sits directly in front of the bomb box at the table. | Can **hear Deaf** and **touch the bomb**. Feels the Mystery Object, textures, dials, and switches, and physically disarms the bomb. Can speak out loud. |
| **4. GAME MASTER** | None (Referee). | Stands by the laptop & Bluetooth speaker. | Runs the 5:00 timer console (`index.html`), presses `[X]` when a mistake happens, presses `[V]` when defused, and resets the box in 30 seconds. |

---

## 2. ROOM LAYOUT & ANTI-CHEAT DIAGRAM

```
                  ┌──────────────────────────────────────────────┐
                  │                 THE MUTE                     │
                  │   - Stands 3 meters away with the Manual     │
                  │   - Mouth taped shut (ZERO sounds allowed)   │
                  │   - Hears Deaf & Blind; acts out charades    │
                  └──────────────────────┬───────────────────────┘
                                         │
                                         │ Silent Charades / Nodding / Pointing
                                         │ (Deaf shouts clues -> Mute mimes answers)
                                         ▼
                  ┌──────────────────────────────────────────────┐
                  │                 THE DEAF                     │
                  │   - Sits near table; SEES the bomb clearly   │
                  │   - HANDCUFFED behind chair (no touching!)   │
                  │   - Wears noise-cancelling headphones        │
                  │   - Yells step-by-step commands to Blind     │
                  └──────────────────────┬───────────────────────┘
                                         │
                                         │ Spoken Commands
                                         │ ("Turn the Triangle dial RIGHT!")
                                         ▼
                  ┌──────────────────────────────────────────────┐
                  │                 THE BLIND                    │
                  │   - Sits at table wearing blackout mask      │
                  │   - Reaches into Mystery Hole & yells object │
                  │   - Feels textures, turns dials & unclips    │
                  └──────────────────────────────────────────────┘
```

---

## 3. STEP-BY-STEP DIY BOX BUILD GUIDE (<$15 BUDGET)

> [!TIP] **Interactive 3D Hardware CAD Schematic**: Open [`bomb_3d_schematic.html`](file:///D:/melle/antigrav/bomb%20game%20L/bomb_3d_schematic.html) in your browser for a full 360° 3D CAD schematic with an exploded assembly slider, dimension measurements, X-ray internal view, and clickable component inspector!

### Shopping List (Materials)
1. **The Box:** 1 sturdy corrugated shipping box or boot box (~30cm × 25cm × 15cm).
2. **Wires & Clips:** 10 wooden clothespins (or binder clips) + 6 colored shoelaces or thick yarn cords (**Red, Blue, Yellow, Green, Pink, Black**).
3. **5 Texture Badges (2"×2" cardboard squares with Velcro on the back):**
   * **Sandpaper** (rough)
   * **Sponge** (soft, porous kitchen/craft sponge)
   * **Metal Coin** (a large coin glued flat to cardboard)
   * **Soft Felt** (fuzzy cloth/fleece)
   * **Ribbed Cardboard** (peel the top layer off corrugated cardboard to expose the wavy ridges)
4. **3 Shape Dials:** 3 plastic bottle caps + 3 brass paper fasteners (brads). Glue raised cardboard/foam shapes on top of each cap: **Triangle (▲)**, **Square (■)**, and **Circle (●)**.Draw a notch/arrow on the edge of each cap so Deaf can see which way it points (**UP, DOWN, LEFT, RIGHT**), and glue a small raised bump on the arrow tip so Blind can feel where it points.
5. **4 Toggle Switches:** 4 cheap rocker switches glued in a row (or 4 craft popsicle sticks pinned on brass brads that flip UP and DOWN), numbered **1, 2, 3, 4**.
6. **The 5 Mystery Objects (placed one at a time inside the box):**
   * **Metal Key**, **AA Battery**, **Spiky Rubber Ball**, **Wooden Block**, **Padlock**.
7. **Clue Tags (Velcro-backed):**
   * 12 Serial Number cards (matching Seeds #01–#12)
   * 2 Indicator cards (`LIT: FRK` and `UNLIT: CAR`)
   * 2 Clothespins glued on the side to hold **0, 1, or 2 AA Batteries**.

---

### How to Assemble the Box in 30 Minutes

```
      ┌───────────────────────────────────────────────────────────────┐
      │ [SN: A34-E9]          [LIT: FRK]          [BATTERIES: (I)(I)] │
      ├───────────────────────────────────────────────────────────────┤
      │  MODULE 2: 3 SHAPE DIALS         MODULE 3: 4 TOGGLE SWITCHES  │
      │   (▲)       (■)       (●)          [1]    [2]    [3]    [4]   │
      ├───────────────────────────────────────────────────────────────┤
      │  MODULE 1: 5 TACTILE WIRES (Top = Slot 1, Bottom = Slot 5)    │
      │                                                               │
      │  SLOT 1: [ Sandpaper   ]  📎════════( WIRE 1 )════════📎      │
      │  SLOT 2: [ Sponge      ]  📎════════( WIRE 2 )════════📎      │
      │  SLOT 3: [ Metal Coin  ]  📎════════( WIRE 3 )════════📎  ┌───┤
      │  SLOT 4: [ Soft Felt   ]  📎════════( WIRE 4 )════════📎  │ H │
      │  SLOT 5: [ Ribbed Card ]  📎════════( WIRE 5 )════════📎  │ O │
      │                                                           │ L │
      └───────────────────────────────────────────────────────────┴───┘
                                                                (Side Hole)
```

1. **Cut the Side Mystery Hole:** Cut a 10cm × 10cm hole in the right side of the box. Tape or glue a dark sock (with the toe cut off) or a black cloth flap inside the hole so Blind can reach their hand in without anyone seeing inside.
2. **Mount the 5 Wire Slots:** Glue 5 clothespins down the left column and 5 down the right column. Stick Velcro strips to the left of each left-hand clothespin for the **5 Texture Badges** so you can shuffle which texture sits in which slot between rounds!
3. **Mount the 3 Shape Dials:** Poke 3 holes across the upper-left section, push the brass brads through the bottle caps, and fold the legs underneath so they rotate smoothly with slight friction.
4. **Mount the 4 Toggle Switches:** Glue the 4 switches in a clean horizontal row on the upper-right section and label them **1, 2, 3, 4**.
5. **Mount the Clue Holders:** Put Velcro strips along the top edge for the **Serial Number** and **Indicator Tag**, and glue 2 clothespins on the side to clip **AA Batteries**.

---

## 4. RUNNING A 5-MINUTE ROUND (STEP-BY-STEP)

### Phase 1: The 30-Second Reset (Before Players Enter)
1. Put the **Blackout Sleep Mask** on the Blind player first so they never see the board.
2. Press **`[N]`** on the laptop console (`index.html`) to pick a Seed (e.g., **Seed #01 — ALPHA**).
3. Match the box to the Seed:
   * Stick on the **Serial Number** card and **Indicator** card.
   * Clip on **0, 1, or 2 Batteries**.
   * Drop the **1 Mystery Object** inside the side hole.
   * Clip the **5 Colored Wires** and stick the **5 Texture Badges** into Slots 1 to 5.
   * Scramble the Dials and Switches so the players have to set them.
4. Seat **Deaf** at the chair, handcuff their hands behind the chair back, and put on their headphones with white/brown noise playing.
5. **CRITICAL ANTI-CHEAT STEP:** Keep **Page 5 (The GM Answer Key)** with you at the laptop! Hand **ONLY Pages 1–4** of the Defusal Manual to **Mute** standing at the 3-meter line.

### Phase 2: During the 5-Minute Countdown
1. Press **`[SPACEBAR]`** on the laptop. The authentic *Keep Talking* vocal *"beep-boop"* countdown begins!
2. **Gathering the Clues:**
   * Blind reaches into the side hole, feels the object, and yells it out (*"It's a Metal Key!"*). Mute hears this directly!
   * Deaf reads the outside of the box and yells to Mute (*"Serial is A-3-4-E-9! Two batteries! Lit F-R-K! Red wire is in Slot 1, Blue wire in Slot 2..."*).
   * **Note on Textures:** Because the Texture Badges look dark/covered or aren't labeled with text, Deaf does NOT know which texture is where — only Blind can feel the textures, and Mute must mime the target texture!
3. **Solving the 3 Modules:**
   * Mute checks the manual tables and acts out instructions to Deaf.
   * Deaf translates Mute's gestures into clear spoken orders for Blind.
   * When Blind finishes a module correctly, GM can press **`[C]`** to play the green *Module Solved Chime*.
4. **Handling Mistakes & Anti-Cheat Enforcement (Strikes):**
   * **Hardware Error:** Blind unclips the wrong wire, or calls "Defused" with a wrong dial/switch $\to$ Press **`[X]`** (+1 Strike).
   * **Vocal Violation:** Mute makes any vocal sound, hums, or whispers $\to$ Press **`[X]`** (+1 Strike).
   * **Air-Writing / Finger-Counting Cheat:** Mute traces letters in the air, uses sign language, OR holds up 1–5 fingers to tell Deaf which wire slot to pull instead of miming the physical texture $\to$ Press **`[X]`** (+1 Strike)! (Holding up 1–4 fingers is ONLY allowed during Module 3 for the 4 numbered toggle switches).
   * **Physical Violation:** Deaf touches the bomb, lifts their headphones, or Blind peeks under the mask $\to$ Press **`[X]`** (+1 Strike).
   * On the **3rd Strike** (or when time hits `00.00`), the bomb automatically **DETONATES** with the explosion blast!
5. **Winning the Game:**
   * Once the 1 target wire is unclipped, all 3 dials are aligned, and all 4 switches are set, Deaf yells **"BOMB DEFUSED!"**
   * GM verifies the box and presses **`[V]`** to stop the clock and play the Victory Fanfare!

---

## 5. LAPTOP CONSOLE HOTKEYS CHEAT SHEET

| Key | Action | Sound Triggered |
| :---: | :--- | :--- |
| **`SPACEBAR`** | Start / Pause 5:00 Timer | Starts the vocal *"beep-boop"* ticking (`doublebeep.wav`) |
| **`X`** or **`1`** | Add Strike (+1 Error) | Plays `Strike.wav` buzzer & speeds up timer |
| **`Z`** | Undo / Remove Strike | Clears last strike lamp |
| **`C`** | Module Solved | Plays positive `CorrectChime.wav` |
| **`V`** or **`D`** | Bomb Defused (Win!) | Stops clock & plays `BombDefused.wav` + `GameOverFanfare.wav` |
| **`R`** | Reset Bomb | Resets clock to `05:00` and clears strikes |
| **`N`** | Next Seed Card | Cycles through Seeds #01 to #12 on screen |
| **`W` / `S` / `B`** | Bonus Foley Sounds | Plays Wire Snip (`W`), Switch Flip (`S`), or Button Press (`B`) |
| **`E`** | Toggle Emergency Siren | Starts/stops the `<60s` `EmergencyAlarm.wav` room siren |
| **`M`** | Mute All Audio | Mutes/unmutes console audio |
