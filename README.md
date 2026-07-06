# Design by Contract — Presentation

A scrollable, frame-by-frame HTML presentation on **Design by Contract (DBC)**. Content is based on *The Pragmatic Programmer* (Topic 23), written in plain language for managers, team leads, and developers. **PHP** is used for code examples only; the concepts apply to any language.

## Preview

**[Open presentation in browser](https://htmlpreview.github.io/?https://github.com/Goals-2026-01-06/design-by-contract/blob/main/design-by-contract.html)**

Uses [GitHub HTML Preview](https://htmlpreview.github.io/) — scroll down to move through all slides.

## How to view

Open the presentation HTML file in any modern browser (Chrome, Edge, Firefox). Scroll down to move through slides. No build step or install required.

**Print to PDF** — use the browser print dialog (Ctrl+P). Each slide is styled to print on its own page.

## Slide overview

1. Title — Design by Contract  
2. Why Contracts?  
3. Why It Matters  
4. What Is Design by Contract?  
5. Three Parts of Every Contract (precondition, postcondition, invariant)  
6. The Deal (formal agreement, violations are bugs)  
7. Caller vs Function Responsibility  
8. Design with Contracts  
9. How to Implement DBC  
10. Invariants vs Assertions (PHP examples)  
11. Example: PHP Deposit (`acceptDeposit`)  
12. Example: PHP Withdraw (`withdraw`)  
13. What This Example Shows  
14. Who Checks Preconditions?  
15. Semantic Invariants  
16. Best Practices  
17. Key Takeaways  

## What you will learn

- **Preconditions** — what must be true before a function runs (caller's responsibility)  
- **Postconditions** — what the function guarantees when it finishes  
- **Invariants** — rules that must hold true from the caller's perspective  
- How DBC differs from user-input validation, unit tests, and defensive checks everywhere  
- Practical patterns: exceptions, `assert()`, typed parameters, and PHPDoc  

## Technical notes

- **Format:** Single self-contained HTML file (17 slides, ~1280×720 each).  
- **Styling:** Cream slides, navy/teal accents; fonts and icons load from Google Fonts and Font Awesome CDN (internet required for first load).  
- **Dependencies:** No Node, npm, or build tools.  

## Source

Concepts and structure follow **Topic 23: Design by Contract** in *The Pragmatic Programmer: Your Journey to Mastery*, 20th Anniversary Edition, by Andrew Hunt and David Thomas.

**Book (PDF):** [The Pragmatic Programmer — 20th Anniversary Edition](https://github.com/XuJia0210/cs_book/blob/main/The%20Pragmatic%20Programmer%20Your%20Journey%20to%20Mastery%2C%2020th%20Anniversary%20Edition%20by%20Andrew%20Hunt%20David%20Hurst%20Thomas.pdf)

PHP examples illustrate the book's ideas for teams that work in PHP day to day.

## License / use

Presentation material for internal review, training, and team discussions. Adapt freely for your organization.
