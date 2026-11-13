# Sourcing Agent

A simple tool that helps recruiters **find engineers on GitHub** by skill and location, and quickly see what each person actually works with.

> **💬 Chat version available:** Just type what you need in plain English, like *"Find React engineers in Delhi and Kolkata, run deep search"*, and get your candidate list right in the chat. No setup, no forms.

---

## The problem

Finding good engineers usually means opening dozens of GitHub profiles one by one, checking their location, scanning their projects, and guessing their skills. It's slow, and easy to miss good people.

## Who it's for

Recruiters and sourcers hiring software engineers who want a faster first pass before manual review.

## What this tool does

You give it two things:

1. **Location(s)**: up to 3 (e.g. New York, Kolkata, Texas)
2. **Skill(s)**: up to 5 (e.g. Python, TypeScript, Go)

It returns a clean list of up to 30 engineers with:

| Name | Location | Tech Stack | GitHub / Portfolio Link |
|------|----------|------------|-------------------------|

Portfolio sites (personal websites, `github.io` pages) are included when the engineer has listed one.

---

## Key features

**Multi-location, multi-skill search**
Search several cities and several skills in one go.

**Fair results across locations**
Results are split evenly, so one big city never crowds out the others.

**Fresh candidates every run**
Run the same search again and you get different people, not the same top names.

**No duplicates**
Each engineer appears once, even if they match several skills.

**Accurate location matching**
Searching "San Francisco" returns people actually in San Francisco, not people who just have "Francisco" in their name.

**Real tech stack, not just what you searched**
The list shows the languages each person actually uses across their recent projects, so you see the fuller picture.

**Deep Search (optional)**
Goes beyond programming languages. Checks each candidate's code for things like React, Node.js, MongoDB, MySQL or Django, and shows which ones were actually found. Slower, but much more useful for framework-based roles.

**Plain error messages**
If something needs attention (like an expired access key), it tells you clearly instead of crashing.

---

## How effective is it?

From real test runs:

- Returned a full list of **30 unique candidates per search**, with no duplicates
- Covered **all requested locations evenly** (e.g. 10 each for 3 locations)
- Location matching was accurate after the exact-phrase fix
- Deep Search surfaced useful extra skills per candidate (e.g. Django, React, MySQL) and clearly marked people with no match
- A full search takes seconds; Deep Search takes a few minutes for 30 candidates

**Honest limits**

- It finds candidates by *public GitHub activity*. Strong engineers with little public code won't show up.
- Deep Search shows a skill *appears in their code*, not how strong they are at it. Think of it as a first filter, then review profiles yourself.
- Only publicly available information is used.

> *Add your own numbers here once you have them: time saved per search, candidates shortlisted, replies received.*

---

## What's next

- More features
- Improve effectiveness

---

## Want to know how it works?

Happy to walk you through how it was built. Reach out: **mailtobobin.work@gmail.com**

---

*Built by Argha. Uses only publicly available GitHub information.*
