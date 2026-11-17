<!--
    chapters-spec.md
    Blueprint Phase 3: Chapter Specifications.
-->

# Agentic Filmmaking: Chapter Specifications

> ***Agentic Filmmaking*, the general-audience course: starting point, not yet revised.** This is the single-course plan of 2026-11-16. On 2026-11-17 Bear split the work into two repos. This one is for a general audience without a film background: people who probably know ChatGPT, and maybe a little Midjourney or Higgsfield. In Bear's words, it is the track *"where there's much more time spent on story making and filmmaking and why that's critical."* The course for trained filmmakers who already have a script and a vision, like Galen, is *AI Filmmaking*, in [/Users/bear/Documents/CoWork/bear-textbooks/books/ai-filmmaking](/Users/bear/Documents/CoWork/bear-textbooks/books/ai-filmmaking). Not yet revised for this audience: the reader paragraph, how much more weight the story chapters get, and whether Galen's film stays the running case. GATE 0 unsigned.


**Author:** Nik Bear Brown

*Phase 3 output from Blueprint. Written by /scaffold (silent mode) on 2026-11-16 from BLUEPRINT.md, outline.md and pantry/; revised the same day with Bear's decisions. Outcomes live in architecture.md. Galen's sessions are written out step by step in outline.md, under each chapter's "On the set"; this file refers to them rather than repeating them. Sidecar unverified until human sign-off.*

---

## Executive summary

- **What this is:** a spec for every chapter, detailed enough that a contributor could start drafting: the opening, the content blocks, the worked example, three exercises and the bridge to the next chapter. Then the case-study plan, contested claims, gaps, hard chapters and how fast each chapter will age.
- **What changed with Bear's decisions:**
  - **Framing:** the craft is framed as vocabulary for directing an agent.
  - **The +1:** judges against the filmmaker's intent; departures from history or taste are flagged once and logged as choices.
  - **The cabin:** removed from the failures; it is now the handoff and Galen's first session.
  - **Ch 4:** has the thesis exercise.
  - **Ch 8 and Ch 9:** carry the two still tiers.
- **Hardest chapters:** 11 (directing dialogue), 14 (compositing generated and live footage) and 15 (festival, copyright and disclosure rules). None has a real run yet.

---

## Chapter Anatomy Template

**TOC stage (now): every chapter has five parts.**

1. **The craft, as vocabulary:** the words a filmmaker uses to describe the picture in their head precisely enough for a model to produce it. Each term earns its place by changing what the model makes. Plain and practical; every term defined on first use.
2. **The agent does it:** what the model does by default, and how to override it. The agent is the hands; the filmmaker directs it directly. Model and tool names go only in a dated **"Tools as of"** box.
3. **The +1:** where the output departs from what the filmmaker intended. Named failures come from real work. A departure from history or from someone else's taste is not a failure: the agent flags it once, the filmmaker decides, and the decision goes in the production log.
4. **On the set: Galen's opening:** what was really done, with file paths, and whose hands did it (so far, Bear's). Where something has not been run: an exact session for Galen to run (in outline.md), never a description of what he would decide.
5. **Exercises:** at least three; one at Apply or above; one that produces something. Every exercise ends in a file and a line in the production log. Templates have blanks for the reader's own decisions; no finished prompts. Galen's prompts appear only as examples of his decisions.

**Draft stage (required later, per /c2):** a one-paragraph overview; 3 to 5 objectives; the opening case; a mid-chapter checkpoint; the worked example (part 4); a summary written as capabilities gained; key terms (film and AI side by side, in plain words); 3 to 5 discussion questions, one across chapters; further reading with one-line notes; the bridge question.

## Keyword Audit (proposed renames, not yet applied)

Most draft titles pass the search test but fail the learner test (they name a topic, not what the learner will do).

| # | Draft title | Proposed title | Why |
|---|---|---|---|
| Intro | Can You Make Your Film Now? | keep | an introduction may pose a question |
| 1 | How Films Tell Stories | Film Language: How Shots, Cuts and Sound Make Meaning | adds the field's keyword |
| 2 | Story: Idea, Conflict and Structure | Developing the Story: Idea, Conflict and Structure | names the action |
| 3 | The Screenplay | Writing the Screenplay and the Shot Table | names both outputs |
| 4 | The Visual Story | Planning the Visual Story: Contrast, Affinity and Look Rules | names the action |
| 5 | The Frame: Composition, Angle and Lens | Composing the Shot: Framing, Camera Angle and Lens | field keywords |
| 6 | Light and Color | Lighting and Color for the Frame | names the action |
| 7 | Designing the World | Production Design: Sets, Props, Costume and Characters | "designing the world" is metaphorical |
| 8 | Storyboards and the Shot List | Storyboarding and Shot Lists | names the action |
| 9 | Producing: Budget, Schedule and Crew | Producing: Budgeting, Scheduling and Crewing | names the actions |
| 10 | Movement: Camera and Action | Camera Movement and Animating the Shot | adds the AI action |
| 11 | Directing Performance and Coverage | Directing Performance, Dialogue and Coverage | dialogue is the hard case |
| 12 | Sound: Dialogue, Voice, Effects and Music | Sound Design: Dialogue, Voice, Effects and Music | field keyword |
| 13 | Editing: Continuity, Time and Rhythm | Film Editing: Continuity, Time and Rhythm | field keyword |
| 14 | VFX, Compositing and Finishing | Visual Effects, Compositing and Finishing | spells out VFX for search |
| 15 | Distribution, Festivals and Disclosure | Distribution, Film Festivals and AI Disclosure | field keywords |

## Chapter Specifications

**Introduction: Can You Make Your Film Now?**
*Problem it solves:* "I have a film in my head and I'm lost on the tech. Is this real, and what will it cost?"
*Opening:* the handoff. Bear stopped before designing Galen's cabin once it was clear his vision is not Galen's, and handed Galen the controls. (Galen opening 1 of 3.)
*Blocks:*
1. The thesis: the filmmaker conducts, the agent plays.
2. The agent is the hands: direct it yourself, without a translator.
3. What it costs, plainly, with the logged figures.
4. The two still tiers, and never paying for motion to find out what something looks like.
5. The first win: a finished opening scene that helps raise money.
6. Setup and the honesty rules (RULES 12 to 14); the pebble.
*Worked example:* the Wrong Ship. A textbook trireme reached two finished films before Galen caught it.
*Exercises:* set up the project and the log; make the pebble film; write a half-page note on where it departed from what you intended.
*Bridge:* the pebble looked like something but said nothing. What makes a sequence of shots mean something?
*Contributor notes:* TB ch 1; CA 1.1 to 1.2; the Agentic Filmmaking README. Common mistake: selling AI as effortless, or as the one making the calls.

**Ch 1: How Films Tell Stories**
*Problem:* "Why does one cut feel like a story and another like stock footage?"
*Opening:* a shot of food followed by a boy looking off-screen: the viewer builds the story (KGB Introduction).
*Blocks:*
1. Juxtaposition and beats.
2. Shot sizes, angles, mise-en-scène and focus, as words to type to an agent.
3. Continuity editing and montage.
4. Sound inside and outside the story world.
5. The five stages mapped to the agentic studio.
6. Bazin's question: what is a generated image a record of?
*Worked example:* the learner's pebble film taken apart shot by shot with this vocabulary.
*Exercises:* label a 30-second clip; build a two-shot juxtaposition from draft stills and write what it implies; a 300-word position on Bazin and generated images.
*Bridge:* now you can name what you see. Where does your film start?
*Contributor notes:* KGB Intro, ch 1; FS Module I and Bazin; TB ch 2; CA ch 1 to 3. Common mistake: a glossary with no making in it.

**Ch 2: Story: Idea, Conflict and Structure**
*Problem:* "I have an image in my head, not a story."
*Opening:* a viral AI short whose story came from the maker's memory of a museum visit, not from a prompt (VP case study).
*Blocks:*
1. Plot and story, conflict, need.
2. Premise, theme and the 25-word test.
3. Character, backstory and point of view.
4. Step outline and cards.
5. Three-act shape, and how short films differ.
6. The LLM as development partner, its default pull toward the familiar, and the override: your own material.
*Worked example:* Galen's decade-old scene, as he tells it, with the Theseus legend as its source.
*Exercises:* a logline and 25-word premise; a step outline; have an LLM draft an outline, audit it against RMM's cliché list, and rewrite the weakest three beats from your own material.
*Bridge:* you have the story. How do you write it so an agent can make it?
*Contributor notes:* BB Writing Your Story; RMM ch 1 to 2 and the clichés list; TB ch 4; CG concept. Common mistake: letting the LLM pick the idea.

**Ch 3: The Screenplay**
*Problem:* "How do I turn the story into something an agent can follow?"
*Opening:* the agent's notes on Galen's script, each flagged once: a cabin on an open-deck ship, a crew count that differs inside the script, a monocle out of period (his call), lightning against Bear's storyboard, lyrics still under copyright. (Galen opening 2 of 3.)
*Blocks:*
1. Format and a sample page.
2. Dialogue and subtext.
3. Exposition: show, don't tell.
4. Logline, treatment, synopsis, pitch.
5. The shot table as the generation plan (RULE 1), as a template with blanks.
6. AI coverage and a synthetic table read, read skeptically.
*Worked example:* the flags above as examples of flag-once-and-log, not as failures. Galen's session is in outline.md.
*Exercises:* format a 3 to 5 page short script; revise one on-the-nose scene to subtext; fill the shot-table template for your script and log a decision for every flag.
*Bridge:* the table says what is in each shot. What should the film look like?
*Contributor notes:* BB Dialog to Pitching; TB Script Format; Galen's SCRIPT-NOTES. Common mistake: treating the shot table as paperwork instead of the plan every prompt comes from.

**Ch 4: The Visual Story**
*Problem:* "Every frame I generate is pretty, and none of them belong together, or to me."
*Opening:* one film's visual-structure graph from BLK ch 9. [example chosen at research]
*Blocks:*
1. The basic visual components.
2. Contrast and affinity.
3. Space, line and shape.
4. Tone and color as structure.
5. The model's default look.
6. Look rules that override it in every prompt (RULES 1, 2).
*Worked example:* Bear's look for the draft storyboard (no lightning), set against Galen's script (lightning in nearly every beat). This shows two people's decisions, not a right answer. Galen's session is in outline.md.
*Exercises:* write your look rules (template with blanks); draw your visual-structure graph; **the thesis exercise:** make the same short scene twice under opposite look rules, or with a second person from the same script, and show the results side by side with the decisions that made them differ.
*Bridge:* the look is yours. How is each frame built?
*Contributor notes:* BLK ch 1 to 9 (core); BB Finding the Look; CR week 2. Common mistake: a mood board with no story attached.

**Ch 5: The Frame: Composition, Angle and Lens**
*Problem:* "The model gives me a frame. Is it the one in my head?"
*Opening:* the same action filmed from different camera positions tells different stories (KGB Introduction, "Camera Positions Make a Dramatic Difference").
*Blocks:*
1. Composition and framing people.
2. Camera height and angle.
3. Lenses and depth of field.
4. Shot size; objective and subjective shots.
5. The model's default framing, and camera words that override it.
6. The still check (RULE 6).
*Worked example:* in Film 1, Bear matched the model to the subject: one for the ship, another for faces and crowds (RULE 4).
*Exercises:* specify and generate one beat three ways (size, angle, lens) in draft stills; run one spec through two models and compare; keep-or-reject notes on ten stills, each reason stated against your intent.
*Bridge:* the frame is right. Is the light?
*Contributor notes:* KGB ch 3 to 5; BB Cinematography; BLK ch 3 to 4; TB ch 5; VP ch 3 to 4. Common mistake: trusting lens words the model ignores.

**Ch 6: Light and Color**
*Problem:* "My stills change light from one shot to the next."
*Opening:* one face lit hard and lit soft (BB, Hard vs Soft).
*Blocks:*
1. Why lighting matters.
2. Hard and soft light.
3. Key, fill and back.
4. Motivated light.
5. Color as continuity.
6. The model's default light, and the time-of-day, quality and palette words that override it.
*Worked example:* Bear's storm-light rework and his note (later in the day, a little darker, no lightning), shown as Bear's decisions. Galen's session is in outline.md.
*Exercises:* a lighting plan for your scene; generate the sequence in draft stills and mark every frame that drifts from your plan; repair the drifters.
*Bridge:* light and frame hold. Now the things and people in them.
*Contributor notes:* BB Lighting and Grip; BLK ch 5 to 6; CG lighting. Common mistake: light with no source in the world. Needs a cinematographer's review.

**Ch 7: Designing the World: Sets, Props, Costume and Characters**
*Problem:* "My hero looks different in every shot, and the ship isn't the one in my head."
*Opening:* the deepfake and likeness debate (CA 2.3).
*Blocks:*
1. The art department and the right details.
2. Wardrobe, makeup and props.
3. Design in rounds on draft stills.
4. Reference sheets and identity models (RULE 20).
5. Period detail as vocabulary: the agent flags a departure once, and the filmmaker's choice is logged.
6. Consent for likeness.
*Worked example:* the Wrong Ship, and the review-slide notes as the relay loop the course ends. Bear's ship rounds include the curl drawn at both ends when one was asked for (RULE 19), and Bear's own Aegeus replaced the agent's first tries. Then **the cabin, the handoff:** Galen's first session, step by step in outline.md.
*Exercises:* a character sheet in four or five angles; a hero-prop sheet; a log of every period departure in your designs, each recorded as your choice.
*Bridge:* the world exists. Lay out the whole scene before anything moves.
*Contributor notes:* BB The Art Department; RMM ch 6; CR week 2. Common mistake: one great portrait and no reference set; or "correcting" the filmmaker's world to match history.

**Ch 8: Storyboards and the Shot List**
*Problem:* "How do I see the whole film before I pay for it?"
*Opening:* Galen's 37-frame draft storyboard. (Galen opening 3 of 3.)
*Blocks:*
1. Shooting on paper and aspect ratio.
2. Arrows, labels and numbering.
3. Maps of the action.
4. The whole scene as draft stills on contact sheets (RULE 3).
5. The review pass and the superseded folder (RULE 12).
6. Hero stills for approved frames only; each becomes a clip's first frame.
*Worked example:*
- Two failures against the script were fixed: a spyglass where the script says monocle, and edge bars.
- Three items wait on Galen: the cabin, the period of the helmets, the crew count.
- The cabin frames are placeholders made before the handoff.
- Galen's review session is in outline.md.
*Exercises:* a numbered draft storyboard of your scene; a review log with keep, reject or question for every frame; a hero-still list and the shot list linked to it.
*Bridge:* every frame is approved. What will it cost to move them?
*Contributor notes:* KGB ch 2, 13; BB A Director Prepares; CG storyboards; VP ch 7. Common mistake: paying for hero stills before the drafts are reviewed.

**Ch 9: Producing: Budget, Schedule and Crew**
*Problem:* "How much will this really cost, and what do I spend it on?"
*Opening:* testing one video model properly can cost hundreds of dollars before a single real shot (VP Preface).
*Blocks:*
1. What a producer does.
2. Breakdown and script marking.
3. The budget in three lines: draft stills, hero stills, motion.
4. Test budget first.
5. Job and cost log (RULE 14).
6. What stays human, and footage as a fundraising tool.
*Worked example:* the logged prices, and the Wrong Ship in money. [NEEDS HUMAN INPUT: credits spent on Films 1 and 2 before the ship was caught.] Galen's budget session is in outline.md.
*Exercises:* break down your script; fill the budget template with the three lines priced separately, plus a test budget; a generate, shoot or cut decision for every shot, with reasons.
*Bridge:* the money is planned. Make the stills move.
*Contributor notes:* BB Production; RMM ch 3 to 5 and the sample budgets; Safety on the Set. Common mistake: budgeting finals and forgetting retries. [NEEDS HUMAN INPUT: per-tier still prices; dollar price per credit.]

**Ch 10: Movement: Camera and Action**
*Problem:* "My clips move, but not the way I meant."
*Opening:* the learner's own pebble clip from the Introduction, replayed: why does the camera move?
*Blocks:*
1. Types of camera movement.
2. Motivated and unmotivated movement.
3. Direction of movement on screen.
4. Image-to-video from a hero still, and the model's default motion.
5. One stated move that overrides it (RULE 7).
6. Four-frame contact sheets (RULE 8).
*Worked example:* Film 1's trireme clips and the prompt that stopped the oars bending and merging. Galen's one-clip session is in outline.md.
*Exercises:* animate three approved hero stills, one stated move each; contact sheets for every clip; a reject log with each departure from your intent named.
*Bridge:* the camera moves. Can the people act?
*Contributor notes:* KGB ch 5, 12, 14; BLK ch 7; CR week 3; VP ch 5. Common mistake: judging a clip by its first frame.

**Ch 11: Directing Performance and Coverage**
*Problem:* "Two characters talk, and the scene falls apart."
*Opening:* a shot-reverse-shot that crosses the line (FS 180-degree rule; KGB ch 8).
*Blocks:*
1. The director's jobs and script analysis.
2. Blocking and coverage.
3. The 180- and 30-degree rules, and eyelines.
4. Two- and three-character dialogue geometry.
5. Reference-to-video, expression and lip-sync.
6. The model's default axis, and the floor plan that overrides it.
*Worked example:* the Aegeus reference-video test (three models held Bear's Aegeus face). **Not run yet:** a two-character dialogue scene. Galen's session is in outline.md.
*Exercises:* a coverage plan with a floor map; generate master, two singles and reverses (drafts, then hero stills, then motion); a take-choice note.
*Bridge:* the picture plays. What does it sound like?
*Contributor notes:* BB Director, Continuity and Coverage; KGB ch 8, 11, 15 to 17; CA 5.5.3. Common mistake: trusting the model with screen direction. Needs a working director's review.

**Ch 12: Sound: Dialogue, Voice, Effects and Music**
*Problem:* "Half the film is sound, and mine is an afterthought."
*Opening:* one clip played silent, with its ambient sound, and with music. [demonstration built at drafting]
*Blocks:*
1. The sound team, microphones, room tone and ADR.
2. Diegetic and non-diegetic sound.
3. Voice synthesis and cloning, with consent.
4. The model's default ambience; effects and music.
5. The agent's mix (RULES 15 to 17).
6. The rights record.
*Worked example:* Film 2's narration, one line per shot, 7 of 25 shots slowed to fit, ambience leveled then ducked, -16 LUFS. **Not run yet:** a score. Galen's session is in outline.md.
*Exercises:* a sound list for your scene; build and mix the soundtrack to a target; a rights and consent record for every source.
*Bridge:* every piece exists. Now cut it.
*Contributor notes:* BB Audio Basics; TB ch 6; CG audio; CA 5.5.3 to 5.5.4. Common mistake: no ear check. Needs a sound editor's review.

**Ch 13: Editing: Continuity, Time and Rhythm**
*Problem:* "The agent assembled it. Why doesn't it feel like mine?"
*Opening:* two cuts of the same scene, judged by Murch's rule of six (BB).
*Blocks:*
1. The six steps from logging to final cut.
2. Continuity cuts and jump cuts.
3. Match cuts, punch-ins and reverses.
4. Compressing and expanding time.
5. Beginnings, endings, transitions and rhythm.
6. The agent's default assembly, and cut notes typed to it directly.
*Worked example:* the agent's assemblies of Films 1 and 2 and the two design films, and what the filmmaker's cut notes would change. Galen's cut session is in outline.md.
*Exercises:* have the agent assemble your scene; cut it to a fine cut with your own notes; a cut-by-cut justification against the rule of six.
*Bridge:* the cut works. Is it finished?
*Contributor notes:* BB The Work of the Editor; KGB ch 6, 7, 9, 10; BLK ch 8; TB ch 7, 8, 10. Common mistake: accepting the assembly as the cut. Needs an editor's review.

**Ch 14: VFX, Compositing and Finishing**
*Problem:* "I shot one real thing on my phone. Can it live in the generated world?"
*Opening:* the history of effects from matte paintings to CGI (CA 1.3), or a hybrid VFX practitioner from CA ch 4. [chosen at research]
*Blocks:*
1. Compositing and green screen.
2. Object removal and replacement.
3. Video-to-video restyling.
4. Consistency across real and generated shots.
5. Titles and overlays in post (RULE 9).
6. Upscaling last, per clip (RULE 11).
*Worked example:* 4K upscaling on Films 1 and 2, then dropped by Bear for later films. **Not run yet:** a generated element in a live-action plate. Galen's session is in outline.md.
*Exercises:* composite one hybrid shot; finish your cut (titles, overlays, upscale); a shot-by-shot real-or-generated label sheet.
*Bridge:* the film is done. Who sees it, and what do you tell them?
*Contributor notes:* CA 1.3, 5.4, 5.5; CR week 4; CG effects; VP ch 6. Common mistake: polishing past the point anyone can see. Color grading has no pantry source.

**Ch 15: Distribution, Festivals and Disclosure**
*Problem:* "How do I release this honestly and get it seen, or funded?"
*Opening:* the festival programmer's view of a submission (RMM ch 10).
*Blocks:*
1. Distribution routes.
2. Festivals and the circuit.
3. Delivery files, captions and metadata.
4. Synthetic-media disclosure and credits.
5. Who owns generated footage.
6. The pitch reel and fundraising.
*Worked example:* four films posted to the Agentic Filmmaking playlist with the synthetic-media flag and captions. **Not run yet:** a festival submission and a pitch reel. Galen's session is in outline.md.
*Exercises:* a delivery package for your scene; a festival list with each festival's AI rule, dated; a credits-and-rights audit of your own film.
*Bridge:* the capstone.
*Contributor notes:* RMM ch 9 to 10; CG Share; BB Getting Started in the Business; CA ch 6. Common mistake: stating a festival or copyright rule without a date. Needs a legal reviewer.

**Capstone: The Opening Scene**
*Capability:* the whole pipeline on the learner's own film, checked against a self-review checklist.
*Deliverables:* script and shot table, look rules, reviewed draft storyboard, hero stills, budget, clips, soundtrack, cut, release, log.
*Length:* the learner's choice. Self-paced and ungraded.

## Case Study Strategy

**Domain coverage map**

| Domain | Chapters | Concepts illustrated |
|---|---|---|
| Galen's opening (period drama at sea) | worked example in Intro and Ch 2 to 15; openings in Intro, 3, 8 | everything; the running case |
| The learner's own film | exercises everywhere; Ch 10 opening (the pebble clip) | transfer to their own work |
| Classic narrative film (Brine's examples, Film Studies case-study films) | openings in 1, 5, 11, 13 | juxtaposition, camera position, the axis, cutting |
| Visual design theory (Block) | 4 | visual structure |
| AI practitioners (VP case study; CA ch 4 interviews) | openings in 2, 7, 14 | memory as story source, likeness ethics, hybrid VFX |
| Cost of testing (VP Preface; logged prices) | 9 | budgeting |
| The festival circuit (Munroe) | 15 | distribution |

**Over-representation flag:** Galen's film appears in far more than 30 percent of chapters. That is by design (it is the running case), so the rule is applied to chapter openings instead: Galen opens only three chapters.

**Failure cases** (all real, all departures from intent): the Wrong Ship (Ch 7, Intro, Ch 9); the spyglass where the script says monocle (Ch 8); the curl drawn at both ends of the hull (Ch 7); the agent's rejected first-try kings (Ch 7); the oars that smeared (Ch 10). Departures from history (helmets, the monocle, the cabin) are taught as flags and logged choices, not failures.

**Escalation:**
- *Act One* cases have one concept and a clear answer: is this a cliché? does this page follow format?
- *Act Two* cases need judgment: does this still or this take match what I intended?
- *Act Three* cases are synthesis with no single answer: is this cut mine? is this release honest enough?

**The thesis case:** Ch 4's side-by-side (the same scene made under opposite look rules, or by two people) is the direct evidence for the thesis. Bear's draft storyboard and Galen's own look rules are a real pair once Galen runs his session.

**Concepts with no case yet:** dialogue lip-sync (Ch 11), a composed score (Ch 12), compositing into live footage (Ch 14), color grading (Ch 14), a festival submission (Ch 15). No hypotheticals are planned: each gets a real session, or the chapter says "not run yet".

## Contested Claims Audit

| Claim | Status | How the course handles it |
|---|---|---|
| A generated film is authored by the filmmaker | Disputed | Present both sides (CA 1.2, 2.3). The course argues that authorship lives in decisions: the filmmaker conducts, the agent plays. The learner writes their own position (Ch 1). |
| Generated footage can be copyrighted | Emerging, varies by country | Dated sources only; no assertion. A "rules as of" box in Ch 15. |
| Festivals accept AI films | Emerging, varies by festival | A dated table, built at research and refreshed each edition. |
| Voice cloning and likeness use are lawful with consent | Emerging, varies by jurisdiction | Teach consent records as practice; point to law with dates; no legal advice. |
| AI makes filmmaking cheaper | Emerging | Show only logged numbers. No claims about the cost of a whole feature. |
| Models obey camera and lens words | Emerging, model-specific | Tested in exercises (Ch 5), never asserted. |
| AI will replace film crews | Disputed | Acknowledge the labor debate (CA 1.2); the course claims only that one person can now direct a short. |
| The photograph has a special claim on reality (Bazin) | Disputed in film theory | Pose it as a question in Ch 1, with formalist replies. |

## Coverage Gaps

| Gap | Why excluded | Name in preface? |
|---|---|---|
| Documentary | [NEEDS HUMAN INPUT — open decision 4]; the pantry is fiction-centred | yes, either way |
| Animation as a form | outside the thesis (a live-action look) | yes |
| Operating a real camera and grip | only hybrid plates in Ch 14 | yes |
| Training in one editing or compositing program | ages fast; the agent assembles | no |
| Film history and theory beyond Ch 1 | covered better in film studies courses | no |
| Composing music | Ch 12 covers selection, spotting and generation only | yes |
| Color grading | research gap; may enter Ch 14 | yes, if still missing |
| Contracts and legal clearance | not legal advice; Ch 15 points to rules | yes |
| Interactive and immersive media | CA covers it; out of the short-film scope | no |

## Hard Chapters

1. **Ch 11, Directing Performance and Coverage.**
   - *Why hard:* models are weakest here, and no dialogue scene has been run.
   - *If written poorly:* it teaches learners to accept dead performances and broken eyelines.
   - *Ideal author:* Bear, with a working director as reviewer. [NEEDS HUMAN INPUT — who reviews?]
2. **Ch 14, VFX, Compositing and Finishing.**
   - *Why hard:* hybrid work needs real footage and VFX skill, and no hybrid shot exists yet.
   - *Ideal reviewer:* a compositor; CA ch 4's hybrid-VFX interview is a lead.
3. **Ch 15, Distribution, Festivals and Disclosure.**
   - *Why hard:* the rules change monthly and differ by festival, platform and country.
   - *If written poorly:* it gives learners wrong legal-sounding advice.
   - *Ideal reviewer:* an entertainment lawyer or a festival programmer.

## Aging Risk Audit

| Chapter | Stable core | Current-state content | Ages in 3 yrs / 5 yrs |
|---|---|---|---|
| Intro, 1 | film vocabulary; who decides | the tool map, prices | low / medium |
| 2, 3 | story, structure, format | LLM features | low / low |
| 4, 5, 6 | visual structure, frame, light | model defaults, override words | medium / high |
| 7 | the art department, consent | identity models, reference limits | high / high |
| 8 | storyboard practice, the two tiers | which models fill each tier | low / medium |
| 9 | breakdown, budgeting | prices per tier and per second | high / high |
| 10, 11 | movement, coverage, the axis | video models, lip-sync | high / high |
| 12 | sound craft, mixing | voice and music models | medium / high |
| 13 | editing grammar | agent assembly | low / medium |
| 14 | compositing principles | specific VFX tools | high / high |
| 15 | festivals, credits | AI rules, copyright, disclosure flags | high / high |

**Structural fix (in the anatomy):** craft, defaults-and-overrides and judgment live in the running text; tools, prices and rules live in dated boxes. The evidence that this is needed is in the pantry itself: the 2025 tool chapter in *Cinematic Algorithms* already names tools Bear's 2026 runs did not use.
