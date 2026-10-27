---
layout: essay
type: essay
title: "Why Is ESLint Yelling at Me?"
date: 2026-09-24
published: true
labels:
  - Software Engineering
  - Coding Standards
  - ESLint
---

## Why Is ESLint Yelling at Me?

Before ICS 314, I thought coding standards were mostly about keeping code organized and making it look nice. I never really thought they could help me become a better programmer. After using ESLint with TypeScript, I can see that coding standards are useful for more than just formatting. They help make code more consistent, readable, and easier to maintain, especially when working on larger projects.

## Getting Used to ESLint

My first experience with ESLint has been both helpful and a little annoying. Sometimes I think my code is finished, but ESLint still finds something that needs to be fixed. Since TypeScript is new to me, these errors have helped me notice mistakes and learn how the language is supposed to be written. I am more familiar with Python, so adjusting to TypeScript's syntax and coding conventions has taken some practice.

One example was when I worked on the Island Cities assignment. ESLint identified many formatting issues in my code, including using double quotes instead of single quotes and missing a trailing comma. Initially, I was frustrated because my program could still work even with these formatting differences. However, I realized that coding standards aren't always about whether a program runs correctly. They are also about making sure the code follows a consistent structure.

For example, a simple piece of TypeScript code might look like this:

```typescript
const cities = [
  "Honolulu",
  "Hilo",
  "Kailua"
];
```

Depending on the ESLint configuration, the code might need to be changed to follow rules for single quotes and trailing commas:

```typescript
const cities = [
  'Honolulu',
  'Hilo',
  'Kailua',
];
```

Both versions accomplish the same thing, but the second follows the style rules used in our assignments. I also learned that ESLint has a `--fix` option that can automatically correct many formatting problems, which makes the process much more manageable.

## Why Coding Standards Matter

I also understand why coding standards are important when working with other people. Code should not only work; it should be easy for someone else to read and understand. If every programmer uses a different style, it becomes harder to review and modify code. Following the same standards makes everyone's code more consistent and easier to work with. This is especially important in software engineering, where multiple developers often contribute to the same project.

Another thing I learned is that ESLint and TypeScript help in different ways. TypeScript can identify problems with types, while ESLint checks whether code follows specific rules and conventions. Using both tools gives me more confidence in my work. Instead of assuming everything is correct because my program runs, I can use these tools to identify issues I might have overlooked.

## What I'll Do Differently

Moving forward, I want to make checking coding standards part of my regular programming process rather than something I only do when an assignment is finished. Running ESLint more frequently will help me catch small issues earlier instead of dealing with a long list of errors at the end. I also think that becoming more familiar with these standards will make writing clean code feel more natural over time.

Overall, I still don't love fixing every ESLint error, but I think it has helped me improve my coding habits. It makes me pay more attention to how I write code instead of only caring about whether it runs. I now understand that writing good software involves more than making a program functional. It also means writing code that other people can understand and maintain.

---

*AI Use Disclosure: I used ChatGPT to help organize my thoughts. I reviewed the content to make sure it reflects my own perspective.*
