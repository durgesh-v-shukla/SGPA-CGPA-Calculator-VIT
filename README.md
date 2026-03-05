# 📊 SGPA & CGPA Calculator

A clean, fully responsive web calculator for students to compute their **SGPA** (Semester Grade Point Average) and **CGPA** (Cumulative Grade Point Average) based on the official university grading system.

---

## 🎓 About

Built for **Computer Science Engineering — Semester 4** students.  
Pre-loaded with all 10 subjects, credit values, and the correct grading table.

---

## ✨ Features

- ✅ Pre-loaded Sem 4 subjects with exact credit values (21 total credits)
- ✅ Official grading system with marks range (A+ = 91–100 = 10 pts, etc.)
- ✅ Live SGPA calculation with formula display
- ✅ Progress bar showing SGPA out of 10
- ✅ Performance label (Outstanding / Excellent / Good...)
- ✅ CGPA calculator — add/remove semesters freely
- ✅ Sem 4 highlighted as current — type expected SGPA to simulate CGPA
- ✅ Fully responsive — works on mobile, tablet, and desktop
- ✅ Mobile view uses card layout instead of table for easy reading
- ✅ No frameworks, no dependencies — pure HTML, CSS, JS

---

## 📐 Grading System

| Grade | Marks Range | Grade Points |
|-------|-------------|--------------|
| A+    | 91 – 100    | 10           |
| A     | 81 – 90     | 9            |
| B+    | 71 – 80     | 8            |
| B     | 61 – 70     | 7            |
| C+    | 51 – 60     | 6            |
| C     | 46 – 50     | 5            |
| D     | 40 – 45     | 4            |
| F     | 00 – 39     | 0            |

---

## 🧮 How SGPA is Calculated
```
SGPA = Σ (Credit × Grade Points) / Total Credits

Example:
Subject has 3 credits, grade A+ (10 pts)
→ 3 × 10 = 30 earned points

All 10 subjects calculated similarly
→ Total earned points ÷ 21 = SGPA
```

## 📊 How CGPA is Calculated
```
CGPA = Sum of all Semester SGPAs / Number of Semesters

Example (4 semesters):
Sem1: 8.5 + Sem2: 9.0 + Sem3: 8.8 + Sem4: 9.2
→ (8.5 + 9.0 + 8.8 + 9.2) / 4 = 8.875
```

---

## 📚 Subjects — Semester 4

| # | Code    | Subject                          | Credits |
|---|---------|----------------------------------|---------|
| 1 | CS2308  | Data Structures-II               | 3       |
| 2 | CS2309  | Theory of Computation            | 2       |
| 3 | CS2310  | Operating System                 | 3       |
| 4 | CS2311  | Software Engineering             | 3       |
| 5 | CS2312  | System & Application Development | 1       |
| 6 | MM0703  | Internet of Things               | 3       |
| 7 | HS2003  | From Campus to Corporate - 2     | 2       |
| 8 | HS2004  | Reasoning & Aptitude Dev. - 4    | 1       |
| 9 | CS2313  | Design Thinking - 2              | 1       |
|10 | CS2314  | Engg. Design & Innovation - 2    | 2       |
|   |         | **Total**                        | **21**  |

---

## 🚀 How to Use

1. Open `index.html` in any browser — or visit the live site
2. **SGPA:** Select a grade for each subject from the dropdown
3. SGPA is calculated instantly with the full formula shown
4. **CGPA:** Enter your past semester SGPAs in the fields
5. Type your expected Sem 4 SGPA to simulate your final CGPA
6. Use **+ Add Semester** or **− Remove Last** to adjust semester count

---

## 🌐 Live Demo

👉 [View Live Site](https://yourusername.github.io/your-repo-name)

---

## 🛠️ Tech Stack

- HTML5
- CSS3 (Flexbox, CSS Grid, Media Queries)
- Vanilla JavaScript (no libraries)
- Google Fonts — Inter

---

## 📁 File Structure
```
📦 repository
 ┗ 📄 index.html       ← entire app in one file
 ┗ 📄 README.md        ← this file
```

---

## 📄 License

This project is open source and free to use.

---

> Made with ❤️ for CSE students
