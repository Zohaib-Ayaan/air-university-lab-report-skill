---
name: air-university-lab-report
description: Turn raw lab work (queries, code, screenshots, notes) into a finished Air University lab report in the standard format used for DBMS, DSA, DLD and similar courses. Use when the student has a lab report to write or package.
---

# Air University Lab Report Formatter

Package the student's raw lab work into a report that follows the standard Air University format. The student supplies the work. You handle structure, wording and formatting.

## Ground rules
- Never invent results, outputs, screenshots or observations. If a task has no result, ask for it.
- Report only what the student's work actually shows. If something was unexpected (for example an UPDATE matched no rows), say so plainly.
- If the instructor's template differs from this format, follow the instructor's template.

## Inputs to collect first (ask only for what is missing)
- Student name, reg. no. / roll number, class
- Department (default: Computer and Software Engineering)
- Course, lab number and lab title
- Objective line from the lab manual
- Instructor name and submission date
- For each task: the queries or code used, the output, and the screenshots in order

## Report structure (in this order)
1. **Cover block:** "<COURSE> Lab <NN>", then "Air University, Islamabad". Header table with AIR UNIVERSITY / DEPARTMENT OF <DEPARTMENT> / LAB NO <NN>. Then Lab Title, Student Name, Reg. No, and Objective.
2. **Lab Assessment table:** rows are Ability to Conduct Experiment, Ability to assimilate the Results, Effective use of lab equipment and follows the lab safety rules. Columns are Excellent (5), Good (4), Average (3), Satisfactory (2), Unsatisfactory (1). Leave the cells empty and add "Total Marks / Obtained Marks" below.
3. **Lab Report Assessment table:** rows are Data presentation, Experimental results, Conclusion. Same columns and the same Total/Obtained Marks line.
4. **Title page block:** DEPARTMENT OF <DEPARTMENT>, then Lab Report number, Title, Name, Roll Number, Class, Submitted To, Date.
5. **Introduction:** one paragraph. Link to the previous lab, then state what this lab covers and which commands or concepts are used. Bold the key terms.
6. **Theory:** short labelled paragraphs, one per concept (bold lead-in label, then definition, syntax, operators or rules).
7. **Task sections:** one heading per task, "<Task name> (Task N)". Each has a short explanation, then the Query/Code in a single-cell bordered table, then figures with captions "Figure N: <description>" and one or two sentences on what the output shows. Figure numbers run continuously across the whole report.
8. **Results and Discussion:** two short paragraphs. First summarise what ran and what happened, including anything that did not change or failed and why. Second state what the lab showed and the practical lesson.
9. **Conclusion:** one short paragraph.
10. **Footer:** page numbers in the form "Page | N".

## Style rules
- Past tense, passive or "we" voice, plain academic wording.
- Bold command and keyword names in prose (**DELETE**, **WHERE**, etc.).
- Keep paragraphs short. No bullet lists inside the report body.

## Course variations
- **DBMS:** SQL queries go in the Query tables. Mention the database, schema and table names where relevant.
- **DSA:** code (C++) goes in code tables, with the output screenshot after each program.
- **DLD:** add the circuit diagram and truth tables as figures or tables inside the relevant task sections. Include the Boolean expression or logic used for each circuit.
- If a course needs a section not listed above, add it where it fits and keep the rest unchanged.

## Output
Produce a .docx. Before finishing, check that figure numbering is continuous, every figure has a caption, the Results section matches what the screenshots show, and the name, date and instructor fields are filled in.
