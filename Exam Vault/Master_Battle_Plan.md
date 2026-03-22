# 🛡️ The Ranker's Endgame: 6-Subject Sprint

## 📅 MONDAY EXAMS (Target: Saturday Focus)
- [ ] **Math:** (Textbook Only) Solve 15 hardest chapter-end problems.
- [ ] **Citizenship:** (AI Bulk Factory) 60-question MC test from notes.
- [ ] **Afaan Oromoo:** (Manual) 1-page grammar & vocab cheat sheet.

## 📅 TUESDAY EXAMS (Target: Sunday Focus)
- [ ] **Physics:** (Textbook Only) Solve 15 hardest formula problems.
- [ ] **Economics:** (AI Bulk Factory) 60-question MC test from notes.
- [ ] **ICT:** (AI Bulk Factory) 60-question MC test from notes.

---
## ⚡ The Strategy Matrix
1. **Math & Physics = DO NOT USE AI.** AI hallucinates math. Use your physical textbook, solve problems on blank paper, grade yourself. 
2. **Citizen, Eco, ICT = BULK FACTORY.** Upload notes to AI, generate 60 questions, paste the code block into an Obsidian note, solve, and get graded.
3. **Afaan Oromoo = CHEAT SHEET.** Summarize rules manually.
```dataview
TABLE 
  last_reviewed AS "Last Reviewed", 
  interval AS "Interval", 
  (date(last_reviewed) + dur(interval + " days")) AS "Next Review"
FROM #review
WHERE (date(last_reviewed) + dur(interval + " days")) <= date(today)
SORT (date(last_reviewed) + dur(interval + " days")) ASC
```
0911637675

![[Pasted image 20260322085158.png]]