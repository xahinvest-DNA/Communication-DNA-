# MULTI_PASS_ANALYSIS

## Purpose
This document formalizes the idea that a strong DNA session should be built from multiple analytic passes rather than one generative response.

## Recommended pass structure

### Pass 1. Observable signal extraction
Return only textual and structural signals.
Do not infer motives yet.

### Pass 2. Hidden-dynamic hypotheses
Build possible motive / dynamic hypotheses from the extracted signals.

### Pass 3. Projection / distortion audit
Check where the user may be reading fantasy, fear, or wish rather than evidence.

### Pass 4. Position summary
Define the user’s current position in the dynamic.

### Pass 5. Possible move generation
Return a small set of grounded next moves consistent with the position.

### Pass 6. Final synthesis
Produce the user-facing answer from the previous passes.

## Why this matters
A single-step answer often produces blended reasoning. Multi-pass analysis enforces internal discipline and makes the output easier to evaluate and improve.
