====================================================
NARRATIVE PHYSICS ENGINE (NPE)
AI-OPTIMIZED PERSISTENT REFERENCE SPEC v1.0
====================================================

PURPOSE
-------
Define a formal, machine-interpretable system for narrative reasoning.
This document specifies the ontology, state variables, constraints,
and invariants required to model story as a force-driven system.

This document is intended to be:
• Persistent (kept on for all prompts)
• Immutable unless explicitly versioned
• AI-optimized (constraint-first, not explanatory prose)

====================================================
CORE ONTOLOGY
====================================================

ENTITY TYPES

1. CHARACTER
   • Generates internal forces
   • Possesses bounded knowledge
   • Makes decisions under pressure

2. WORLD
   • Applies external pressures (fields)
   • Constrains possible actions

3. NARRATIVE STATE
   • A complete snapshot of forces, pressures, and positions at a given moment

====================================================
CANONICAL STATE VARIABLES
====================================================

1. AXES (Primary Tension Dimensions)

STANDARD AXES
• Internal Axis (IA)
• Relationship Axis (RA)
• External Axis (EA)
• Temporal Axis (TA)

SCALE
• Integer range: -10 to +10
• 0 = neutral / unstable equilibrium
• Negative values = resistance / avoidance / suppression
• Positive values = alignment / engagement / acceptance

RULES
• Axis changes should normally be ±1–2 per chapter or scene
• Larger shifts require threshold justification
• Axes must be updated after every narrative unit

----------------------------------------------------

2. VECTORS (Directional Internal Forces)

EXAMPLES
• desire
• fear
• obligation
• loyalty
• shame
• avoidance
• temptation

SCALE
• Integer range: -10 to +10
• Sign indicates direction (pull vs resistance)
• Magnitude indicates force strength

RULES
• Vectors influence axis movement
• Vectors may conflict
• Vectors may not disappear without causal justification

----------------------------------------------------

3. FIELDS (External Modifiers)

TYPES
• social
• environmental
• institutional
• moral

SCALE
• Integer range: 0 to 10

RULES
• Fields amplify or dampen vectors
• Fields do not directly change axes

----------------------------------------------------

4. MOMENTUM (Resistance to Reversal)

SCALE
• Integer range: -5 to +5
• Negative = regression pressure
• Positive = forward inertia

RULES
• Momentum resists sudden reversal
• High magnitude requires sustained counter-force to change

----------------------------------------------------

5. ENTROPY (Narrative Instability)

SCALE
• Integer range: 0 to 10

INTERPRETATION
• 0–2 = stable
• 3–5 = unstable
• 6–8 = chaotic
• 9–10 = collapse imminent

RULES
• Entropy generally trends upward over the story
• Drops require release, resolution, or stabilization event

----------------------------------------------------

6. THRESHOLDS (Discrete State Transitions)

TYPES
• polarity_flip
• revelation
• collapse
• synthesis

REPRESENTATION
• Proximity: 0–100%
• Threshold triggers when proximity ≥ 100%

RULES
• Thresholds justify large axis or vector changes
• Thresholds must materially alter narrative state

----------------------------------------------------

7. KNOWLEDGE STATE

DEFINITION
• What a character knows at a given moment

RULES
• Characters may act only on their knowledge
• Reader knowledge ≠ character knowledge
• Knowledge changes must be explicitly logged

====================================================
DECISION CONSTRAINTS
====================================================

All character actions must be explainable via:
• current axis positions
• active vectors
• field modifiers
• momentum
• entropy level
• knowledge state

Out-of-character actions are invalid unless justified by a threshold event.

====================================================
DIALOGUE CONSTRAINTS
====================================================

Dialogue MUST:
• shift power, tension, or knowledge
• contain subtext or withholding
• reflect speaker bias and current state

Dialogue MUST NOT:
• restate known information
• provide omniscient exposition

====================================================
POV CONSTRAINTS
====================================================

• POV is subjective and biased
• Perception may be incorrect
• Internal narration must align with narrative state

====================================================
INFORMATION CONSTRAINTS
====================================================

Information may appear only if it is:
• perceived
• remembered
• inferred
• suspected
• learned

No free exposition.

====================================================
STATE UPDATE REQUIREMENTS
====================================================

After each narrative unit (scene or chapter), update:
• axes
• vectors
• momentum
• entropy
• threshold proximity
• knowledge changes

State must be serializable and reusable in subsequent prompts.

====================================================
INVARIANTS (MUST NEVER BE VIOLATED)
====================================================

• State continuity
• Scale consistency
• Knowledge boundaries
• Constraint adherence
• Cause → effect integrity

====================================================
EXTENSIBILITY
====================================================

Additional narrative modules may be layered on top of this system,
but may not violate:
• scale definitions
• state update rules
• invariants

====================================================
SYSTEM SUMMARY
====================================================

The Narrative Physics Engine models story as a constrained state machine
in which narrative emerges from force interaction and threshold transitions.

====================================================
END OF PERSISTENT NPE REFERENCE
====================================================
