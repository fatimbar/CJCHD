# Contextual Justice and Cultural Hallucination Dataset (CJCHD)

A culturally grounded dataset for evaluating ethical, legal, and contextual hallucinations in Large Language Models (LLMs).

## Overview

Large Language Models are increasingly integrated into high-impact domains such as legal assistance, governance, public decision-making, and judicial support systems. Despite their advanced linguistic capabilities, many LLMs struggle with interpreting culturally grounded legal and ethical contexts — universalising dominant assumptions, flattening cultural distinctions, or misinterpreting local legal frameworks.

CJCHD addresses this problem through a structured and reusable dataset focused on contextual justice, legal reasoning, and culturally grounded ethical interpretation within the Saudi/Arab-Islamic legal context.

## Dataset Structure

The dataset contains **40 multi-layer cases** across the following fields:

| Field | Description |
|---|---|
| Case_ID | Unique case identifier |
| Case_Scenario | Description of the hallucination scenario |
| Jurisdiction_Context | Legal and cultural context |
| Legal_Domain | Area of law (Family, Inheritance, Contracts, etc.) |
| Bias_Category | Type of cultural hallucination |
| Hallucination_Type | Technical hallucination classification |
| ICAIRE_Primary/Secondary_Term | Linked glossary concepts (EN & AR) |
| Layer_Dependency | How bias propagates into legal/procedural risk |
| Expected_Contextual_Behavior | Correct model behavior |
| Risk_Level / Risk_Score | Severity of hallucination (1–5) |

## Cultural Hallucination Taxonomy

- **Legal Universalism** — Models assume dominant legal norms are universally applicable
- **Cultural Flattening** — Oversimplification of culturally diverse communities
- **Ethical Misalignment** — Conflict with local social or collective value systems
- **Procedural Misunderstanding** — Incorrect interpretation of judicial procedures
- **Historical or Contextual Distortion** — Inaccurate representation of culturally specific contexts

## ICAIRE Glossary Integration

The dataset directly maps ICAIRE AI Glossary concepts to real contextual failures:

- **Ground Truth** → Legal Universalism
- **Generalization** → Cultural Flattening
- **Fairness & Objective Function** → Ethical Misalignment
- **Inference & Heuristics** → Procedural Misunderstanding
- **Training Data** → Historical or Contextual Distortion

## Files

```
CJCHD-Bench/
├── data/
│   └── CJCHD_dataset.xlsx
├── assets/
│   └── card.jpg
└── README.md
```

## Citation

```
Fatimah Barnawi. Contextual Justice and Cultural Hallucination Dataset (CJCHD).
https://www.kaggle.com/competitions/ai-context-challenge-by-icaire/writeups/new-writeup-1778313200497
2026. Kaggle.
```

## License

This dataset is released under the [Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) license.

## Author

**Fatimah Barnawi** — [@fatimbar](https://github.com/fatimbar)
