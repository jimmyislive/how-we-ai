---
layout: page
title: About
---

# How We AI

A community‑driven collection of **real, practical ways people use AI in their daily work and life**.

Contributors share stories via **GitHub pull requests**, each as a simple Markdown file. The site is then published automatically.

---

## 1. What This Project Is (and Isn’t)

**This is:**

* Real‑world AI usage (work, learning, parenting, health, creativity, ops, leadership, etc.)
* First‑person or lightly anonymized
* Practical and honest (including failures)

**This is not:**

* Marketing copy
* Tool documentation
* Pure prompts without context
* Thought leadership essays with no concrete usage

---

## 2. Repository Structure

```text
how-we-ai/
├── README.md
├── CONTRIBUTING.md
├── use-cases/
│   ├── engineering/
│   ├── leadership/
│   ├── education/
│   │   └── how-we-ai.md
│   ├── health/
│   ├── creative/
│   └── personal/
└── site/
```

Each **use case = one Markdown file**.

---

## 3. Markdown File Format (Canonical Template)

Every submission should follow this structure.

````markdown
---
title: "Using AI to build out this site"
author: "Jimmy J."            # real name, first name, or pseudonym
github handle: "@jimmyislive"
role: "Engineer"   # optional but encouraged
company: "" # optional
industry: "Technology"
category: "education"       # must match a folder name
tools:
  - ChatGPT
frequency: "Weekly"
date: 2026-01-01
---

## The Problem

Describe the real problem you were trying to solve.
Be specific and grounded in reality.

> Example: I wanted to gather use cases for how people use AI in their daily lives and workflows.

---

## How I Used AI

Explain **exactly** how AI fit into your workflow.

- Where did AI enter the process?
- What inputs did you give it?
- What did you trust it with vs double‑check?

---

## Concrete Example

Include a real interaction, prompt, or flow.

```text
"Here are the steps I followed..."
````

Or describe a step‑by‑step loop.

---

## What Worked Well

* Speed improvements
* Quality gains
* Confidence
* Reduced cognitive load

---

## What Didn’t Work (or Felt Risky)

Honesty matters here.

* Wrong answers
* Overconfidence
* Hallucinations
* Security concerns

---

## Impact

Quantify if possible.

* Time saved
* Fewer errors
* Better decisions
* New capability unlocked

---

## Would I Recommend This?

Yes / No / With caveats — and why.

---

## Final Thoughts

Optional reflections, lessons learned, or advice to others.

````

---

## 4. Writing Guidelines

- **Length:** 400–1,200 words is ideal
- **Voice:** First‑person preferred
- **Tone:** Practical, reflective, non‑salesy
- **Anonymity:** Allowed (just say so)
- **Sensitive data:** Never include secrets, PII, or proprietary code

---

## 5. Contribution Flow (Step‑by‑Step)

1. **Fork the repo**
2. Create a new file:
   ```bash
   use-cases/<category>/<your-slug>.md
````

3. Copy the template above
4. Fill it out honestly
5. Commit and open a **Pull Request**
6. Maintainer reviews for clarity & fit (not content policing)
7. More details available in CONTRIBUTING.md

---

## 6. Review Criteria (Lightweight)

PRs are accepted if they are:

* Real and specific
* Clearly written
* Non‑promotional
* Useful to someone else

We do **not** judge:

* Seniority
* Tools used
* Writing polish

---

## 7. Full Example

You can see a complete example at use-cases/education/how-we-ai.md

## 8. Philosophy

> This project is about **how people actually use AI**, not how vendors say they should.

Messy. Human. Imperfect. Useful.

Yes, there is a lot of hype around AI. The challenge with AI today is not weather it is useful or not, but "how" it is providing value. Everyone keeps talking about how its going to change the world without getting into specifics. A lot seems like fluff. The more use cases we can identify and learn from, the better chances of AI being a net positive, for everyone. 
