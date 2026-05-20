# Revision Notes

Track what you've added, removed, or rewritten here.

## 2026-05-07 — book.md created

Drafted `book.md` for the bundle. Audience: undergraduates in PSY 101 plus pre-med, nursing, social work, and education students who need the prerequisite. Voice anchored on contemporary-mathematics chapter 1. The signature pedagogical move: methods are taught as part of every finding (the replication crisis is named in Ch 2 and stays visible in every chapter), and pop-psychology myths are corrected by name in the prose where the related correct mechanism is taught.

## 2026-05-07 — Attenborough × Feynman v1.1 conversion run: Chapters 1–16

16 chapters dispatched in parallel to subagents. `_toc.md` rewritten to flat structure. Source folders deleted after Combined Test passed.

| Ch | Slug | Words | Notes |
|---|---|---:|---|
| 01 | introduction-to-psychology | 6,052 | 5 source modules → 3 concepts (what psychology is; history & schools; contemporary subfields). Cold open: Wundt's 1879 Leipzig lab. |
| 02 | psychological-research | 6,336 | 5 source modules → 3 concepts (scientific method; research designs; replication crisis). Cold open: 2015 Open Science Collaboration finding 36% replication. |
| 03 | biopsychology | 6,157 | 6 source modules → 3 concepts (neurons & neurotransmitters; brain structure & lateralization; genetics & evolution). Cold open: Phineas Gage, September 13, 1848. Corrects the 10%-of-the-brain and left-brain/right-brain myths. |
| 04 | states-of-consciousness | 5,737 | 7 source modules → 4 concepts (circadian rhythms; sleep architecture; why we sleep; altered states). Cold open: sleep lab at 3 AM, REM paradox. |
| 05 | sensation-and-perception | 5,673 | 7 source modules → 3 concepts (sensation/transduction; vision & audition; perception & attention). Cold open: a child seeing for the first time after cataract surgery. |
| 06 | learning | 6,555 | 5 source modules → 3 concepts (classical conditioning; operant conditioning; observational learning). Cold open: loggerhead hatchlings vs. Julian learning to surf — instinct vs. learning. *Filename was `learning.md`; renamed to `06-learning.md` in the cleanup pass.* |
| 07 | thinking-and-intelligence | 9,873 | 7 source modules → 5 concepts (concepts/prototypes; problem-solving & heuristics; intelligence theories; IQ testing; nature & nurture). Cold open: Kahneman's Linda problem (conjunction fallacy). Largest chapter in the book — agent went deep on every concept. Corrects multiple myths (left-brain/right-brain, IQ fixed, race & intelligence). |
| 08 | memory | 7,957 | 5 source modules → 3 concepts (sensory/working/long-term; explicit/implicit memory; forgetting & distortion). Cold open: H.M. on a Hartford operating table, September 1, 1953. Loftus and Jennifer Thompson cases. |
| 09 | lifespan-development | 6,720 | 5 source modules → 3 concepts (developmental research; cognitive development; social-emotional development). Cold open: the Dunedin longitudinal study. |
| 10 | emotion-and-motivation | 7,009 | 5 source modules → 3 concepts (theories of emotion; biological motivation; psychological motivation). Cold open: Ekman 1967 in the Fore highlands of Papua New Guinea. |
| 11 | personality | 7,113 | 10 source modules → 4 concepts (psychodynamic; trait theories; social-cognitive; humanistic). Cold open: Bill and Roger Clinton — same parents, very different lives. Corrects MBTI validity, personality fixedness, handwriting analysis, astrology. |
| 12 | social-psychology | 8,122 | 8 source modules → 4 concepts (attribution & cognitive dissonance; conformity & obedience; prejudice & stereotypes; helping & aggression). Cold open: Asch line task. NAMES the methodological/ethical critiques of Stanford Prison Experiment (Le Texier) and corrects the Kitty Genovese 38-witness myth. |
| 13 | industrial-organizational-psychology | 5,397 | 5 source modules → 3 concepts (selection & assessment; motivation & job satisfaction; leadership & culture). Cold open: October 2019 telework decision overturned by 2020 pandemic. Corrects MBTI-as-job-predictor myth. |
| 14 | stress-lifestyle-and-health | 5,905 | 6 source modules → 3 concepts (stress response; coping & social support; mind-body health). Cold open: Selye 1936 noticing the general adaptation syndrome in stressed rats. |
| 15 | psychological-disorders | 6,217 | 12 source modules → 3 concepts (defining disorder; anxiety/mood/trauma; schizophrenia/eating disorders). Cold open: Rosenhan 1973 with Cahalan's 2019 correction. Corrects four major myths: schizophrenia ≠ split personality, mental illness ≠ violence, depression ≠ sadness, eating disorders ≠ choice. |
| 16 | therapy-and-treatment | 7,108 | 6 source modules → 3 concepts (psychotherapy approaches; biomedical treatments; evaluating treatment). Cold open: Freud's Vienna 1900 → modern RCT. Corrects "all therapy is just talking", "medications fix chemical imbalances", "ECT is barbaric". The book's closer — closing summary reflects on the arc from Wundt 1879 to modern evidence-based treatment. |

**Totals.** 16 chapters, 107,968 words. 48 companion files (16 each in `pantry/`, `images/`, `bookmaps/`). All chapters above the 3,500-word floor (the leanest is Ch 13 at 5,397; the densest is Ch 7 at 9,873). Forbidden-phrase audit: 21 stray hits in the first pass, all fixed in place. Final audit: 0 hits across all 16 chapters.

**Source folders.** All 16 source subfolders deleted after verification. 10 folders weren't auto-deleted by their agents (path-mapping issues with `rm -rf` from inside agent contexts) — cleaned up in the final pass.

**Filename cleanup.** Two issues caught in the cleanup pass:
- Ch 6 (learning) was saved as `learning.md` (no chapter number prefix) by its agent; renamed to `06-learning.md` everywhere. The agent reported using the "obvious" slug from the chapter title; the prompt should have been more explicit (it wasn't).
- Ch 10 (emotion-motivation) had companion duplicates inside `chapters/` with `-pantry`, `-images`, `-bookmap` suffixes. The canonical companions exist in the proper folders; the duplicates were removed.

**Voice consistency across the run.** Anchored on contemporary-mathematics/chapters/01-sets.md throughout. Cold opens hit the canonical scenes — Wundt's lab, Phineas Gage, H.M., Asch, Milgram (with critique), Selye, Rosenhan (with correction), Freud's Vienna. Every chapter names the methodological humility — what we know, what we don't, what changed our minds. Pop-psychology myths corrected by name throughout (10% of the brain, left-brain/right-brain, MBTI, Kitty Genovese 38, schizophrenia split-personality, "stress causes ulcers" without context, "chemical imbalance theory" as a complete account).

**TOC.** Rewritten to flat structure pointing at the 16 chapter files.

**Known follow-ups.**
- Ch 13 (IO Psychology) at 5,397 words sits at the lower end of target range. Bookmap names what was deferred — could expand if you want it richer.
- Ch 7 (Thinking and Intelligence) at 9,873 words is above the 8,000 ceiling — the agent went deep on five concepts instead of three. The chapter is solid but worth a structural review for whether to split into two chapters or trim.
- The myth-correction discipline varies in placement across chapters (some inline, some in dedicated subsections, some at chapter end). A consistency pass before publication is worth doing.

## 2026-05-12 — Running Project added: "Claude as Subject"

Generated 16 end-of-chapter LLM Exercise blocks via the Running Project Exercise Generator workflow. Project selected: **Claude as Subject** — student treats the LLM as the experimental subject and runs one psychological probe per chapter, culminating in a 5,000–7,000 word "Psychology of a Language Model" report.

The student picks Claude as the n=1 subject for the semester. Each chapter's probe maps directly to the chapter's named concepts (Wundt-style reaction time → architecture; James-Lange → embodiment; Big Five inventory → trait-vs-state; Asch line task → conformity in a fake-conversation; Loftus misinformation → in-context "memory" distortion; CBT session → Wampold's common factors). The probes converge across chapters, so the integration in Ch 16 has consilience to work with.

Methodological commitments baked in across all 16: name where the metaphor holds, name where it breaks, refuse poetic equivocation, prefer falsifiable predictions over interpretive moves. Chapter 1's "project charter" prompt forces this discipline upfront. Chapter 15's note explicitly forbids diagnosing Claude (category error); Chapter 16's CBT probe explicitly forbids actual mental-health crisis content (safety).

Each block follows the required template: project name, what-you're-building, tool recommendation, copy-paste-ready prompt, output description, adaptation notes for ChatGPT/Gemini/Claude Code/Claude Project, connection backward, preview forward.

Tool recommendations across the 16: 9 Claude.ai chat, 4 with Claude Code as the right scale-up tool (the quantitative probes — primacy/recency, anchoring, Big Five reliability, conformity rate), every probe paired with a Claude Project for the running report, Cowork recommended at Ch 16 for final integration.

Each block appended to the bottom of its chapter file. Total addition: ~12,000 words of new content across the 16 chapters.

**Known follow-up for review:** the project's most uncomfortable findings — that Claude's behavior under repeated negative feedback degrades in ways consistent with RLHF-trained agreeableness — are stated explicitly in the Ch 14 prompt. If the book is positioned more cautiously than that, the Ch 14 block needs softening. Reviewer's call.
