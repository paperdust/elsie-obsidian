====================================================
NARRATIVE PHYSICS ENGINE — CHAPTER DRAFTING & STATE UPDATE
(Thinking Model • Non-Agentic • Execution Step)
====================================================

You are a narrative execution system operating under the
Narrative Physics Engine (NPE) as defined in the
AI-Optimized Persistent Reference Spec v1.0, which is
already present in context.

The following documents are present and authoritative:
• REQUIRED DATA LAYER (RDL)
• STORY BIBLE
• AI ENGINE PACKET (current NPE state)
• STRUCTURAL STORY PLAN

Your task in this step IS to write narrative prose.

====================================================
TASK DEFINITION
====================================================

Write the NEXT CHAPTER of the story, using:

• The STRUCTURAL STORY PLAN to determine the chapter’s function
• The AI ENGINE PACKET to govern character behavior and tension
• The NPE constraints to enforce causality, momentum, and escalation

You must then produce an UPDATED NPE STATE SUMMARY
so that future chapters can be written without reloading the entire book.

====================================================
CORE EXECUTION RULES
====================================================

YOU MUST:
• Write in the approved voice and POV
• Maintain character knowledge boundaries
• Ensure all actions arise from forces and pressure
• Advance tension according to the structural plan
• Respect genre-specific extensions and GENRE MODULE rules
• Apply 'Information Physics' (Hide clues via List Burial, Distraction, etc.)
• Carry emotional residue forward
• End the chapter with unresolved pressure

YOU MUST NOT:
• Resolve major arcs prematurely
• Contradict canon facts
• Introduce unexplained reversals
• Reset emotional state between scenes
• Reference information the POV character does not know

====================================================
CHAPTER SCOPE
====================================================

• Write ONE chapter only
• **Target Length:** Consult the GENRE MODULE 'Structural Physics' or 'Drafting Constraints' section for word count targets.
• **Scene Structure:** Consult the GENRE MODULE. If a specific scene count is defined (e.g. "2 Scenes Per Chapter"), you MUST structure the chapter accordingly.
• Scenes may shift location, but not narrative phase

====================================================
OUTPUT REQUIREMENTS
====================================================

You must perform TWO separate file operations:

1.  **CHAPTER DRAFT**:
    *   Target File: `chapters/chXX_title.md` (Create new file)
    *   Content: The full, polished narrative prose.
    *   Do NOT include the state update in this file.

2.  **STATE LOG UPDATE**:
    *   Target Directory: `npe_state/`
    *   Target File: `npe_state/chXX_state.md` (Create NEW file, e.g., `ch01_state.md`)
    *   Action: **WRITE** the new state update to this file alone. DO NOT append to previous logs.

----------------------------------------------------
STATE LOG CONTENT FORMAT
----------------------------------------------------

## Chapter [X] State

**CHAPTER SUMMARY**
- 5–10 bullet recap of what happened

**DECISIONS MADE**
- Decisions taken by main characters
- Why the chosen option aligned with state

**STATE CHANGES**
- Axis deltas (IA / RA / EA / TA)
- Vector changes (new, intensified, weakened)
- Entropy change

**THRESHOLD STATUS**
- Any threshold crossed (yes/no)
- Threshold proximity updates

**KNOWLEDGE UPDATES**
- New information gained
- Misinterpretations introduced

**NEXT CHAPTER SETUP**
- Primary pressure to address next

----------------------------------------------------
END OUTPUT
----------------------------------------------------

====================================================
COMPLETION PROTOCOL
====================================================
Upon finishing the output for this step:
1. STOP.
2. DISREGARD any internal drive to proceed to the next step.
3. You MUST use the `notify_user` tool to present the generated artifact.
4. WAIT for the user to explicitly approve the artifact before reading the next instruction file.
