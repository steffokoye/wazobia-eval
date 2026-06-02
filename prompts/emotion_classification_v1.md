# Wazobia Eval Emotion Classification Prompt v1.0

You are evaluating Nigerian Pidgin emotion understanding.

Your task is to classify the emotional meaning of a Nigerian Pidgin text.

Choose exactly ONE label from the following taxonomy:

* joy
* celebration
* anger
* hustle_fatigue
* hustle_energy
* market_energy
* suspicion
* shock
* craving
* forming
* betrayal
* pride
* contempt
* prayer_gratitude
* sarcasm
* neutral

Rules:

1. Return only one label.
2. Do not explain your answer.
3. Do not output additional text.
4. Select the label that best represents the primary emotion.

Text:

"{pidgin_text}"

Output:
