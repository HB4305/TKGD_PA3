# PA3 Report — Requirement 3: Peer Review
## Freestyle Chess Mobile Web — Group 06

**Course:** CSC13112 - UI/UX Design  
**Lecturer:** Dr. Le Khanh Duy  
**Teaching Assistant / Instructor:** MSc. Pham Nguyen Son Tung  
**Assignment:** Project Assignment 3 (PA3) — Paper Prototype & Formative Testing  
**Product Scope:** Freestyle Chess Mobile Website on Smartphone Browser  
**Document Purpose:** Record lecture presentation feedback, lecturer critique, peer questions, group responses, and revision actions following the PA3 Peer Review session.

---

## 1. Presentation Record

| Field | Details |
| :--- | :--- |
| **Presentation Date & Time** | August 22, 2026 · During lecture session |
| **Group / Presenters** | **Group 06** — 5 Presenters (Lê Mai Hoai Bảo, Trương Công Thiên Phú, Lâm Hữu Khánh, Phạm Chí Bảo Ninh, Phùng Ngọc Tuấn) |
| **Presentation Duration** | ~10 minutes (5 members × ~2 minutes per section) |
| **Presented Materials** | - Interactive Swiss Modern Presentation Slide Deck (`PA3_presentation.html`)<br>- Speaker Narration Script (`PA3_script.md`)<br>- Hand-drawn Paper Prototypes (6 variants for Navigation & Schedule)<br>- Physical Paper Phone Case simulator & cutting overlays<br>- Formative Testing Plan & Qualitative Evaluation findings (`PA3_Formative_Testing_vn.md`)<br>- Prototype Demonstration Videos in Google Drive: [https://drive.google.com/drive/folders/1YdE95hFgk1xwMHTducJXECs5c1NQ5tfX?usp=drive_link](https://drive.google.com/drive/folders/1YdE95hFgk1xwMHTducJXECs5c1NQ5tfX?usp=drive_link) |
| **Meeting / Session Mode** | On-campus lecture presentation & live demonstration |

---

## 2. Feedback, Questions and Group Responses

The table below documents the feedback received from the Course Instructor (Lecturer), along with Group 06's detailed responses and corresponding revision actions:

| No. | Commenter Name | Role / Group | Feedback Or Question | Group Response | Revision Action Taken | Status |
| :---: | :--- | :---: | :--- | :--- | :--- | :---: |
| **1** | **Lecturer** | Course Instructor | **Slide 14 Visual Enhancement:**<br>"On Slide 14 (*Testing Procedure & Roles*), the team should incorporate actual photographs of the user testing / interview sessions to provide a more intuitive, authentic visual context and eliminate excessive empty space on the slide." | **Strongly Agreed.**<br>The team acknowledged that Slide 14 previously relied solely on text role cards (Facilitator, Mobile, Observer) and statistic counters, leaving considerable whitespace. Adding authentic photos of the live testing sessions—showing the participant holding the paper phone case, the facilitator reading scenarios, and the 'Computer' operator manipulating paper overlays—substantially boosts visual credibility, realism, and aesthetic balance. | - Restructured Slide 14 in `PA3_presentation.html` to integrate high-resolution testing session photos alongside role cards.<br>- Updated `PA3_script.md` for Presenter 4 to reference the displayed session images during narration.<br>- Embedded testing photo documentation into `PA3_Formative_Testing_vn.md`. | **Done** |
| **2** | **Lecturer** | Course Instructor | **Back Navigation Buttons:**<br>"The prototype should include dedicated 'Back' buttons on the screens (especially on nested detail screens such as Event Detail and Match Detail) so users have clear, visible controls to return to previous states and navigate backward easily." | **Strongly Agreed.**<br>The group recognized that while the paper prototype allowed users to navigate forward into detail screens (`event.JPG` and `match.JPG`), returning to previous overview screens relied heavily on bottom navigation tabs or browser back gestures. Providing explicit, high-visibility 'Back' buttons (`< Back` / Back chevron in the top app bar and sticky return headers) directly adheres to *Jakob Nielsen's Heuristic #3: User Control and Freedom* by ensuring an obvious 'emergency exit'. | - Added explicit Back button specifications to `PA3_Task_Workflow_Specification.md` for all sub-screen user flows.<br>- Documented Back button requirements in the *Points of Improvement* section of `PA3_Formative_Testing_vn.md`.<br>- Formally scheduled prominent top-left `< Back` buttons and modal close triggers for all detail screens in the PA4 Hi-fi Figma backlog. | **Done** |

---

## 3. Detailed Revision Summary & Artifact Changes

Following the feedback received during the Peer Review session, Group 06 performed the following systematic revisions across project artifacts:

| Document / Artifact | Section / Element | Before Revision | After Revision | Motivation & Rationale |
| :--- | :--- | :--- | :--- | :--- |
| **`PA3_presentation.html`** | Slide 14 (`Testing Procedure & Roles`) | Layout contained only 3 text-based role cards and 4 numerical stat boxes; significant unused whitespace. | Redesigned layout with a 2-column visual grid: Left column features interactive role cards and stats; Right column embeds authentic testing session photo gallery illustrating participant interaction with the paper phone case. | Directly satisfies the Lecturer's critique to make Slide 14 visually intuitive, tangible, and aesthetically balanced. |
| **`PA3_script.md`** | Slide 14 Narration (Presenter 4) | Script only recited the definition of the 3 roles and numerical stats. | Added narration directing the audience's attention to the testing session photos on the slide (*"As shown in the photos from our testing sessions..."*). | Synchronizes spoken narrative with updated visual slide elements. |
| **`PA3_Task_Workflow_Specification.md`** | Section II & Section III (Detail Flows) | User flows only described forward navigation into Event and Match details without explicit Back button steps. | Added explicit `Back Button (`< Back`)` return flows for all detail screens, allowing users to return directly to the exact previous scroll position on Schedule. | Ensures user control, navigability, and clear reverse interaction paths. |
| **`PA3_Formative_Testing_vn.md`** | Section 11 (Points of Improvement) | Improvement list focused mainly on font sizes and quick filter chips. | Added Item 4: *"Design explicit, accessible Back buttons on top-left of all detail screens with minimum 44×44px touch target"* as a mandatory requirement for PA4. | Translates review feedback into concrete design requirements for the next project phase. |
| **`06-PA3-WeeklyReport.md`** | Section 7.2 & Section 9 | Retrospective and improvement lists did not explicitly list the Back button and Slide 14 visual updates. | Updated Formative Testing outcomes and Retrospective action items to include Slide 14 imagery integration and Back navigation implementation. | Maintains end-to-end traceability across all Scrum documentation. |

---

## 4. Action Plan & Roadmap for PA4 (Hi-fi Prototype)

Based on the feedback documented above, Group 06 commits to the following actionable items in Sprint 4 (PA4):

1. **Explicit Navigation & Back Controls:**
   * Implement a standardized top app bar component with a high-contrast `< Back` chevron button (touch target ≥ 48×48px) on all second-level and third-level screens (`Event Detail`, `Match Detail`, `Player Profile`, `Video Player`).
   * Include breadcrumbs and sticky return headers when users scroll deeply into match stats.
2. **Comprehensive Visual Documentation:**
   * Maintain high visual standards by capturing photos and video recordings of all subsequent user testing sessions in PA4 (Summative Usability Study).
   * Incorporate real participant testing footage and screen recordings directly into the PA4 final presentation and demo video.
3. **Seamless Integration of Winning Variants:**
   * Combine `Nav-1: Fixed Bottom Navigation Bar` and `Sch-3: Date Strip + Match Detail` into a cohesive Figma component library with auto-layout, interactive hover/tap states, and dark/light mode tokens.

---

## 5. Final Note & Sign-off

All feedback and recommendations provided by the Course Instructor (Lecturer) during the lecture presentation have been thoroughly analyzed, documented, and integrated into the project specifications. The revisions ensure that the project deliverables are robust, user-centered, and fully prepared for the upcoming High-Fidelity Prototyping phase (PA4).

*Report compiled and verified by Group 06 on August 22, 2026.*

**Team Members:**
- Lê Mai Hoài Bảo (Product Owner) — *Signed*
- Lâm Hữu Khánh (Scrum Master) — *Signed*
- Phạm Chí Bảo Ninh (Paper Prototype Lead) — *Signed*
- Trương Công Thiên Phú (UX Researcher) — *Signed*
- Phung Ngoc Tuan (Testing Lead) — *Signed*
