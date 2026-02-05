# NPE STATE LOG: INITIAL STATE
**Project:** Solterra Bay - Book 2: "The Stilled Disciple"

## 1. GLOBAL VARIABLES
*   **Time:** [T-Minus 72 Hours] (Countdown to Demos's permanent death)
*   **Entropy:** 0.2 (Low - "The Calm Before")
*   **Dominant Field:** `F_PublicPanic` (The fear of the "Feral Gorgon" fueled by rumors)

## 2. AXIS DEFINITIONS (The Measured Forces)
*   **Axis_A (Trust):** Scale 0-10. (0 = Paranoia, 10 = Absolute Faith).
    *   *Cornelius:* 5 (High Professional Trust, Low Personal Intimacy).
    *   *Photine:* 2 (She is lying to everyone).
*   **Axis_B (Justice):** Scale 0-10. (0 = Lawless/Vigilante, 10 = Due Process).
    *   *The Mob:* 1 (Torches and Pitchforks).
    *   *Cornelius:* 9 (Believes in the System).
*   **Axis_C (Visibility):** Scale 0-10. (0 = Hidden/Masked, 10 = Exposed).
    *   *Melaina:* 0 (Invisible/Hidden).
    *   *Demos:* 10 (Statue in public view).

## 3. ENTITIES & VECTORS (Starting State)

### Cornelius (The Sleuth)
*   **Archetype:** The Scholar Dragon.
*   **V_Curiosity:** +8 (Driven to solve the puzzle).
*   **V_Duty:** +7 (Must protect the Town/Knowledge).
*   **V_Bias:** -4 (Believes "Biology is Destiny" regarding Gorgons).

### Photine (The Antagonist/Healer)
*   **Archetype:** The Desperate Mother.
*   **V_Protect(Melaina):** +10 (Absolute/Override).
*   **V_Guilt:** +6 (Rising steadily as she lies).
*   **V_Deception:** +9 (Masking the truth/fundraising).

### The Gorgon Enclave (The Suspects)
*   **V_Defense:** +8 (Circle the wagons).
*   **V_Fear:** +9 (Terrified of the Mob/Council).

## 4. FIELDS (The Environment)
*   **F_TheWeep:** (Biological Field). A degenerative disease acting on Melaina. Force: *Decay*.
*   **F_TheClock:** (Temporal Field). A rigid 72-hour limit. Force: *Pressure*.
*   **F_Scarcity:** (Economic Field). The lack of funds to ship Melaina. Force: *Desperation*.

## 5. THRESHOLD CONSTRAINTS
*   **Midpoint Lock:** Melaina MUST be petrified by Chapter 10. (State Change: `Melaina.Status` -> `Statue`).
*   **Climax Lock:** Demos MUST be un-petrified by Sunset Day 3. (State Change: `Demos.Status` -> `Alive`).
