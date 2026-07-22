# Rice Course Planner

A single-file, offline degree & schedule planner for Rice University.
Open `index.html` in any browser — no install, no server. Your data is
saved automatically in that browser (and can be exported/imported as JSON).

## What it does

- **Plan** — lay out courses across semesters (Fall/Spring, multiple years),
  with per-term credit totals and automatic overload / underload flags.
- **Week** — see any term as a weekly calendar grid, with automatic
  **time-conflict detection** and a **"days free for work"** summary for
  planning internship/office time.
- **Requirements** — auto-computed progress toward the 120-credit total,
  a **D1 / D2 / D3 division tracker**, and editable custom requirement
  groups (e.g. "Major core — 30 credits", "2 courses in STAT").
- **Catalog** — paste course blocks copied straight from
  courses.rice.edu; CRN, title, meeting times, days, and credits are
  parsed automatically. Tag each course D1/D2/D3.
- **Data** — enter your profile, paste your transcript (so completed
  courses count toward requirements), and export/import a backup file.

## Paste format (from courses.rice.edu)

```
CRN: 15079
Course: BUSI 215 001
Part of Term: Full Term
Title: LEADING ACROSS SOCIAL DIVIDES
Instructor(s): Jun, Sora
Meeting: 4:00PM - 5:15PM MW
Credits: 3
```

Paste as many of these blocks as you like at once into the Catalog tab.
