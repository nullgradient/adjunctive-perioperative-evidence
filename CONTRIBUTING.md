# Contributing

Welcome, and thank you for your interest in contributing! There are several ways in which you can contribute and all are appreciated.

The goal of this project is to collect and verify evidence regarding adjunctive interventions for surgical care. Since much of the content is and has been generated with AI assistance, human verification is extremely important and will greatly improve the value of this information.

Please note that this project has adopted the [Contributor Covenant](<https://www.contributor-covenant.org/version/3/0/>) as its [Code of Conduct](CODE_OF_CONDUCT.md), and all contributors must adhere to it.
 
## How to Contribute

### 1. Verifying Existing Research

The most valuable contribution you can make is verifying the cited research.

- **Check the source:** Read the abstract or full text of the cited paper.
- **Verify the claim:** Ensure the paper actually supports the claim made in this repository.
- **Mark as verified:** If verified, please add a note (e.g., `[Human Verified]`) next to the citation. If the citation is incorrect or hallucinated, please remove it or flag it.

### 2. Adding New Claims

You can add new claims regarding perioperative adjuncts.

- **Location:** Add a new Markdown document for the intervention under the `evidence/` folder using the appropriate subfolder, e.g. `evidence/supplements/`, `evidence/diet-and-lifestyle/`, etc.
- **Format:** The title and introduction should clearly communicate the intervention and the specific claim.
- **Evidence:** Provide citations (DOI, PubMed link, or standard citation format).
- **Categorize:** Classify evidence as Supporting, Refuting, or Mixed by adding an entry to [`CURRENT-EVIDENCE-SUMMARY.md`](evidence/CURRENT-EVIDENCE-SUMMARY.md).

### 3. Updating Existing Claims

If you find new evidence that contradicts or nuances an existing claim, please update the entry.

### 4. Reporting Problems

If you notice errors, missing citations, unclear wording, or other issues but aren't ready to submit a change yourself, please open an issue describing the problem. This is a valuable way to improve quality and help guide future contributions.

## Style Guide

- Keep formatting consistent with existing Markdown files.
- Avoid medical advice; focus on summarizing research findings.

## Disclaimer

Remember, this repository is **not medical advice**. Ensure all contributions maintain this distinction.
