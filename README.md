# SMM4H-HeaRD-2025-Task-4-Detection-of-Insomnia-in-Clinical-Notes

This repository contains my implementation for the SMM4H-HeaRD 2025 Shared Task 4: Detection of Insomnia in Clinical Notes.

The goal of this task is to develop a multi-label classification system that automatically identifies insomnia based on clinical notes. The system predicts the satisfaction of predefined insomnia rules (Definition 1, Definition 2, Rule A, Rule B, and Rule C) using rule and transformer-based approaches.

## Subtasks

The task is divided into three subtasks:
	•	Subtask 1:
Predict the satisfaction of two definitions and three rules for each clinical note, treating the problem as five independent binary classification tasks.
	•	Subtask 2:
Perform multi-label classification, jointly predicting the satisfaction of all five definitions/rules per clinical note.
	•	Subtask 3:
Predict an overall insomnia label (yes/no) for each clinical note by aggregating the individual definition/rule predictions according to specific aggregation rules provided by the organizers.


⸻

## Dataset
	•	Clinical notes are derived from the MIMIC-III database.
	•	Labels are curated based on predefined insomnia definitions and rules provided by the shared task organizers.
	•	Access to MIMIC-III requires credentialed access through PhysioNet.

⸻

## Methods
	•	Data preprocessing and formatting of clinical notes.
	•	Fine-tuning transformer models such as:
	•	ClinicalBERT
	•	BlueBERT
	•	Longformer (for longer notes)
	•	Multi-label classification setup with custom loss functions.
	•	Evaluation based on F1-score, precision, recall, and Rouge-L scores.

⸻

## Frameworks and Tools
	•	Python 3.9+
	•	PyTorch
	•	Hugging Face Transformers
	•	Scikit-learn
	•	Pandas, NumPy

## References
	•	SMM4H-HeaRD 2025 Task 4 - Insomnia Detection
	•	MIMIC-III Clinical Database

⸻

## Acknowledgements
	•	Special thanks to the organizers of SMM4H-HeaRD 2025.
	•	MIMIC-III Database access and use governed under PhysioNet credentialed data use agreement.

⸻

## Tags: #SMM4H2025 #ClinicalNLP #InsomniaDetection #TransformerModels #MultiLabelClassification

⸻

