# FOUNDATION_BEFORE_IMPLEMENTATION

## Purpose
This document records what must exist before building another public-facing bot or app surface.

## Required foundation items

### 1. DNA Analysis Spec v1
A formal specification of:
- task types;
- router fields;
- analysis stages;
- output blocks;
- judge checks;
- quality standards.

### 2. Ethalon case set
A manually prepared set of high-quality reference analyses demonstrating the desired DNA reasoning style.

### 3. Working taxonomy
At minimum:
- task types;
- user states;
- material types;
- dynamic types;
- projection types;
- move types.

### 4. Multi-pass engine design
The product must be able to separate signal extraction, hypothesis generation, distortion checking, position summary, move generation, and final synthesis.

### 5. Evaluation loop
There must be a way to judge whether the system became better in practice, not only more eloquent.

## Product lesson
Do not start with interface-first implementation. Start with analysis-core discipline.
