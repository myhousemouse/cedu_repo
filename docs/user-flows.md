# User flows

Status: Target flow identified; current interface validation pending

## VOCA TEST — create a student vocabulary test

- Primary user: teacher
- Goal: create a usable student test from vocabulary in a CEDU book
- Evidence status: the goal is confirmed by the user; the detailed sequence
  below comes from historical first-party documentation and must be checked
  against the current interface.

### Main path

1. Enter VOCA TEST from CEDU Book and sign in if required.
2. Register or select a CEDU book.
3. Select the unit or word range.
4. Choose question types, item counts, and distribution.
5. Review the words and generated items.
6. Update or regenerate selected content when necessary.
7. Preview the student test and answer sheet.
8. Enter test metadata such as campus, class, teacher, and test name.
9. Save, download, or print the test.
10. Find the saved test later to reuse or adapt it.

### Alternate and failure paths to validate

- The required book is not in “my books.”
- Selected ranges and requested item counts conflict.
- A specific word or generated item is unsuitable.
- The teacher moves backward after editing later steps.
- The session ends before saving.
- Print preview differs from the final print or downloaded file.
- A prior test must be duplicated for another class or date.

### Completion state

The teacher has a saved, identifiable test whose student sheet, answer sheet,
content selection, item count, and print/download output have all been checked.

For each flow, capture:

1. User goal
2. Entry condition
3. Main path
4. Alternate and failure paths
5. Completion state
6. Related requirements

