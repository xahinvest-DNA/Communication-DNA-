# PROJECT NAV

## Repository status
This repository is currently in a theory-first phase for Communication DNA, focused on personal mode and the internal analysis engine required to avoid shallow chatbot behavior.

## Where to start

### 1. Foundation
- `docs/00_foundation/PROJECT_SCOPE.md`
- `docs/00_foundation/CONTEXT_AND_THEORY.md`

### 2. Product space
- `docs/01_product-space/PRODUCT_FORMS.md`
- `docs/01_product-space/PERSONAL_MODE_MAP.md`
- `docs/01_product-space/PERSONAL_MODE_HIERARCHY.md`

### 3. User task structure
- `docs/02_user-jobs/JTBD_PERSONAL.md`
- `docs/02_user-jobs/HIDDEN_TASKS_AND_EFFECTS.md`
- `docs/02_user-jobs/PERSONAL_TASK_TAXONOMY.md`

### 4. Scenario layer
- `docs/03_modes/USER_SCENARIOS.md`
- `docs/03_modes/USE_CASE_LIBRARY.md`

### 5. Mechanics / analysis core
- `docs/04_mechanics/ANALYSIS_MODEL.md`
- `docs/04_mechanics/SESSION_OUTPUTS.md`
- `docs/04_mechanics/SIGNAL_LIBRARY.md`
- `docs/04_mechanics/DECODER_MIRROR_NAVIGATOR.md`
- `docs/04_mechanics/WHY_SIMPLE_BOT_FAILS.md`
- `docs/04_mechanics/ANALYSIS_ENGINE_REQUIREMENTS.md`
- `docs/04_mechanics/MULTI_PASS_ANALYSIS.md`
- `docs/04_mechanics/JUDGE_LAYER.md`
- `docs/04_mechanics/DNA_ONTOLOGY_V0.md`

### 6. Risk and ethics
- `docs/05_risks/RISKS_AND_GUARDRAILS.md`
- `docs/05_risks/ETHICS_AND_BOUNDARIES.md`

### 7. Research and validation
- `docs/06_research/RESEARCH_QUESTIONS.md`
- `docs/06_research/VALIDATION_PLAN.md`
- `docs/06_research/EVALUATION_CRITERIA.md`
- `docs/06_research/FOUNDATION_BEFORE_IMPLEMENTATION.md`

### 8. Decisions and unresolved tension
- `docs/07_decisions/DECISIONS_LOG.md`
- `docs/07_decisions/OPEN_QUESTIONS.md`
- `docs/07_decisions/CONFLICTS.md`

### 9. Working notes
- `docs/08_working-notes/THEORY_LOG.md`
- `docs/08_working-notes/POSSIBLE_MOVES.md`
- `docs/08_working-notes/POSITIONING_DRAFTS.md`

### 10. Prompts
- `docs/09_prompts/THEORY_SESSION_PROMPT.md`
- `docs/09_prompts/DEEP_RESEARCH_PROMPT.md`

## Current conceptual center
The current center of gravity is no longer only personal-mode theory. It is the transition from product theory to a real DNA analysis engine.

Key ideas now fixed in the repository:
- personal mode should be organized by task type, not by relationship label;
- a weak bot fails because it uses one-step generation instead of staged analysis;
- a strong product needs Decoder -> Mirror -> Navigator logic;
- the system should use routing, multi-pass analysis, a judge layer, and explicit ontology;
- implementation should start from the analysis core, not from the interface.

## Recommended next document
The next central document to create is:
- `docs/04_mechanics/DNA_ANALYSIS_SPEC_V1.md`

This should unify router, analyzer, judge, ontology, output structure, and evaluation logic into one working specification.
