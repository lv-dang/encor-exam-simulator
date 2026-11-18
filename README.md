# ENCOR 350-401 Exam Simulator

A free, single-file practice exam for the **Cisco CCNP / CCIE Enterprise Core (ENCOR 350-401) v1.2** exam. It runs in any browser, works well on a phone, and needs no install, account or server.

### ▶ [Open the simulator](https://lv-dang.github.io/encor-exam-simulator/)

![Version](https://img.shields.io/badge/version-1.2.0-4fd1c5) ![Questions](https://img.shields.io/badge/questions-814-7aa2ff) ![Blueprint](https://img.shields.io/badge/blueprint-ENCOR%20v1.2-f6ad55) ![No install](https://img.shields.io/badge/install-none-48bb78)

---

## What's inside

- **814 original questions** covering every objective of the ENCOR v1.2 blueprint (wireless is left out, because Cisco removed it in v1.2)
- **Exhibits:** about 330 questions come with a CLI output, JSON payload or network topology. About 100 explanations also include a diagram.
- **Question types:** single answer, choose two, choose three, and drag and drop (put steps in order, or match items)
- **Explanations:** every question explains why the right answer is right and why each wrong answer is wrong, with links to Cisco documentation or RFCs for further reading
- **271 hard items:** multi-step and exhibit questions you can drill on their own

### Questions per domain

| # | Domain | Exam weight | Questions |
|---|--------|:-----------:|:---------:|
| 1 | Architecture | 15 % | 121 |
| 2 | Virtualization | 10 % | 83 |
| 3 | Infrastructure | 30 % | 245 |
| 4 | Network Assurance | 10 % | 82 |
| 5 | Security | 20 % | 161 |
| 6 | Automation & AI | 15 % | 122 |

## Ways to practise

| Mode | What it does |
|------|--------------|
| **Full mock exam** | 100 random questions in 120 minutes, spread across the six domains by exam weight. Timed, and you can't go back, just like the real exam. |
| **Practice exams A–E** | Five fixed exams of 100 questions each, with no overlap. You get the same questions every time, so you can compare your scores. **D and E are kept out of every other mode until you take them**, so you can use them as an unseen final check before you book. |
| **Custom session** | Choose weak areas by domain, subtopic or topic tag, then pick a mix, a mode and how many questions you want. |

**Mixes for custom sessions**

- **Weak only:** only the topics you picked
- **70 / 30:** 70 % from your weak areas, 30 % from the rest of the blueprint
- **Blueprint:** all topics at real exam weights
- **Due for review:** spaced repetition. A missed question comes back the next day. Each correct answer pushes it further out: 1, 3, 7, then 21 days.
- **Hard only:** multi-step and exhibit questions

**Modes:** *Practice* shows the answer and explanation after each question. *Exam simulation* is timed at 1.2 minutes per question and shows your results only at the end.

An optional setting puts questions you haven't seen and questions you missed first.

## Results and progress tracking

- Score by domain and by subtopic, plus a list of subtopics below 75 % with a one-tap **Drill these subtopics now** button
- Time per question: your slowest questions, and questions you rushed (under 20 seconds) and got wrong
- Full answer review with your misses shown first, and a **Retry missed** button
- Readiness check for each domain: you need to have seen at least 80 % of its questions and scored at least 85 % on your first try
- Score history chart for practice exams A–E against an 85 % target
- Flag any question you doubt. Flagged questions are listed with their IDs, and you can practise them as a set.

> Cisco doesn't publish the number of questions or the pass mark. The 100-question mock is an estimate based on the published 120-minute length. The 85 % target is a rule of thumb, not a guarantee that you'll pass.

## Your progress is saved

Progress is saved in your browser's local storage. Nothing is sent anywhere.

- **New versions keep your progress.** Your history and any unfinished session carry over. When a question is rewritten, only its old result is reset.
- **Moving to another device or browser:** go to **Progress → Keep your progress** and use *Copy backup text* / *Paste backup text*. If you're running the file locally, you can also use *Download backup* / *Restore from file*.

## Running it locally

Download `index.html` (or the release file) and open it in any modern browser. Everything is in that one file, apart from Google Fonts. If you're offline, the page uses system fonts instead.

## Sources

The questions follow the ENCOR v1.2 blueprint and draw on these resources. They were checked against current Cisco documentation and RFCs.

- *CCNP and CCIE Enterprise Core ENCOR 350-401 Official Cert Guide*, 2nd ed. (Cisco Press)
- *CCNP and CCIE Enterprise Core ENCOR 350-401 Exam Cram*
- *31 Days Before Your CCNP and CCIE Enterprise Core Exam*
- *CCNP and CCIE Enterprise Core & ENARSI Portable Command Guide*
- INE ENCOR course

Every question is original. None are taken from the real exam or from braindumps.

## Changelog

**v1.2.0** · 2026-11-17
- About 55 more context topologies and 50 more explanation diagrams
- Many more visuals for security, virtualization, routing concepts, FHRP, multicast and automation

**v1.1.0** · 2026-11-17
- Full technical audit of all 814 questions
- Rebuilt ordering items that had an arbitrary step order; turned one item into a matching item
- Fixed a static VRF route, a TACACS+ exhibit, a SPAN statement and the wording of several questions

**v1.0.0** · 2026-11-17
- First release: 800 questions, full mock, practice exams A–E, exhibits, drag and drop, and multi-answer items

## Disclaimer

This is an independent study tool. It is not affiliated with, endorsed by or sponsored by Cisco Systems, Inc. Cisco, CCNP, CCIE and ENCOR are trademarks of Cisco Systems, Inc.
