# CSS5120: CL-Lab1-Text-Commons

This is the repository for the **CSS5120: Computational Linguistics Lab 1 Assignment**.

In this assignment, each student will contribute a data source of their interest. You are also encouraged to reference and use data contributed by other students in future projects. We hope everyone will act as both a **contributor** and a **beneficiary** of this data collection.

## Assignment Requirements

The core objective of this Lab is **non-crawler** text data collection.

1.  **Data Source Requirements**:
    *   Please use **Public Datasets** (HuggingFace, Arxiv, Kaggle, Common Crawl, or Published Datasets), **Official APIs** (Wikipedia, Reddit, The Guardian, etc.), or **Digital Archives** (Project Gutenberg).
    *   We encourage mining **"long-tail" domains** (e.g., movie scripts, legal documents, lyrics, ancient texts, code comments, etc.).

2.  **Submission Standards**:
    *   Each student must submit **one dataset** accompanied by a detailed documentation file.

3.  **Data Format**:
    *   Recommended formats: **`.txt`**, **`.jsonl`**, **`.csv`**, or other common plain text formats.
    *   **Size & Representativeness**: There are no strict requirements on data size or representativeness. The goal is to demonstrate the availability of the data source.
        *   If collecting via **API**, returning **100 to 500 records** is sufficient.
        *   If submitting a **public dataset**, you may provide the full dataset OR the first 100 rows with a direct link included in the readme.

---

## Submission Guide

Please follow these steps to submit your assignment via the **Pull Request** workflow:

1.  **Fork** this repository to your own GitHub account.
2.  Create a new folder under the `data/` directory.
    *   **Naming Convention**: `Name_DataTopic`
    *   *Example: `ZhangSan_Shakespeare`*
3.  Upload the following two files into your folder:
    *   **Data File** (The dataset itself)
    *   **Documentation**: `Yourname_README.md` (see the template below).
4.  Submit a **Pull Request (PR)** to the `main` branch of this repository.

### Directory Structure Example

```text
CL-Lab1-Text-Commons/
├── README.md                       <-- (The file you are reading)
├── data/
│   ├── ZhangSan_Shakespeare/   <-- Your Folder
│   │   ├── sonnets.txt                 <-- Your Data
│   │   └── Zhangsan_README.md                   <-- Your Metadata Card
│   ├── LiSi_LegalCases/
│   │   ├── cases_sample.csv
│   │   └── LIsi_README.md
│   └── ...
```

---

## Your Data's Readme Template (Yourname_README.md)

Please use the following template.

### Naming Convention

Please add your name as a prefix to the filename of your data's readme (e.g., "Yourname_readme.md")

And Please ensure your file includes the following content:

### 1. Metadata Card

| Field | Content |
| :--- | :--- |
| **Contributor** | [Your Name] |
| **Data Source** | [Source Name & URL, e.g., Project Gutenberg (http://...)] |
| **Domain/Category** | [e.g., Literature / Sentiment Analysis / Medical / Dialogue] |
| **Language** | [e.g., English (Early Modern) / zh-CN] |
| **Data Scale** | [e.g., 154 Sonnets / 5MB / 10k lines] |
| **File Format** | [.txt / .jsonl / .csv] |

### 2. Dataset Introduction
Briefly describe what this dataset contains, its characteristics, how you obtained it and what research question you plan to use it for.
