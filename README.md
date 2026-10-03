# Air University Lab Report Skill

A skill for Claude that turns your raw lab work into a finished lab report in the standard Air University format: cover block, assessment tables, Introduction, Theory, tasks with figures, Results and Discussion, and Conclusion.

You bring the work (queries or code, screenshots, and the objective from your lab manual). Claude handles structure, wording and formatting, and gives you a Word (.docx) file.

> Built from a real Air University lab report (Department of Computer and Software Engineering, DBMS). Always check the result against your instructor's template. If your instructor's template differs, theirs wins.

## What it does

- Builds the cover block, both assessment tables and the title page
- Writes the Introduction, Theory, Results and Discussion, and Conclusion from your actual work
- Lays out each task with the query or code in a table and numbered figure captions
- Handles course variations: SQL (DBMS), C++ (DSA), and circuit diagrams and truth tables (DLD). See [examples/course-variations.md](examples/course-variations.md)

## What it does not do

- It does not run your code or produce output for you. If you do not send a result, it asks for it instead of inventing one.
- It does not replace doing the lab. Submit only work you actually did and understand, and follow your course's rules on AI assistance.

## Install

### Option A: as a Claude skill

1. Download this repo (Code > Download ZIP) and unzip it.
2. Zip the folder `air-university-lab-report` (the folder itself, with `SKILL.md` inside).
3. In Claude, open the Skills settings and upload that zip. Menu names change over time, so look for "Skills" under settings or capabilities. Skills may depend on your plan.
4. Turn the skill on.

### Option B: no install, works anywhere

Open `air-university-lab-report/SKILL.md`, copy everything, and paste it at the start of a new chat (or into a Project's instructions). Then send your lab work.

## How to use

1. Start a new chat and say: "Make my lab report using the Air University lab report skill."
2. Send:
   - Course, lab number and lab title
   - The objective line from the lab manual
   - Your name, reg. no., class, department, instructor and submission date
   - For each task: the query or code you ran, and the screenshots in order
   - Notes on anything that went wrong or surprised you
3. Review the draft. Check every figure and result against your screenshots.
4. Fix anything that is wrong, then submit.

### Example prompt

```text
Use the Air University lab report skill.
Course: DBMS, Lab 03, "SQL DML Commands"
Objective: <paste from the lab manual>
Name / Reg. no. / Class: <yours>
Instructor: <name>    Date: <date>
Task 1: <your query> + screenshots
Task 2: <your query> + screenshots
Note: one UPDATE changed no rows because that record did not exist.
```

## Repo layout

```text
air-university-lab-report/
  SKILL.md                  the skill itself
examples/
  course-variations.md      how DBMS, DSA and DLD reports differ
LICENSE
README.md
```

## Customising

Edit `SKILL.md` to match your department's or instructor's template, for example a different cover page. If your change would help other students, open a pull request.

## Contributing

Issues and pull requests are welcome, especially for new course formats (OS, networks, electronics) and corrections where the format does not match what instructors expect.

## License

MIT. See [LICENSE](LICENSE).
