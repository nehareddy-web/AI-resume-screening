<!-- ============================================================
  HORROR README - AI Resume Screening System
============================================================= -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,40:3B0000,100:8B0000&height=270&section=header&text=THE%20PILE&fontColor=E50914&fontSize=80&fontAlignY=38&animation=blinking&desc=AI%20Resume%20Screening%20System&descAlignY=62&descSize=24&descColor=ffffff" width="100%" alt="The Pile"/>

<img src="https://readme-typing-svg.demolab.com?font=Creepster&size=28&duration=2800&pause=900&color=E50914&center=true&vCenter=true&width=850&height=60&lines=5%2C200+resumes.+One+recruiter.;The+pile+kept+growing...;Somewhere+inside+it%2C+the+perfect+candidate+was+hiding.;The+machine+found+them+first." alt="Typing SVG"/>

<br/>

![Rating](https://img.shields.io/badge/RATED-TV--MA-E50914?style=for-the-badge)
![Genre](https://img.shields.io/badge/GENRE-NLP_THRILLER-000000?style=for-the-badge&labelColor=000000&color=8B0000)
![Resumes](https://img.shields.io/badge/RESUMES_PROCESSED-5,200+-8B0000?style=for-the-badge&labelColor=000000)
![Effort](https://img.shields.io/badge/MANUAL_SCREENING-~40%25_LESS-E50914?style=for-the-badge&labelColor=000000)

![Python](https://img.shields.io/badge/Python-0A0A0A?style=for-the-badge&logo=python&logoColor=white)
![NLP](https://img.shields.io/badge/NLP-8B0000?style=for-the-badge)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-0A0A0A?style=for-the-badge&logo=scikitlearn&logoColor=white)
![TF-IDF](https://img.shields.io/badge/TF--IDF-8B0000?style=for-the-badge)
![Cosine Similarity](https://img.shields.io/badge/Cosine_Similarity-0A0A0A?style=for-the-badge)

</div>

```
╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║   ⚠  VIEWER DISCRETION ADVISED  ⚠                            ║
║                                                              ║
║   This project contains: endless resume piles, buzzword      ║
║   keyword-stuffing, and a machine that reads faster than     ║
║   any human ever could.                                      ║
║                                                              ║
║   Recruiters with a fear of 5,000 unread PDFs may find       ║
║   this deeply comforting.                                    ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝
```

---

## 🕯️ THE PLOT

> *Every opening gets hundreds of applications. Every recruiter has the same nightmare: the right candidate is somewhere in the pile, and nobody will ever find them.*

Recruitment teams spend countless hours **manually reviewing large volumes of resumes**. This project builds an **intelligent system that automates resume screening** with Natural Language Processing and Machine Learning.

It reads each resume, **classifies it into a job category**, and scores candidates on **experience and skills match**, so recruiters see the strongest candidates first.

---

## 🔪 THE BODY COUNT *(What Got Eliminated)*

| 💀 Victim | ⚰️ Cause of death | 🩸 Result |
|:--|:--|:--|
| **Manual resume screening** | TF-IDF + cosine similarity ranking | **~40%** less effort (~150 hrs over 6 months) |
| **Slow data prep** | Automated Python ETL pipeline | **4 hrs → 45 min** per batch |
| **Irrelevant matches** | Skill-cluster analysis informing JD rewrites | **+22%** match-score relevance |
| **Slow HR reporting** | Power BI and Excel funnel reports | **-25%** turnaround |

<div align="center">

```
 5,200+ resumes interrogated   ·   Top 10 skill clusters exposed   ·   0 resumes left unread
```

</div>

---

## 🔍 THE INTERROGATION: *PIPELINE*

```
   📄 RAW RESUMES (PDF)
        │
        ▼
   🧲 TEXT EXTRACTION       pull the text out of every PDF
        │
        ▼
   🧹 CLEANING              strip noise, normalise, tokenise
        │
        ▼
   🧬 TF-IDF VECTORS        turn language into numbers
        │
        ▼
   🗂️ CLASSIFICATION        assign each resume a job category
        │
        ▼
   🎯 COSINE SIMILARITY     score every candidate against the job description
        │
        ▼
   🏆 RANKED SHORTLIST      the best candidates rise to the top
```

---

## 🩸 WHAT THE MACHINE LOOKS FOR

```
 🔴  SKILLS MATCH SCORE    →  how closely a resume matches the job description
 🔴  EXPERIENCE            →  years and relevance of past roles
 🔴  KEYWORDS & CONTEXT    →  language patterns extracted with NLP
 🔴  JOB CATEGORY          →  the field the resume belongs to
```

---

## 🖥️ SYSTEM LOG

```
$ ./screen --resumes=5200 --job="Data Analyst"
[ OK ]  Extracting text from PDFs...
[ OK ]  Cleaning and tokenising...
[ OK ]  Building TF-IDF vectors...
[WARN]  Keyword-stuffed resume detected.
[ OK ]  Computing cosine similarity...
[DONE]  Candidates ranked.
[DONE]  Recruiter workload reduced by ~40%.

$ status
> The pile has been defeated.
```

---

## 🛠️ THE ARSENAL

| 🧰 Category | ⚔️ Tools |
|:--|:--|
| Language | Python |
| Data handling | Pandas, NumPy |
| NLP | Text cleaning, TF-IDF vectorization |
| Machine learning | Scikit-learn, cosine similarity |
| Reporting | Power BI, Excel |

---

## 🚪 ENTER IF YOU DARE: *RUN IT LOCALLY*

```bash
# 1. Clone the repository
git clone https://github.com/nehareddy-web/AI-resume-screening.git
cd AI-resume-screening

# 2. Install the dependencies
pip install -r requirements.txt

# 3. Unleash the screener
python main.py
```

---

## 🔮 THE SEQUEL

- 🔴 Add a web interface where recruiters can upload resumes and a job description
- 🔴 Try transformer-based embeddings for deeper semantic matching
- 🔴 Add explanations showing why each candidate was ranked where they were

---

<div align="center">

### 🩸 THE STORY ISN'T OVER.

*The pile will keep growing. Now there's something that can read it.*

[![▶ MORE CASE FILES](https://img.shields.io/badge/▶_MORE_CASE_FILES-GitHub_Profile-E50914?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nehareddy-web)
[![CONNECT](https://img.shields.io/badge/💀_CONNECT-LinkedIn-8B0000?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/nehareddy11)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:8B0000,50:3B0000,100:000000&height=120&section=footer&text=Don't%20look%20behind%20you...&fontSize=20&fontColor=ffffff&fontAlignY=68&animation=blinking" width="100%" alt="footer"/>

</div>
