# maths-sheets

Add .qmd files in /worksheets and they will appear on [this website](https://matthewhillary.github.io/maths-sheets/worksheets/) after the push the changes in github.

## Worksheet authoring guide for the agent

When adding new worksheets, follow these rules:

1. Put `date` in the frontmatter first.
2. Keep the sheet intended for printing: do not include answers in the main exercise section.
3. Use plain exercise statements; optionally add an answer key in a separate sheet or bonus section clearly marked 'Answer Key'.
4. Keep format consistent with existing files in `worksheets/`.
5. Generally there should be quite a few examples of a similar type for the student to work through rather than a smorgasboard of many different question types.

### Example QMD structure

```yaml
---
title: Algebra I - [topic]
date: 2026-03-27
categories: [algebra]
---

# Algebra I: [topic]

---

### Part A: Simplifying Expressions
1.  Simplify: $3(x + 5) - 2(2x - 1)$
2.  Simplify: $\frac{12a^{2}b}{4ab}$

---

### Part B: ...
4. ...

---

### (Optional) Answer Key
- 1. ...
- 2. ...
```

### Printing / agent style notes

- Design the worksheet so it prints cleanly on one or two pages.
- No immediate answers inside the exercise numbered list (answers can be in a separate answer key page).
- Keep layout simple: headings, numbered questions, minimal text formatting.
