# Course variations

The core report structure stays the same across courses. These notes cover what changes.

## DBMS (SQL labs)
- The Query tables hold SQL statements, one block per task.
- Mention the database, schema and table names (for example `Database.dbo.Table`) when the lab uses them.
- Show a SELECT result after any INSERT, UPDATE or DELETE so the effect is visible.
- If a statement affects zero rows, say so in the Results section.

## DSA (C++ labs)
- Put the full program in a code table, then the output screenshot straight after it.
- Explain the logic in a few sentences (what the pointers, arrays or nodes do), not line by line.
- Note the compiler or IDE used (for example Dev C++).

## DLD (digital logic labs)
- Add the circuit diagram as a figure in the relevant task.
- Add truth tables as tables. Include the Boolean expression and any simplification steps.
- State the gates or ICs used and compare observed outputs with the expected truth table.

## Other courses
Start from the standard structure in `air-university-lab-report/SKILL.md` and add the sections your course needs. If you build a variation others could use, open a pull request.
