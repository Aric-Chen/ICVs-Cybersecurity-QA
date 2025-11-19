# ICV-Cybersecurity-QA Dataset

This repository provides the question–answer (Q&A) dataset used in our paper on intelligent connected vehicles (ICVs) cybersecurity and data security compliance.

To support the study, we constructed a high-quality Q&A dataset for ICVs cybersecurity standards and regulations, focusing on aspects relevant to real-world compliance. Based on 108 collected documents (48 laws and regulations, 60 technical standards and normative documents), approximately 10 representative Q&A pairs were manually assisted and extracted from each source. The questions cover diverse types (e.g., term interpretation, clause analysis, cross-document reasoning) to ensure domain professionalism and answer accuracy.

The resulting dataset was randomly split into:
- **50% training set** – for prompt optimization and model training;
- **50% test set** – for independent evaluation and comparative analysis.

## Knowledge Base (KB) Source Tables

In addition to the Q&A files, this repository also includes supplementary tables that document the knowledge sources behind all Q&A pairs.

The Knowledge Base (KB) that supports the research focuses on the domain of cybersecurity and data security for intelligent connected vehicles (ICVs) and currently contains **108 key documents**:

- **Table 1** – Summary of the 48 relevant laws and regulations.  
- **Table 2** – Summary of the 60 relevant technical standards and normative documents.

These tables serve as a complete inventory of the KB used to construct the dataset and allow users to trace each Q&A pair back to its original regulatory or standard document. To promote further research in this field (e.g., AI-driven automated compliance analysis), we share this KB inventory openly. Given the rapid evolution of ICVs security regulations and standards, the KB will be continuously maintained and updated to incorporate the latest industry developments.

## Repository Structure (example)

- `training_dataset_final.json` – Q&A pairs in the training set.  
- `test_dataset_final.json` – Q&A pairs in the test set.  
- `APEO-RAG_Supplementary_KB_Inventory.pdf` - Supplementary material listing all **108 knowledge-source documents** (48 laws and regulations, 60 technical standards and normative documents) that provide the ground-truth basis for the Q&A dataset.



