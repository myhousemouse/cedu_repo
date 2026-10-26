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

## 2. Portfolio roles

| Property or service | Current observed role | Primary audience / job | Evidence | Confidence |
| --- | --- | --- | --- | --- |
| `cedugroup.com` | Corporate and business-portfolio hub | Partners, applicants, press, and people evaluating the company | Current navigation covers company, businesses, brands, newsroom, careers, and inquiries; it names CEDU Book, CEDU Learn, Cheonilmun Study Cafe, and CEDU Culture Center. | High |
| `cedubook.com` | Publishing catalogue, discovery, learning-material, support, and commerce entry | Students, parents, and teachers selecting books or resources | Current navigation separates elementary/middle/high books and materials, smart search, curriculum maps, support, account areas, and VOCA TEST. | High |
| `cedulearn.com` | Online English-learning platform connected to CEDU content | Teachers operating classes and students completing learning | Current metadata describes an online English-learning platform using CEDU content; the corporate site positions it for learners and instructors. Historical records describe teacher campuses, assignments, training/test/review, grading, and reports. | High for role; medium for detailed current features |
| VOCA TEST | Printable vocabulary-test creation attached to CEDU Book | Teachers or learners making tests from CEDU books | Current CEDU Book navigation exposes VOCA TEST and “나의 VOCA TEST.” Historical records describe a free print/download flow. | High for existence; medium for current flow |
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
| Student | Select a book, access linked practice, complete learning, and know what to review | Current book segmentation and CEDU Learn positioning; detailed flows historical |
| Teacher / academy instructor | Select content, obtain materials, create tests, assign work, and inspect results | Current teacher resources and VOCA TEST; detailed operations historical |
| Parent | Select or pay for learning and understand progress | Historical under-14 guardian-verification QA; current journey unverified |
| School / academy administrator | Standardize materials and manage classes/accounts | Inferred from historical campus and class-management records |
| CEDU teams | Publish content, operate linked services, support users, and correct errors | Current catalogue/support plus historical QA workflow |

Finding: learner, buyer, and operator are not necessarily the same person.
Recommendations must identify who decides, pays, assigns, learns, and reviews.

## 4. Key journeys and evidence-backed risks

### Discover and select a book

Current path: CEDU Book home → grade-level or smart/curriculum search → book
detail → purchase or learning material. The home also promotes digital benefits
such as P-Voca, “보카플,” and QR-based CEDU Learn questions.

Interpretation: these services can differentiate the book, but eligibility,
free/trial/paid status, account requirements, and the next step need consistent
explanation. Detail-page consistency has not yet been verified.

### Book or QR to digital learning

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
| F-01 | Observed fact | The official sites serve different portfolio layers but use separate architectures and task vocabularies. | Current public navigation; high | Cross-service tasks may lack a clear starting point. |
| F-02 | Interpretation | Books connect discovery, QR access, vocabulary practice, printable tests, and CEDU Learn. | Current promotions plus historical service map; high | Clear eligibility and next-step messaging can improve activation and trust. |
| F-03 | Historical fact | QR/app entry, identity conversion, entitlement, and record persistence produced multiple QA issues. | Vault QA rows 20, 23, 27, 63; high for snapshot, current status unknown | Failure near first use can erase trust before content value is experienced. |
| F-04 | Historical fact | Resume, progress, and result states produced inconsistencies. | Vault QA rows 5, 17, 34, 58; high for snapshot, current status unknown | Learners may not know what is saved, complete, or next. |
| F-05 | Observed fact | CEDU Book has strong discovery utilities: grade catalogues, smart search, curriculum maps, materials, and support. | Current CEDU Book; high | Valuable acquisition and support asset to preserve. |
| F-06 | Historical fact | Digital concepts use structured repetition: Day progress, word relationships, tests, and error review. | Vault service map and week-1 analysis; medium | Differentiation can come from curriculum depth and book continuity. |

## 6. UI/UX comparative evidence from UI Bowl

CEDU serves book-linked learners, minors, teachers, and purchasers. Consumer
language-app patterns cannot be copied without testing content density,
safeguarding, entitlement, and teacher-assigned flows.

### Learning home and next action

- [Plang](https://uibowl.io/name/%ED%94%8C%EB%9E%AD?patterns=%EB%A9%94%EC%9D%B8&patternName=%ED%95%99%EC%8A%B5%20%EC%A0%84) — the observed pre-learning home centers one “start today’s learning” action while keeping streak and report destinations visible. It demonstrates answering “what should I do now?” before exposing all features.
- [Langflix](https://uibowl.io/name/%EB%9E%AD%ED%94%8C%EB%A6%AD%EC%8A%A4?patterns=%EB%A9%94%EC%9D%B8&patternName=1.%EC%BD%94%EC%8A%A4) — the observed home combines review percentage, streak, course progress, and one start action. It supports colocating status and resumption.
- [Teumteumit](https://uibowl.io/name/%ED%8B%88%ED%8B%88%EC%9E%87?patterns=%EB%A9%94%EC%9D%B8&patternName=%ED%99%88) — the observed home uses one daily knowledge card and compact navigation, demonstrating progressive disclosure for a short daily job.

Proposed CEDU application: after QR/app entry, show recognized book and Day,
saved/entitled state, one next learning/review action, and a recoverable
change-book action. Unlike the references, CEDU must also explain ownership,
trial/payment boundaries, and whether guest activity will persist.

### Onboarding and activation

- [Plang](https://uibowl.io/name/%ED%94%8C%EB%9E%AD?patterns=%EC%98%A8%EB%B3%B4%EB%94%A9) — the observed nine-screen flow starts with a lightweight welcome, then uses explicit choices, progress indication, and completion feedback.
- [Teumteumit](https://uibowl.io/name/%ED%8B%88%ED%8B%88%EC%9E%87?patterns=%EC%98%A8%EB%B3%B4%EB%94%A9) — the observed 1-of-5 step previews the workload and makes selectable learning volume concrete.
- [Langflix](https://uibowl.io/name/%EB%9E%AD%ED%94%8C%EB%A6%AD%EC%8A%A4?patterns=%EC%98%A8%EB%B3%B4%EB%94%A9) — the observed first screen states the content value before asking the user to begin or sign in.

Proposed CEDU application: make QR activation a state-confirmation flow, not a
generic tour: recognized book → free/paid and sign-in implications → saved-
learning choice → ready state. Historical guest-to-member and wrong-book issues
make confirmation and recovery more important than early personalization.

### Results, review, and progress

- [Santa](https://uibowl.io/name/%EC%82%B0%ED%83%80?patterns=%ED%95%99%EC%8A%B5%ED%95%98%EA%B8%B0&patternName=%ED%95%99%EC%8A%B5%20%EA%B2%B0%EA%B3%BC%20%EB%B3%B5%EC%8A%B5) — the observed review retains answer context and offers optional AI explanation. Review is an action on a mistake, not only a score.
- [Teumteumit](https://uibowl.io/name/%ED%8B%88%ED%8B%88%EC%9E%87?patterns=%ED%86%B5%EA%B3%84%C2%B7%EB%A6%AC%ED%8F%AC%ED%8A%B8&patternName=%EB%82%A0%EC%A7%9C%EB%B3%84%20%EC%8A%A4%ED%83%AC%ED%94%84) — the observed calendar turns repeated activity into a simple date-based history.
- [Semo](https://uibowl.io/name/%EC%84%B8%EB%AA%A8?patterns=%ED%86%B5%EA%B3%84%C2%B7%EB%A6%AC%ED%8F%AC%ED%8A%B8&patternName=%EA%B7%B8%EB%9E%98%ED%94%84) — the observed report explains that analysis begins after a test, treating “not enough data” as a designed state.
- [Plang](https://uibowl.io/name/%ED%94%8C%EB%9E%AD?patterns=%ED%86%B5%EA%B3%84%C2%B7%EB%A6%AC%ED%8F%AC%ED%8A%B8&patternName=%EB%A0%88%EB%B2%A8%ED%85%8C%EC%8A%A4%ED%8A%B8%20%EA%B2%B0%EA%B3%BC%EB%A6%AC%ED%8F%AC%ED%8A%B8) — the observed report gives an outcome, interpretable skill range, and confirmation action rather than raw metrics alone.

Proposed CEDU application: define one source of truth for Day completion, score,
incorrect-answer count, review state, and book progress. Results should explain
the outcome, offer the next review action, and show whether progress was saved.
Empty, interrupted, offline, and partially synced states need recovery actions.

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
| 1 | Own book/QR activation, identity, entitlement, and saved-state continuity as one journey | F-02, F-03; onboarding references | Fewer first-use dead ends and clearer trust | Test guest, member, minor, wrong-book, trial/expired, app/web, and offline cases |
| 2 | Create a consistent learning-state model and recovery UX | F-04; home/result/report references | Learners can resume and understand completion and next action | Reconcile state definitions; test interrupted and partially synced sessions |
| 3 | Clarify portfolio wayfinding and cross-service handoffs | F-01, F-02 | Users know whether to use CEDU Book, Learn, VOCA TEST, or a linked tool | Inventory entries/exits and test top tasks by actor |
| 4 | Turn results into targeted review rather than a terminal score | F-04, F-06; Santa/report references | Stronger learning loop and clearer digital value | Define pedagogical rules and test comprehension |
| 5 | Give teachers and parents role-appropriate progress explanations | Actor map; F-06 | Better decisions without unnecessary detail | Confirm priorities, privacy, and minor-account constraints |

## 9. Next research actions

1. Inventory book detail, material, VOCA TEST, QR, sign-in, pricing, support,
   and cross-domain transitions at URL level.
2. Execute top journeys with authorized test accounts on mobile web and app,
   recording guest/member/minor and free/paid state changes.
3. Verify current status of historical QA risks.
4. Observe at least one student, teacher, and purchaser/parent.
5. Convert opportunities into requirements only after that validation.
