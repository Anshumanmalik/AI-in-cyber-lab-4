# Lab Assignment 4 – Explainable and Privacy-Aware AI Threat Alert

**Student:** Anshuman Malik  
**Roll No.:** 2401010086  
**Course:** B.Tech CSE (Core)  
**Subject:** ENSP355 – AI in Cyber Security  
**Platform:** Google Colab / Python

## Project overview

This notebook implements the Lab 4 tasks from the AI in Cyber Security lab manual:

1. **Baseline predictions with confidence:** Predicts Normal/Suspicious for five sanitized login records and reports the maximum class probability.
2. **Feature importance and explanation:** Displays a sorted feature-importance table, a bar chart, and explanations for the top three features.
3. **Controlled sensitivity test:** Changes only `failed_logins` from 2 to 8 for the fifth sample and compares the prediction and confidence.
4. **Privacy masking:** Masks IP addresses and account IDs before displaying the privacy-aware output, and lists four responsible-use rules.
5. **Responsible alert generation:** Assigns Low/Medium/High severity, provides reasons and recommended actions, and indicates whether human review is required.

## Files

- `Lab_4_Explainable_Privacy_Aware_AI_Threat_Alert.ipynb` – Google Colab notebook.

## Run in Google Colab

1. Download the `.ipynb` notebook.
2. Open [Google Colab](https://colab.research.google.com/).
3. Select **File → Upload notebook** and upload the downloaded notebook.
4. Select **Runtime → Run all**.
5. Check that all tables and the feature-importance chart are displayed.
6. Save the notebook to Google Drive and use **Share** to create a shareable link, as required by your course.

## Dataset note

The Lab 4 manual says to reuse the Lab 2 Decision Tree and dataset. Those Lab 2 source files were not included with the Lab 4 upload, so this notebook uses a small illustrative training dataset to run end-to-end. Replace the illustrative training data with the original Lab 2 data/model if your instructor has supplied them.

## Submission evidence

Capture or retain the following outputs:

- Five-row baseline prediction/confidence table and lowest-confidence record.
- Feature-importance table and chart, with top-three explanations.
- Before/after sensitivity comparison.
- Masked identifier table and four privacy/responsible-use rules.
- Final alert table showing severity, reason, recommended action, and human-review status.
- Conclusion and shareable Colab link.

## Important limitation

This is a small classroom prototype. Confidence is not certainty, feature importance does not prove causation, and predictions may not generalize to real-world login activity. High-risk or uncertain outcomes require authorized human review. Do not use the notebook to automatically punish users or block accounts.
