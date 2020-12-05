---
language: multilingual
tags:
- zero-shot-classification
- nli
- pytorch
datasets:
- mnli
- xnli
- anli
license: mit
pipeline_tag: zero-shot-classification
widget:
- text: "La película empezaba bien pero terminó siendo un desastre." 
  labels: "positivo, negativo, neutral"
- text: "¿A quién vas a votar en 2020?"
  labels: "Europa, elecciones, política, ciencia, deportes"
---

### XLM-RoBERTa-large-XNLI-ANLI

XLM-RoBERTa-large model finetunned over several NLI datasets, ready to use for zero-shot classification.

Here are the accuracies for several test datasets:

|                             | XNLI-es | XNLI-fr | ANLI-R1 | ANLI-R2 | ANLI-R3 |
|-----------------------------|---------|---------|---------|---------|---------|
| xlm-roberta-large-xnli-anli | 93.7% | 93.2% | 68.5%  | 53.6%  | 49.0%  |