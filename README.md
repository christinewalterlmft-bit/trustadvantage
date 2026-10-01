[README.md](https://github.com/user-attachments/files/32909656/README.md)

<p align="center">
  <img src="assets/cover-front.png" alt="The Trust Advantage, front cover" width="300">
</p>

<h1 align="center">The Trust Advantage</h1>

<p align="center">
  <strong>The 8-Week Playbook to Master Communication and Build Unshakeable Trust at Work</strong><br>
  Corporate Edition · Christine Walter, LMFT, PCC
</p>

<p align="center">
  <a href="dist/The_Trust_Advantage_Corporate_Edition.pdf"><strong>Download the PDF</strong></a>
</p>

---

## About the Book

Trust is the invisible operating system of every organization. When it is high, people raise problems early, disagree in the meeting instead of the hallway, and give one another the benefit of the doubt. When it is low, everything slows down.

*The Trust Advantage* turns research on psychological safety, listening, feedback, influence, and trust repair into an eight-week training program. It is built for practice, not inspiration: one skill per week, seven daily drills per skill, and a clear standard for mastery. It works for individuals, and it works faster when a whole team goes through it together.

## What's Inside

**Part One · Foundations**

| Chapter | Focus |
|---|---|
| Introduction: Why Trust Is the Advantage | The business case for trust at work |
| How to Use This Playbook | How the program works, plus the eight weeks at a glance |
| Your Two-Minute Trust Baseline | A self-assessment to retake after Week 8 |
| The Science in Five Minutes | The four research findings behind every skill |
| The Trust Equation | The operating model for all eight weeks |

**Part Two · The Eight Weeks**

| Week | Skill | You will learn to |
|:---:|---|---|
| 1 | Warmth First: Win the First Four Seconds | Lead with good intent before credentials |
| 2 | Listen So They Feel Heard | Ask questions that deepen understanding |
| 3 | Make It Safe to Speak | Make honesty, and bad news, feel safe |
| 4 | Turn Toward the Small Moments | Respond to small bids for connection |
| 5 | Say the Hard Thing Kindly | Give feedback that is clear and caring |
| 6 | Presence: The Body Speaks First | Align your posture, face, and voice with your intent |
| 7 | Influence Without Manipulation | Persuade in ways that serve both sides |
| 8 | Repair, Rebuild, Repeat | Apologize well and rebuild trust over time |

**Part Three · The Toolkit**

| Resource | Use |
|---|---|
| The 12 Trust Habits | A one-page cheat sheet to print and pin up |
| Your 8-Week Mastery Tracker | A worksheet for logging progress and wins |
| Running It With Your Team | A 30-minute weekly huddle format for group rollout |
| References and Further Reading | Full APA citations with DOIs |

## How Each Week Works

Every week follows the same structure, so readers always know where they are:

| Section | Purpose |
|---|---|
| The One Thing to Remember | The single idea to carry all week |
| The Big Idea & Why It Works | The concept and the research behind it |
| The Skills | Specific, observable behaviors to use immediately |
| Your 7-Day Practice | One drill per day, in real conversations |
| Mastery Check & Common Traps | The standard to meet and the mistakes to avoid |
| Team Conversation | Two questions for discussing the skill with colleagues |

<p align="center">
  <img src="assets/sample-week.png" alt="Sample page: Week 1 practice drills, mastery check, and team conversation" width="300">
</p>

## Research Foundation

The core findings are drawn from peer-reviewed research and foundational scholarship, including work on warmth and competence judgments, psychological safety (Edmondson; Google's Project Aristotle), speaker–listener neural coupling, active-constructive responding, the structure of effective apologies, and competence- versus integrity-based trust repair. Practical techniques that come from coaching practice rather than controlled studies, such as the SBI feedback model and box breathing, are identified as such in the text.

Every in-text citation in the PDF links to its entry in the References section, and every reference includes a DOI or stable URL where one exists.

## Building From Source

The PDF is generated from HTML and CSS using [WeasyPrint](https://weasyprint.org/). The output is a 6 × 9 in print-ready file with running heads, a linked table of contents, and PDF bookmarks.

**Requirements:** Python 3.10 or later, and Node.js (used only to download the fonts).

```bash
# 1. Install dependencies
pip install -r requirements.txt
npm install

# 2. Prepare fonts, generate cover art, and build the PDF
python3 setup_fonts.py
python3 art.py
python3 build.py
```

The finished book is written to `dist/The_Trust_Advantage_Corporate_Edition.pdf`.

To edit the book, change the manuscript text in `build.py` (each week is defined as a structured block) or the design in `book.css`, then rerun `python3 build.py`.

## Repository Structure

```
trust-advantage/
├── build.py          # Manuscript content, references, and PDF build
├── book.css          # Typography, page layout, and design system
├── art.py            # Generates the cover and divider artwork (SVG)
├── setup_fonts.py    # Converts the open-license fonts for the build
├── requirements.txt  # Python dependencies
├── package.json      # Font packages (Fontsource)
├── assets/           # Images used in this README
└── dist/             # The finished PDF
```

## Printing Notes

The PDF is set at a standard 6 × 9 in trade trim with mirrored margins for binding. The front and back covers are included as the first and last pages. A wraparound cover with a spine, an ISBN, and a barcode are not included and would need to be added for retail or print-on-demand distribution.

## License and Permissions

**Book content:** Copyright © 2026 Christine Walter. All rights reserved. The text, cover design, and artwork may not be reproduced or redistributed without written permission from the author. As stated in the book, readers and organizations may photocopy the Trust Baseline and the Part Three worksheets for personal and internal team use.

**Fonts:** Source Serif 4, Cormorant Garamond, and Inter are used under the [SIL Open Font License 1.1](https://openfontlicense.org/).

**Cited research:** All cited works remain the property of their respective authors and publishers.

**Build code:** No open-source license has been applied to the build scripts. Add a `LICENSE` file if you want others to reuse them.

## About the Author

**Christine Walter, LMFT, PCC**, is a Licensed Marriage and Family Therapist and a Professional Certified Coach. Her work brings together the clinical understanding of how relationships work and the coaching craft of how people change.

---

<p align="center"><em>Read a week. Practice a week. Build trust for life.</em></p>
