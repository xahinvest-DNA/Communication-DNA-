# JUDGE LAYER

## Purpose
The first generated analysis should not be trusted blindly. A separate quality-control layer is needed.

## Judge responsibilities
The judge layer should check whether the generated analysis:
- separates observations from inferences;
- avoids overclaiming hidden intent;
- preserves uncertainty where evidence is weak;
- avoids generic advice;
- matches DNA structure rather than generic therapeutic language;
- produces grounded next moves.

## Common failure patterns to detect
- pseudo-depth with weak evidence;
- confidence inflation;
- motivational storytelling detached from text;
- emotionally comforting but strategically empty advice;
- pathologizing normal ambiguity;
- user-flattering confirmation bias.

## Minimal architecture pattern
- generator;
- critic / judge;
- final synthesizer.

## Product implication
Without a judge layer, the system will repeatedly regress into plausible but unreliable answers.