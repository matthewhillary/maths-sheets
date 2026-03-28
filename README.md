# maths-sheets

Add .qmd files in /worksheets and they will appear on [this website](https://matthewhillary.github.io/maths-sheets/worksheets/) after you push the changes to GitHub.

To update I'd recommend opening the repo in a code space (see the green code button if you are in the repo) and then asking the chat for the type of maths worksheet you want. After it's updated you can commit and sync the change and in a couple of minutes it should appear at the website. 

## Worksheet authoring guide for the agent

When adding new worksheets, follow these rules:

1. Put `date` in the frontmatter first.
1. This is a quarto project which uses mathjax so keep the equations in the format required for this.
1. Keep the sheet intended for printing.
1. Do not include answers in the main exercise section. Include an answer key discretely in a separate sheet if you think the question requires it (ie, if the tutor might need it)
1. Keep format consistent with existing files in `worksheets/`.
1. Generally there should be quite a few examples of a similar type for the student to work through rather than a smorgasboard of many different question types.
1. Leave space for the student to do their working if you think the question requires it.

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

1.  Simplify: $\frac{12a^{2}b}{4ab}$

---

### Part B: ...

1. ...

---

### (Optional) Answer Key

- 1. ...

- 1. ...

```

### Printing / agent style notes

- Design the worksheet so it prints cleanly on one or two pages.
- No immediate answers inside the exercise numbered list.
- Keep layout simple: headings, numbered questions, minimal text formatting.
