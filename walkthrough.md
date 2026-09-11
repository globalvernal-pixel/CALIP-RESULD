# Caliph Life School — Student Result Portal Summary & Documentation

## 1. Overview of Code Changes

The **Caliph Life School — Student Result Portal** has been created and updated with the exact examination database transcribed directly from the official school mark sheets.

### Files Modified & Created:
- **`index.html`**:
  - Structured search interface featuring the official **Caliph Life School logo**, school title, and examination subtitle.
  - Three validated search fields: **Student Name**, **Roll Number / Register Number**, and **Class / Batch** dropdown (Class 1A, 1B, 2A, 2B, Class 1–10).
  - Dynamic result card displaying full student metadata, subject-wise marks table, summary statistics, overall status badges, and print controls.
- **`styles.css`**:
  - Institutional design system utilizing deep royal navy (`#0f2744`, `#1e3a6e`) and gold accent highlights (`#d4a843`).
  - Animated background gradients, micro-interactions, responsive flex/grid layouts, and dedicated `@media print` CSS for A4 mark sheet printing.
- **`data/students.js`**:
  - Full dataset containing **88+ real student records** across Classes **2B (C2B)**, **2A (C2A)**, **1B (S1B)**, and **1A (S1A)** transcribed directly from the school mark sheet registers.
- **`app.js`**:
  - Case-insensitive search engine matching student names, roll numbers (e.g. `C2B-05`, `S1A-04`), and flexible class filtering.
  - Validation handling with animated toast notification popups.

---

## 2. Examination Subjects

All student records are evaluated across the 5 core Islamic Studies & General subjects of Caliph Life School:

1. **CEE** (Continuous & Comprehensive Evaluation) — Max Marks: 100 | Pass: 35
2. **FIQH** (Islamic Jurisprudence) — Max Marks: 100 | Pass: 35
3. **PRACTICAL ISLAM** — Max Marks: 100 | Pass: 35
4. **THE MOST BEAUTIFUL NAMES** (Asma-ul-Husna / Seerah) — Max Marks: 100 | Pass: 35
5. **LIFE OF PROPHET** (Seerah & Islamic History) — Max Marks: 100 | Pass: 35

---

## 3. Transcribed Student Mark List

### Class 2B (C2B)
| Rank | Roll No | Student Name | CEE | FIQH | PRACTICAL ISLAM | BEAUTIFUL NAMES | LIFE OF PROPHET | Total | % | Status |
|:---:|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 1 | C2B-05 | AHAMMED UNNAIS | 65.33 | 85.0 | 67.0 | 71.5 | 84.0 | 372.83 | 74.57% | PASSED |
| 2 | C2B-27 | MUHAMMED SHAMIL | 70.67 | 82.0 | 62.0 | 68.0 | 78.0 | 360.67 | 72.13% | PASSED |
| 3 | C2B-13 | AZEEM MAMPAT | 65.33 | 87.0 | 65.0 | 67.0 | 73.5 | 357.83 | 71.57% | PASSED |
| 4 | C2B-09 | AMIR MUHAMMED | 69.33 | 87.5 | 61.0 | 60.0 | 74.5 | 352.33 | 70.47% | PASSED |
| 5 | C2B-23 | MUHAMMED FAZIL | 57.33 | 86.0 | 65.0 | 67.0 | 75.0 | 350.33 | 70.07% | PASSED |
| 6 | C2B-32 | MUHAMMED ZAYAN | 56.00 | 89.0 | 52.0 | 69.5 | 76.0 | 342.50 | 68.50% | PASSED |
| 7 | C2B-06 | AHMMED SHAHIN | 72.00 | 72.0 | 58.5 | 66.0 | 69.5 | 338.00 | 67.60% | PASSED |
| 8 | C2B-01 | AAMIR SHAN | 54.67 | 82.0 | 60.0 | 66.0 | 74.5 | 337.17 | 67.43% | PASSED |
| 9 | C2B-08 | AMIR BIN JAFAR | 82.67 | 80.5 | 46.0 | 57.5 | 66.5 | 333.17 | 66.63% | PASSED |
| 10 | C2B-39 | SAYYID SHAHZAD | 49.33 | 87.0 | 58.0 | 59.0 | 74.5 | 327.83 | 65.57% | PASSED |
| 11 | C2B-12 | AYMAN NOUFAL | 49.33 | 83.0 | 56.5 | 61.5 | 73.5 | 323.83 | 64.77% | PASSED |
| 12 | C2B-31 | MUHAMMED YASIN | 56.00 | 76.0 | 52.5 | 65.0 | 70.0 | 319.50 | 63.90% | PASSED |

### Class 2A (C2A)
| Rank | Roll No | Student Name | CEE | FIQH | PRACTICAL ISLAM | BEAUTIFUL NAMES | LIFE OF PROPHET | Total | % | Status |
|:---:|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 1 | C2A-05 | FATHIMA HANIYA | 62.67 | 88.0 | 70.0 | 70.5 | 64.0 | 355.17 | 71.03% | PASSED |
| 2 | C2A-01 | AYESHA RIDA | 52.00 | 87.0 | 62.0 | 70.0 | 63.0 | 334.00 | 66.80% | PASSED |
| 3 | C2A-04 | FATHIMA JUNA | 33.33 | 88.0 | 63.0 | 78.5 | 63.0 | 325.83 | 65.17% | FAILED |
| 4 | C2A-10 | NATHASHA MARYAM | 52.00 | 79.0 | 63.0 | 53.0 | 63.0 | 310.00 | 62.00% | PASSED |

### Class 1A (S1A)
| Rank | Roll No | Student Name | CEE | FIQH | PRACTICAL ISLAM | BEAUTIFUL NAMES | LIFE OF PROPHET | Total | % | Status |
|:---:|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 1 | S1A-04 | FATHIMA BATOUL | 81.33 | 89.0 | 69.0 | 79.0 | 79.0 | 397.33 | 79.47% | PASSED |
| 2 | S1A-03 | FATHIMA AMNA | 57.33 | 89.0 | 79.0 | 78.0 | 71.0 | 374.33 | 74.87% | PASSED |
| 3 | S1A-08 | REYAH RIZWAN | 61.33 | 89.0 | 68.0 | 76.0 | 77.0 | 371.33 | 74.27% | PASSED |
| 4 | S1A-01 | AFRIN FATHIMA MOHAMED SHAFEEK | 36.00 | 51.0 | 53.0 | 60.0 | 54.0 | 254.00 | 50.80% | PASSED |

---

## 4. How to Search & Verify Results
1. Enter any student's name in the **Student Name** field (e.g. `AHAMMED UNNAIS` or `FATHIMA`).
2. Enter their exact register/roll number in the **Roll Number** field (e.g. `C2B-05`, `C2A-05`, `S1A-04`).
3. Select their corresponding class batch from the **Class / Batch** dropdown (`Class 2B (C2B)`, `Class 2A (C2A)`, `Class 1A (S1A)`, `Class 1B (S1B)`).
4. Click **Check Result** to view the full mark sheet.
5. Click **Print / Download Marksheet (PDF)** for standard A4 printing.
