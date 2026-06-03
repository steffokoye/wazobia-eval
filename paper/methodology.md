# Methodology

## Benchmark Design

Wazobia Eval evaluates language models on culturally grounded Nigerian Pidgin language understanding.

The benchmark consists of four tracks:

### Track A: Emotion Classification

Models classify text into one of sixteen emotion categories.

### Track B: Sarcasm Detection

Models determine whether a statement is sincere or sarcastic.

### Track C: Cultural Reasoning

Models answer questions requiring understanding of Nigerian cultural context.

### Track D: Contextual Emotion Disambiguation

Models infer emotional meaning when identical expressions appear in different contexts.

---

## Evaluation Procedure

Each model receives identical prompts.

Model outputs are recorded without modification.

Predictions are compared against gold labels.

Metrics include:

* Accuracy
* Per-category accuracy
* Error analysis
* Qualitative observations

---

## Human Review

Human annotators review benchmark entries and verify label quality.

Inter-Annotator Agreement (IAA) procedures are incorporated to improve benchmark reliability.
