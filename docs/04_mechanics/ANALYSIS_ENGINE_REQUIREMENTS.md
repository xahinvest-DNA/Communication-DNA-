# ANALYSIS ENGINE REQUIREMENTS

## Core principle
Communication DNA should not be implemented as a single-step answer generator. It should be implemented as a staged analysis engine.

## Minimum internal stages

### Stage 1. Intake normalization
Normalize the input into a structured case:
- material provided;
- user question;
- context notes;
- emotional intensity clues.

### Stage 2. Router
Classify the case into:
- material type;
- task type;
- user state;
- context depth;
- reading risk;
- output depth recommendation.

### Stage 3. Signal extraction
Extract only what is observable in the material.
No interpretation yet.

### Stage 4. Hypothesis generation
Generate likely hidden dynamics from signals.
These remain hypotheses, not facts.

### Stage 5. User-side distortion check
Estimate where the user may be projecting, idealizing, catastrophizing, seeking permission, or otherwise distorting the reading.

### Stage 6. Position detection
Summarize the user’s actual position in the dynamic.

### Stage 7. Move generation
Generate only grounded possible moves that fit the actual position.

### Stage 8. Final synthesis
Create the final response using the validated internal outputs.

## Required output discipline
The final system should clearly separate:
- what is seen;
- what is inferred;
- what is uncertain;
- what belongs to the user side;
- what moves are available.

## Product warning
If these stages collapse into one answer, the product drifts back toward shallow chatbot behavior.