<!--
    vision.md
    Blueprint Phase 1: Vision and Positioning.
-->

# Agentic Filmmaking: Vision

> ***Agentic Filmmaking*, the general-audience course: starting point, not yet revised.** This is the single-course plan of 2026-11-16. On 2026-11-17 Bear split the work into two repos. This one is for a general audience without a film background: people who probably know ChatGPT, and maybe a little Midjourney or Higgsfield. In Bear's words, it is the track *"where there's much more time spent on story making and filmmaking and why that's critical."* The course for trained filmmakers who already have a script and a vision, like Galen, is *AI Filmmaking*, in [nikbearbrown/ai-filmmaking](https://github.com/nikbearbrown/ai-filmmaking). Not yet revised for this audience: the reader paragraph, how much more weight the story chapters get, and whether Galen's film stays the running case. GATE 0 unsigned.


**Author:** Nik Bear Brown

*Phase 1 output from Blueprint. Written by /scaffold (silent mode) on 2026-11-16 from BLUEPRINT.md, outline.md, pantry/ and the Agentic Filmmaking notes; revised the same day with Bear's decisions. There is no book.md yet, so Bear's 2026-11-16 words stand in for it. Sidecar unverified until human sign-off.*

---

## Executive summary

- **What this is:** who the course is for, what kind of course it is, what it argues, and how it differs from the three closest alternatives.
- **What is settled (Bear, 2026-11-16):**
  - **Format:** a self-paced online course with no fixed length.
  - **Reader:** anyone who wants to make AI films, especially people with a clear vision who lack the technical skill to get an AI to produce it.
  - **Thesis:** the filmmaker conducts; the agent plays.
- **What is open:** Galen's consent to be the public running case, the cost to students, and fiction-only versus documentary too.

---

## Book Concept Summary

This course teaches **the filmmaker's vocabulary, and how to direct an AI agent with it through every stage of making a film**, to **anyone who wants to make AI films, especially those with a clear vision and no technical skill**. It does it by **following one real film (Galen's opening scene) from idea to release, in the order costs rise: words, draft stills, hero stills, motion, sound, cut**. It fills the gap left by classical filmmaking textbooks (craft, but no AI and a crew assumed) and by AI filmmaking courses (tools, but little craft). It succeeds if the student can **make and release the opening scene of their own film, with a production log that shows every decision, cost and AI disclosure, without going down a rabbit hole of bad decisions.**
[CONFIRMED: Bear, 2026-11-16, reader and deployment; the rest follows from BLUEPRINT.md]

**Biggest unresolved structural question:** whether Galen agrees to be the public running case. Every chapter's "On the set" depends on it.

## Book Type and Deployment Specification

**Type:** a self-paced online course, with no fixed length. Not a semester course, not a workshop. [CONFIRMED: Bear, 2026-11-16] Chapters run in sequence, but each chapter's AI half can be re-entered by task ("how do I storyboard with an agent?"), so it also works as a handbook.

**Primary use:** one person, on their own time, making the opening of their own film.

**Secondary use:** viewers of the Agentic Filmmaking playlist, who see the same running case. [INFERRED FROM: README, "The series and the course"]

**Explicitly NOT designed for:**
- semester or workshop delivery;
- studio VFX professionals;
- software training for one editor or compositing package;
- a film theory or history survey;
- prompt engineering for its own sake.

**How the TOC signals the type:** chapter titles use the field's own words (screenplay, storyboard, producing, editing), and every chapter ends in a file the learner made. The AI work sits inside every chapter instead of in a separate part.

**Assessment requirements** (self-paced, so nothing is graded; detail in architecture.md):

| Assessment | Status |
|---|---|
| Chapter exercises, each ending in a file | needed |
| Running production log (decisions, costs, job IDs, superseded files) | needed |
| Capstone, checked against a self-review checklist | needed |
| Self-check quizzes | desired |
| Flashcards for the glossary | desired |
| Exam bank | out of scope |
| Semester LMS modules | out of scope |
| Hosting platform | [NEEDS HUMAN INPUT — it decides the quiz format] |

## Learner Profile

Target reader: anyone who wants to make AI films. Many already carry a clear vision in their head; what they lack is the technical skill to get an AI to produce it. Comfortable chatting with an AI; no film school, no editing software, no camera required. The craft half of each chapter is what separates this course from tool tutorials. Galen is the running case, not the target reader: an old-school filmmaker with UCLA training who is new to AI, whose judgment models the +1. [CONFIRMED: Bear, 2026-11-16]

In Bear's words, the course is *"for people who want to make AI films, basic tips on how to do that ... for people who just are lost on the tech"*. They *"have a dream of making films"* and want to start making their vision without *"going down a rabbit hole of bad decisions"*.

**What they reliably know:** watching films; chatting with an AI; shooting phone video; basic file handling.

**How the craft is taught to them:** as vocabulary. Shot size, lens, light quality and period detail are how a filmmaker describes the picture in their head precisely enough for a model to produce it. Plain and practical; every term defined on first use.

**Prior misconceptions** (each one is a source's own warning, so the course can quote it):

1. *"The AI makes the film from a prompt."* The Curious Refuge syllabus itself says there is much more to it than typing a prompt (CR week 1).
2. *"Better gear makes a better film."* Barrance opens by refuting this (TB ch 1).
3. *"A beautiful frame is a good shot."* Block and Brine both tie the frame to story structure (BLK ch 9, KGB ch 1).
4. *"The video model will fix a bad still."* It will not: fix it at the still (RULES 2, 3).
5. *"I'll find out what it looks like in the video."* Never pay for motion to find out what something looks like; the Wrong Ship reached two finished films that way.
6. *"Generated footage is cheap."* Testing a video model costs real money; 100 test clips can cost hundreds of dollars (VP Preface).
7. *"Generated footage needs no credit, disclosure or consent."* (CA ch 2.3; RULE 13)
8. *"The AI should make the creative calls."* The agent is the hands; the filmmaker decides.

**Current capability gap:** they cannot describe the picture in their head precisely enough for a model, hold a look across generated images, catch where output departs from their intent, budget the expensive steps, or finish and release a film honestly labelled.

**Motivation:** creative. They want to make *their* film, and some want footage that helps raise money for the rest.

## Prerequisite Map

Only true prerequisites are listed. Story structure, film vocabulary, editing and audio terms are taught as content, not assumed.

| Prerequisite | Safe to assume? | Treatment |
|---|---|---|
| Chatting with an AI assistant | Yes | none |
| Running a CLI agent | Probably | Introduction setup |
| Keeping a project folder in order (names, superseded files) | Probably | Introduction setup, then embedded |
| An account and credits on a generation service | No | [NEEDS HUMAN INPUT — which service, who pays, is there a free path?] |
| A phone or camera | Probably | needed only for Ch 14's hybrid work |

**Prerequisite decision:** four items are rated No or Probably, which crosses the threshold of three. Option chosen: **(1) a foundations chapter**, folded into the Introduction, which acts as Chapter 0 (agent setup, project folder, production log, accounts).

## Central Argument

Thesis: the filmmaker conducts; the agent plays. The agent generates, logs and prices options; every choice of what to keep, reject or change belongs to the filmmaker. The proof is that two people can take the same idea, run the same tools and make completely different films, because the difference lives in their decisions, not in the software. The course teaches the tech so it stops being the obstacle, and never makes the creative calls for the reader. [CONFIRMED: Bear, 2026-11-16]

**Two consequences:**
- The agent is the hands. "Direct it yourself", not "do it yourself".
- Bear's role ends at teaching. The course exists so the filmmaker talks to the agent directly, without anyone relaying notes.

**Supporting method:** the cost order. Decide everything you can on cheap draft stills; pay for a hero still only for a clip's first frame; pay for motion last.

**Thesis test:** the TOC reflects it.
- The Introduction opens on the handoff (Bear stopping before the cabin and handing Galen the controls).
- Ch 4's exercise proves it directly: the same scene made under opposite look rules, or by two people.
- Every "On the set" ends in a session Galen runs himself.

## Field Positioning

**1. Blain Brown, *The Basics of Filmmaking* (Routledge, 2020)**
- *Covers that this course also covers:* the whole craft, from screenwriting to editing, by department.
- *Misses:* AI entirely; it predates the tools.
- *What this course changes:* it assumes a crew, a budget and a set. This course is for the learner who has none of those, and teaches the same craft as the vocabulary for directing an agent.

**2. Curious Refuge, *AI Filmmaking Course* (four-week syllabus)**
- *Covers:* AI tools across concept, directing, cinematography, VFX and distribution, with an assignment each week.
- *Misses:* depth of craft (filmmaking concepts are one goal among many in week 1); an agent that runs the tools and keeps the log.
- *What this course corrects:* it teaches tool by tool, so it ages with the tools. Its week 2 goals include removing watermarks from videos; this course keeps disclosure and credit (RULE 13).

**3. James Hutson and Andrew Allen Smith, *Cinematic Algorithms* (CRC Press, 2025)**
- *Covers:* AI in video production, ethics and authorship, the history of effects, 12 interviews with AI filmmakers, and workflows for each kind of generation.
- *Misses:* teaching the craft; exercises a learner can complete; cost.
- *What this course corrects:* its tool chapter already names tools that Bear's 2026 runs did not use. Tools belong in dated boxes, not in the spine.

**Positioning statements:**
- Unlike *The Basics of Filmmaking*, which teaches each department of a crewed production, this course teaches the same craft to one person directing an agent, for learners with a vision and no crew.
- Unlike the Curious Refuge course, which teaches AI tools week by week, this course teaches the filmmaker's vocabulary and has an agent run the tools, for learners who want skills that outlast this year's models.
- Unlike *Cinematic Algorithms*, which surveys AI in film and its debates, this course makes a film from idea to release with every cost and failure on the record, for learners who want to make work, not study it.
