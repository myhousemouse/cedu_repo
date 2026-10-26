# Existing service analysis

Status: Baseline v1 completed; authenticated journeys remain to be researched

Last checked: 2026-10-26 (KST)

## 1. Scope, sources, and limitations

- Current official sources: [CEDU Group](https://cedugroup.com/),
  [CEDU Book](https://www.cedubook.com/), and
  [CEDU Learn](https://cedulearn.com/), checked 2026-10-26.
- Historical first-party context: the user-supplied vault under
  `/workspace/experience/Cedu-ServicePlanning-Obsidian-Vault`, especially
  `99_Sources/쎄듀 서비스 정리 원문.md`,
  `01_Program/쎄듀 QA 업무 기준 및 서비스 구분.md`, and
  `02_Work-Logs/쎄듀 QA 발견사항 및 개인 담당 기록.md`.
- Comparative UI source: UI Bowl, checked 2026-10-26. Its released-product
  screens are pattern references, not evidence that the same design will work
  for CEDU.

Only public, unauthenticated pages were reviewed. CEDU Learn is a JavaScript
application; public metadata confirmed its positioning, but its rendered and
authenticated journeys were unavailable in the current browser surface.
Detailed features therefore use the dated vault and are labeled historical.
Apps, app stores, social channels, analytics, VOC, and pricing were not
comprehensively inventoried.

### Confirmed analysis focus

The primary service is **VOCA TEST**, not the full CEDU portfolio and not VOCA
TEST Play / 보카플.

- Primary user: teacher
- Job to be done: use vocabulary from CEDU books to create test content for
  students
- Product type: teacher-facing learning-content authoring tool
- Core authoring object: a printable or downloadable vocabulary test
- Adjacent but distinct service: VOCA TEST Play / 보카플, where students learn
  and review vocabulary digitally

The portfolio material below is retained only to explain entry, content, and
account context. Improvement analysis must be based on the teacher's VOCA TEST
authoring workflow.

## 2. Portfolio roles

| Property or service | Current observed role | Primary audience / job | Evidence | Confidence |
| --- | --- | --- | --- | --- |
| `cedugroup.com` | Corporate and business-portfolio hub | Partners, applicants, press, and people evaluating the company | Current navigation covers company, businesses, brands, newsroom, careers, and inquiries; it names CEDU Book, CEDU Learn, Cheonilmun Study Cafe, and CEDU Culture Center. | High |
| `cedubook.com` | Publishing catalogue, discovery, learning-material, support, and commerce entry | Students, parents, and teachers selecting books or resources | Current navigation separates elementary/middle/high books and materials, smart search, curriculum maps, support, account areas, and VOCA TEST. | High |
| `cedulearn.com` | Online English-learning platform connected to CEDU content | Teachers operating classes and students completing learning | Current metadata describes an online English-learning platform using CEDU content; the corporate site positions it for learners and instructors. Historical records describe teacher campuses, assignments, training/test/review, grading, and reports. | High for role; medium for detailed current features |
| VOCA TEST | Teacher-facing vocabulary-test authoring attached to CEDU Book | Teachers creating student tests from words in CEDU books | Current CEDU Book navigation exposes VOCA TEST and “나의 VOCA TEST.” Historical records describe book setup, range/type/count configuration, preview, save, print, and download. | High for purpose; medium for current detailed flow |
| VOCA TEST Play / 보카플 | Book-linked vocabulary learning | Learners practicing synonyms/antonyms through tests and review | Current CEDU Book promotes a book-linked “보카플” function. Historical records describe QR/app entry, Day learning, game tests, incorrect-answer review, and paid continuation. | Medium |
| Middle-school grammar N-je QR exercises | Book-linked, no-login supplementary questions | Book owners wanting extra practice and immediate results | Historical October 2026 records describe total assessment and basic training using QR entry and CEDU Learn question assets. Current flow was not executed. | Medium |

Interpretation: these sites are portfolio layers, not substitutes. The group
site establishes corporate trust; CEDU Book supports content discovery and
ownership; CEDU Learn and book-linked tools extend printed content into
practice, assessment, review, and class operations. The book is both a product
and an acquisition key for digital journeys.

The public sites do not establish whether identity, entitlements, records, and
support are continuous across services. “One connected ecosystem” remains a
hypothesis until transitions are tested.

## 3. Users and stakeholders

| Actor | Goal and role | Evidence status |
| --- | --- | --- |
| Teacher / academy instructor | Select a CEDU book and its words, configure and inspect a test, then save/print/download it for students | Confirmed primary user; current VOCA TEST entry plus historical guide |
| Student | Take the teacher-produced test | Confirmed recipient, not the primary authoring user |
| Parent | Select or pay for learning and understand progress | Historical under-14 guardian-verification QA; current journey unverified |
| School / academy administrator | Standardize materials and manage classes/accounts | Inferred from historical campus and class-management records |
| CEDU teams | Publish content, operate linked services, support users, and correct errors | Current catalogue/support plus historical QA workflow |

Finding: the teacher is the author and the student is the recipient. Analysis
must optimize the teacher's production work without confusing it with the
student-facing learning experience.

## 4. Key journeys and evidence-backed risks

### Discover and select a book

Current path: CEDU Book home → grade-level or smart/curriculum search → book
detail → purchase or learning material. The home also promotes digital benefits
such as P-Voca, “보카플,” and QR-based CEDU Learn questions.

Interpretation: these services can differentiate the book, but eligibility,
free/trial/paid status, account requirements, and the next step need consistent
explanation. Detail-page consistency has not yet been verified.

### VOCA TEST authoring

Historical path: enter VOCA TEST from CEDU Book → add/select a book → choose
units, question types, and item counts → inspect selected words and print
preview → update changes → enter campus/class/teacher/test metadata → save,
download, or print → manage prior tests.

This is a multi-constraint authoring flow. The important UX questions are
whether teachers can see the consequences of each choice, recover from a wrong
selection without losing work, directly adjust generated content, and trust the
final student-facing output. The current authenticated interface must be
observed before any friction is treated as fact.

### Adjacent book or QR learning (out of primary scope)

Historical path: scan QR or enter app/web → select or recognize book → learn or
test → receive results → review errors. The QA snapshot includes app-camera
entry failure, wrong-book data after QR entry, guest-to-member records not
persisting, and book progress not updating after completion. These show one
connected risk across entry, identity, entitlement, and progress; their current
production status is unknown.

### Teacher operation

Historical path: select content → create a printable test or
campus/assignment → distribute → receive grading/progress → provide review or
reports. Current public navigation confirms teacher resources and VOCA TEST,
but the authenticated operational flow remains to be tested.

### Learn, see results, and resume

Historical VOCA TEST Play records describe Day learning, tests, results,
incorrect-answer review, and direct tests. QA records include inability to
resume, contradictory result counts, clipped mobile content, double-advance on
rapid taps, and missing registration error messages. These are dated findings,
not claims about the current production build.

## 5. Findings

| ID | Type | Finding | Evidence / confidence | Likely impact |
| --- | --- | --- | --- | --- |
| F-01 | Confirmed fact | VOCA TEST is a teacher-facing content-authoring tool whose output is a student vocabulary test based on CEDU-book words. | User correction, 2026-10-26; high | Teacher authoring efficiency and output confidence define the analysis. |
| F-02 | Observed fact | CEDU Book exposes VOCA TEST and “나의 VOCA TEST” as account-linked destinations. | Current public navigation; high | Entry, saved work, and reuse are part of the service boundary. |
| F-03 | Historical fact | The documented flow contains several dependent choices: book, unit/range, question type, item count, word review, metadata, and output. | Vault `쎄듀 서비스 정리 원문.md`; medium for current interface | Users need visible scope, reversible choices, and early conflict feedback. |
| F-04 | Historical fact | The tool supports saving, downloading, and printing, and records campus/class/teacher/test names. | Same historical source; medium for current interface | Completion depends on the correctness of both content and physical/digital output. |
| F-05 | Hypothesis | Reusing or adapting an existing test may be a frequent teacher job. | “나의 VOCA TEST” navigation; low until teacher research | Duplication/versioning could remove repetitive setup. |
| F-06 | Research gap | No current authenticated authoring session or teacher observation has been completed. | Current access limitation; high | No current-screen friction should yet be reported as fact. |

## 6. UI/UX comparative evidence from UI Bowl

The relevant comparison is a desktop authoring or configuration tool, not a
student learning app. The references below demonstrate interaction patterns,
not equivalent education workflows.

- [Museby](https://uibowl.io/website/%EB%AE%A4%EC%A6%88%EB%B0%94%EC%9D%B4%20Museby?patterns=%EC%83%9D%EC%84%B1%ED%95%98%EA%B8%B0&imgId=cmttbab590028kz041nq3vokv) — the observed campaign-creation screen uses a visible stepper, keeps the editable form central, and places a live summary/status panel beside it. This supports showing a teacher where they are while preserving the consequences of earlier choices.
- [Mailchimp](https://uibowl.io/website/%EB%A9%94%EC%9D%BC%EC%B9%A8%ED%94%84%20(Mailchimp)?patterns=%EC%83%9D%EC%84%B1%ED%95%98%EA%B8%B0&patternName=%EB%B8%8C%EB%9E%9C%EB%93%9C%20%ED%82%A4%ED%8A%B8) — the observed brand-kit builder groups different outputs into persistent, separately editable cards. This supports treating book/range, question composition, and test metadata as reviewable authoring sections rather than disposable wizard answers.
- [Sabangnet](https://uibowl.io/website/%EC%82%AC%EB%B0%A9%EB%84%B7?patterns=%EC%83%9D%EC%84%B1%ED%95%98%EA%B8%B0&patternName=%EA%B3%A0%EA%B0%9D%20%EB%8C%80%EB%9F%89%20%EB%93%B1%EB%A1%9D) — the observed bulk-registration flow combines a dense table with validation, error states, and confirmation. This demonstrates that high-density work needs row-level feedback and recoverable errors rather than only a final failure message.
- [Kyobo Book Centre](https://uibowl.io/website/%EA%B5%90%EB%B3%B4%EB%AC%B8%EA%B3%A0?patterns=%EC%83%9D%EC%84%B1%ED%95%98%EA%B8%B0&patternName=%EB%A6%AC%EC%8A%A4%ED%8A%B8) — the observed list-creation flow uses an explicit name, a selected-item list, and a completion confirmation. This supports making the authored collection and its save state visible.

Proposed VOCA TEST application: use a staged but reversible builder—book and
range → question composition → word/item review → output preview and metadata →
save/print/download. Keep a persistent summary of selected scope and item count;
validate conflicts where they occur; allow teachers to move backward without
discarding edits. Unlike campaign or commerce tools, VOCA TEST must also
preserve pedagogical balance, answer-key correctness, print layout, and
copyright-bounded CEDU content.

## 7. Strengths to preserve

- Recognized English-learning brands and a broad elementary-to-high catalogue.
- Structured, book-aligned content and reusable question assets.
- Teacher distribution and operations, not only direct-to-consumer learning.
- Multiple print-to-digital bridges for practice, assessment, and review.
- Discovery, learning-material, support, and account surfaces on CEDU Book.
- Historical QA discipline recording conditions, expected/actual behavior,
  evidence, and re-check state.

## 8. Opportunity themes

These are proposals, not accepted product decisions.

| Priority | Opportunity | Evidence | Expected outcome | Validation needed |
| --- | --- | --- | --- | --- |
| 1 | Make the authoring scope and resulting item count continuously visible | Historical authoring flow; Museby | Fewer configuration mistakes and less backtracking | Observe teachers creating short and large tests |
| 2 | Make every generation step reversible without losing valid work | Multi-constraint flow; Mailchimp | Faster iteration and safer experimentation | Verify current save/regenerate behavior |
| 3 | Add item-level review, validation, and selective regeneration/editing | Teacher output-confidence need; Sabangnet | Fewer content and answer-key errors | Confirm which item properties teachers may edit |
| 4 | Treat preview, answer sheet, print/download, and metadata as one output check | Historical flow | Higher confidence before distributing a test | Test common printers, file formats, and long campus/class names |
| 5 | Support finding, duplicating, and adapting prior tests | “나의 VOCA TEST” entry; Kyobo list pattern | Less repeated setup for recurring classes | Measure reuse frequency and versioning needs |

## 9. Next research actions

1. Observe the complete authenticated VOCA TEST teacher flow.
2. Record fields, defaults, constraints, validation, save behavior, and output
   at each authoring step.
3. Ask teachers to create a new test and adapt an old one; measure hesitation,
   backtracking, and manual checking.
4. Verify print/download and answer-sheet output across realistic item counts.
5. Convert opportunities into requirements only after that validation.
