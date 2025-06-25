# 🧠 AI-Powered Resume Screening System using NLP and TF-IDF

This project automates the resume screening process using **Natural Language Processing (NLP)** and **TF-IDF-based semantic similarity**, helping recruiters efficiently shortlist candidates based on their relevance to a given job description (JD).

---

## 📌 Problem Statement

Recruiters often spend hours manually reviewing resumes to match candidates with job requirements — a process that's time-consuming, subjective, and prone to overlooking qualified applicants.

---

## ✅ Solution Overview

This system analyzes resumes and ranks candidates based on a composite score derived from:

- ✅ **Skill Overlap** — Matching skills between resume and JD
- 🎓 **Education Match** — Relevant degree detection
- 🧾 **Experience Estimation** — Years of experience using regex
- 🧠 **Semantic Similarity** — TF-IDF and cosine similarity to compare resume-JD context

---

## 📂 Dataset

- **25 synthetic resumes** created in CSV format
- Fields: `Name`, `Email`, `Phone`, `Summary`, `Skills`, `Education`, `Experience`, `Projects`, `Certifications`

---

## 🛠️ Tech Stack

- **Language**: Python
- **Libraries**: pandas, scikit-learn, re, ipywidgets, matplotlib
- **NLP**: TF-IDF Vectorizer, Cosine Similarity
- **Dashboard**: Jupyter Notebook + ipywidgets

---

## ⚙️ Key Features

- ✨ Cleaned and preprocessed resume data
- ✅ Parsed job description into required skills
- 📊 Scored resumes across 4 dimensions (skills, education, experience, context)
- 🔢 Ranked candidates using a weighted composite score
- 🧩 Built an **interactive dashboard** to:
  - Filter by candidate name or experience
  - View full profiles
  - Export filtered shortlists to CSV

---

## 📈 Sample Output

| Name           | Final Combined Score |
|----------------|----------------------|
| Priya Sharma   | 2.84                 |
| Amit Khanna    | 1.43                 |
| Shruti Shah    | 1.42                 |

---



## 🚀 How to Run

1. Clone this repo  
   `git clone https://github.com/yourusername/resume-screening-nlp.git`

2. Install dependencies  
   `pip install -r requirements.txt`

3. Open the notebook  
   `Jupyter Notebook > Resume_Screening_System.ipynb`

---

## 📤 Output

- Ranked candidate list
- Downloadable CSV for recruiter handoff
- Interactive visualizations in notebook

---

## 📌 Conclusion

This project proves how AI can enhance hiring workflows — reducing manual effort and improving decision quality by surfacing the most relevant resumes using both keyword and semantic insights.

---

## 📬 Contact

**Author**: [Manjiri Gajmal]  
📧 Email: careermanjiri@gmail.com  
🔗 LinkedIn: [www.linkedin.com/in/manjirigajmal](www.linkedin.com/in/manjirigajmal)

---

