<div align="center">
 
# 📘 SQL Handbook for Data Analytics

### *From `SELECT *` to Salary Interviews — One Notebook at a Time*

A complete, interview-ready, chapter-wise SQL learning system built as Jupyter Notebooks for aspiring **Data Analysts**.

👩‍💻 **Author:** Supriya Dixit &nbsp;|&nbsp; 📅 **Version:** 1.0 &nbsp;|&nbsp; 📗 **23 Chapters** &nbsp;|&nbsp; 🎯 **Beginner → Interview-Ready**

</div>

---

## 🧠 About This Handbook

Most SQL tutorials teach syntax. This handbook teaches you to **think like a Data Analyst**.

Every chapter is built around a simple idea: SQL isn't just about writing correct queries — it's about answering real business questions (*"Which customers are we losing?", "What's our top-selling product this quarter?"*) and being able to explain your logic clearly in an interview.

That's why every single chapter — from `SELECT` to `Window Functions` — follows the same rigorous structure, so you always know exactly what to expect and where to revise from.

---

## 🧭 The Learning Framework

Every chapter is built on 8 consistent pillars:

| Pillar | What It Gives You |
|---|---|
| 🎯 **Learning Objectives** | A clear checklist of what you'll be able to do by the end |
| 📖 **Interview-Ready Definitions** | Crisp, quotable definitions — exactly how to phrase it out loud |
| 💼 **Business Insight** | Real-world context: Amazon, Swiggy, Banks, Hospitals, HR, E-commerce |
| 🧪 **Worked Examples** | Sample tables → query → output → line-by-line explanation |
| ⚙️ **SQL Logical Execution Order** | How SQL *actually* processes your query under the hood |
| ✅❌ **Best Practices & Common Mistakes** | What top analysts do — and what trips up beginners |
| 🎤 **Interview Q&A** | Real questions with full written answers, not just prompts |
| 📚 **Quick Revision** | A 30-second cheat sheet before you close the notebook |

---

## 📂 The Complete Curriculum — 23 Chapters

### 🟢 Part 1 — SQL Foundations
> *Master the query anatomy every analyst uses daily*

| # | Chapter | You'll Learn |
|---|---|---|
| 01 | [Introduction to SQL](./01_INTRODUCTION_TO_SQL.ipynb) | SQL vs MySQL, DBMS/RDBMS, SQL categories |
| 02 | [SELECT Statements](./02_SELECT_STATEMENTS.ipynb) | Retrieving data, aliases, DISTINCT |
| 03 | [WHERE Clause](./03_WHERE_CLAUSE.ipynb) | Filtering rows with comparison & logical operators |
| 04 | [ORDER BY Clause](./04_ORDER_BY_CLAUSE.ipynb) | Sorting, ASC/DESC, multi-column sorts |
| 05 | [Aggregate Functions](./05_AGGREGATE_FUNCTIONS.ipynb) | COUNT, SUM, AVG, MIN, MAX |

### 🟡 Part 2 — Grouping, Joining & Logic
> *Where most SQL interviews are actually won or lost*

| # | Chapter | You'll Learn |
|---|---|---|
| 06 | [GROUP BY Clause](./06_GROUP_BY_CLAUSE.ipynb) | Summarizing data by category |
| 07 | [HAVING Clause](./07_HAVING_Clause.ipynb) | Filtering groups, WHERE vs HAVING |
| 08 | [SQL JOINS](./08_SQL_JOINS.ipynb) ⭐ | Keys, INNER/LEFT/RIGHT/multi-table joins |
| 09 | [CASE Statements](./09_CASE_STATEMENTS.ipynb) | Conditional logic & categorization |
| 10 | [String Functions](./10_STRING_FUNCTIONS.ipynb) | Cleaning & formatting text data |
| 11 | [Date Functions](./11_DATE_FUNCTIONS.ipynb) | Date arithmetic, extraction, formatting |
| 12 | [NULL Functions](./12_NULL_FUNCTIONS.ipynb) | ISNULL, COALESCE, handling missing data |

### 🔴 Part 3 — Advanced Analytical SQL
> *The concepts that separate an analyst from a beginner*

| # | Chapter | You'll Learn |
|---|---|---|
| 13 | [Subqueries](./13_SUBQUERIES.ipynb) | Nested queries, correlated subqueries |
| 14 | [CTEs](./14_COMMON_TABLE_EXPRESSIONS_CTE.ipynb) | Readable, reusable query blocks |
| 15 | [Window Functions](./15_WINDOW_FUNCTIONS.ipynb) ⭐ | RANK, ROW_NUMBER, LAG/LEAD, running totals |
| 16 | [SET Operators](./16_SET_OPERATORS.ipynb) | UNION, UNION ALL, INTERSECT, EXCEPT |
| 17 | [Views](./17_VIEWS.ipynb) | Virtual tables, updatable views |

### 🟣 Part 4 — Database Design & Data Management
> *How real production databases are built and maintained*

| # | Chapter | You'll Learn |
|---|---|---|
| 18 | [Temporary Tables](./18_TEMP_TABLES.ipynb) | Local/global temp tables, table variables |
| 19 | [Constraints](./19_CONSTRAINTS.ipynb) | PRIMARY/FOREIGN KEY, UNIQUE, CHECK |
| 20 | [DML](./20_DML.ipynb) | INSERT, UPDATE, DELETE, Transactions |
| 21 | [DDL](./21_DDL.ipynb) | CREATE, ALTER, DROP, TRUNCATE |

### 🏆 Part 5 — Real-World Application & Interview Mastery
> *Turning knowledge into a job offer*

| # | Chapter | You'll Learn |
|---|---|---|
| 22 | [Business Case Studies](./22_BUSINESS_CASES.ipynb) | End-to-end SQL problem solving with insights |
| 23 | [Interview Preparation Handbook](./23_INTERVIEW_QUESTIONS.ipynb) 🎤 | Full interview roadmap + question bank across all rounds |

---

## 🗺️ Suggested Learning Path

```
Foundations (1-5)  →  Grouping & Joins (6-12)  →  Advanced SQL (13-17)
        →  Database Design (18-21)  →  Case Studies & Interviews (22-23)
```

New to SQL? Start at Chapter 1 and go in order.
Prepping for interviews this week? Jump straight to **Chapter 23**, then revisit weak topics using the tables above.

---

## 🚀 Getting Started

```bash
git clone https://github.com/<your-username>/SQL-Handbook-For-Data-Analytics.git
cd SQL-Handbook-For-Data-Analytics
```

Open any chapter in **Jupyter Notebook**, **JupyterLab**, or **VS Code** — or simply click a chapter link above to read it directly on GitHub.

---

## 🛠️ SQL Dialect Notes

Examples are written to work across **MySQL**, **PostgreSQL**, and **SQL Server**, with call-outs wherever syntax diverges — e.g. `LEN()` (SQL Server) vs `LENGTH()` (MySQL/PostgreSQL), or `#TempTable` vs `CREATE TEMPORARY TABLE`.

---

## ❓ FAQ

**Do I need to install a database to use this?**
No — every chapter is self-contained with sample tables and expected outputs, so you can learn the logic without setting up a database. (Optional: connect the notebooks to MySQL/PostgreSQL if you want to run queries live.)

**Is this enough to crack a Data Analyst interview?**
This handbook covers the full syllabus most SQL interviews draw from — fundamentals through window functions, database design, and a dedicated interview-prep chapter. Pair it with mock interviews and timed practice for best results.

**Can I contribute or suggest a chapter?**
Yes! Open an issue or PR — chapters like Index Optimization, Stored Procedures, or `PIVOT`/`ROLLUP` are great candidates for a v2.

---

## ⭐ Show Some Love

If this handbook helped your data analytics prep, please **star ⭐ the repo** — it helps other learners find it too.

---

<div align="center">

**📌 Status: All 23 chapters complete ✅**
*Consistent formatting · Verified chapter sequence · Full interview Q&A across every chapter*

</div>
