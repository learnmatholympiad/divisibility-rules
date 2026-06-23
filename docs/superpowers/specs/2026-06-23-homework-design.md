# Homework Feature Design
**Date:** 2026-06-23  
**Status:** Approved

## Overview
Add a Homework section to the existing lessons hub (`index.html`) and create two standalone homework pages — one per lesson posted so far.

## Hub Changes (`index.html`)
- New "Homework" section below the Topics grid, separated by a matching gold divider
- Same 4-column card grid as Topics
- Cards use cyan accent (`#38BDF8`) instead of gold to visually distinguish homework from lessons
- Initially two active cards: Percentages Homework → `homework-percentages.html`, Divisibility Rules Homework → `homework-divisibility.html`
- Future assignments added as new cards; unposted ones grayed out

## Homework Pages (shared design)
- Scrollable single-page layout (not a slide deck) — students work at their own pace
- Same Nunito + Fira Code font stack and warm cream background as lesson pages
- Back-link to hub at the top

## `homework-percentages.html`
- Three read-only problem cards (word problem style)
- Problems from `Percentages Homework.txt`:
  1. Number increased 20% then decreased 20% — is it the same?
  2. $100 toy discounted 20% twice — final price?
  3. Brain Teaser: 50% of a number = 25% of 80
- Each card has a small note: "✏️ Write your answer in your notebook."

## `homework-divisibility.html`
- **5 multiple choice questions** — student clicks an option, sees "✅ Correct!" or "❌ Incorrect, try again!" Keeps trying until right. No score shown.
- **3 short answer questions** (word problem style) — each card shows the problem and a note: "✏️ Write your answer in your notebook."

### MC Questions
1. Units digit rule for divisibility by 5
2. Is 48 divisible by 3? (with reasoning)
3. Which number is divisible by 6: 21, 33, 48, or 35?
4. Missing digit X in X649 to make it divisible by 3
5. Is 715 divisible by 11?

### Short Answer Questions
1. 85 apples, bags of 5 — can they all be packed perfectly?
2. 132 students, vans of 3 — can all students ride with no empty seats?
3. Farmer Brown's 9,762 eggs — can they be packed in dozens? (apply combined rules)
