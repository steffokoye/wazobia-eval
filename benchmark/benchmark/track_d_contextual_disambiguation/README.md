# Wazobia Eval Track D

## Contextual Emotion Disambiguation

### Motivation

Many Nigerian Pidgin expressions change meaning depending on context, social relationship, tone, speaker intent, and cultural cues.

Traditional NLP benchmarks assume:

text → meaning

However, Nigerian communication often follows:

text + context → meaning

This benchmark track evaluates whether language models can correctly infer emotional meaning when identical expressions appear in different contexts.

---

## Example

Text:

"You don try well well."

Context A:
Friend wins scholarship.

Label:
celebration

---

Text:

"You don try well well."

Context B:
Friend damages your car.

Label:
sarcasm

---

Text:

"You don try well well."

Context C:
Junior employee exceeds target.

Label:
pride

---

Text:

"You don try well well."

Context D:
Politician makes obvious mistake.

Label:
contempt

---

## Research Goal

Measure how effectively language models resolve contextual ambiguity in Nigerian Pidgin language understanding.

---

Status:
Future Benchmark Track
Version 0.1
