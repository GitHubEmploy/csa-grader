# CSA Grader — Assignment Grading Tool

Lightweight HTML/JS grading tool built to streamline TA workflow for CSA (Computer Science A) assignments. Provides structured scoring rubrics with instant totals.

## Features

- **Rubric Scoring** — Pre-defined criteria with per-category point entry
- **Auto-Calculation** — Running total updates on every input change
- **Assignment Variants** — Separate pages for different homework assignments
- **Zero-Dependency** — Pure HTML + vanilla JavaScript, no build step

## Tech Stack

| Component | Technology |
|-----------|------------|
| Frontend | HTML5, CSS, vanilla JavaScript |
| Format | Static single-page app (no server required) |

## Project Structure

```
index.html          — Entry point (redirects to current homework)
summerhw2.html      — Homework 2 grading rubric
summerhw3.html      — Homework 3 grading rubric (video project)
```

## Usage

Open any `.html` file in a browser. Enter scores per rubric category; the total updates automatically.

```
Total: 24/35
```

## Notes

Quick TA utility — not a full LMS integration. Add new assignments by copying and adjusting the rubric HTML.
