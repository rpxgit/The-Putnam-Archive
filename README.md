# ***The Putnam Archive***
This unofficial repository contains problem statements, solutions, and competition results for recent years. I will attempt to keep up with this complete archive of the William Lowell Putnam Mathematical Competition exams (1985–Present) in LaTeX (.tex) and PDF formats. 

# 🏆 Putnam Mathematical Competition Archive

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)]()

A structured Git mirror and offline archive of the **William Lowell Putnam Mathematical Competition** papers. This repository provides an intuitive, hierarchical structure for raw exam questions, complete solution papers, and historical statistics spanning from 1985 to the present.

---

## 🗺️ Archive Overview

The repository is divided by category (Problems vs. Solutions), and then organized chronologically by year to allow for clean browsing and scalable storage.

* **1995 – Present:** ✨ **Complete Sets** — Full `.tex` and `.pdf` coverage for both Exam Problems and Solutions.
* **1985 – 1994:** 📝 **Problems Only** — Full `.tex` and `.pdf` coverage for Exam Problems. Solutions are not available in this archive range.

### 📊 Format Availability Matrix

| Timeline | Problems (`.tex`) | Problems (`.pdf`) | Solutions (`.tex`) | Solutions (`.pdf`) | Dataset Status |
| :--- | :---: | :---: | :---: | :---: | :--- |
| **1995 – Present** | ✅ Yes | ✅ Yes | ✅ Yes | ✅ Yes | 🟢 Full Problems + Solutions |
| **1985 – 1994** | ✅ Yes | ✅ Yes | ❌ *N/A* | ❌ *N/A* | 🟡 Exam Statements Only |

---
## ⚖️ Copyright & Attributions

* **Problems:** The text and compilation of the exam questions are copyrighted by the **Mathematical Association of America (MAA)**. They are included here for educational, archival, and non-commercial study purposes.
* **Solutions:** The solution documents available from 1995 onward were compiled using various collaborative academic efforts by **Manjul Bhargava, Kiran Kedlaya, and Lenhard Ng**. 
---
## 🛠️ Compilation Note (For `.tex` Files)
To compile the source `.tex` documents locally, make sure you have a standard LaTeX distribution installed (such as TeX Live, MiKTeX, or MacTeX). 

You can compile any individual file via your CLI:
```bash
pdflatex 1995_problems.tex
```
----


## 📁 Directory Structure

The repository utilizes a hybrid structure separated by category to prevent spoilers and keep files cleanly organized by year:

```text
├── Problems without Solutions (1985-1994)/                  # Original Exam Sheets without Solutions
│   ├── Tex/
│   │   ├── 1985.tex
│   │   └── ...
│   ├── PDF/
│   │   ├── 1985.pdf
│   │   └── ...
│   │
├── Problems & Solutions (1985-1994)/                       # Original Exam Sheets with Solutions
│   ├── TeX/
│   │   ├── 1995.tex
│   │   └── 1995s.tex
│   ├── PDF/                                                # Compiled with Solutions
│   │   ├── 1995.pdf
│   │   └── 1995s.pdf
│   |
└── README.md








