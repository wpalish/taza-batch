---
name: TazaBatch
description: An inherited working cabinet for synthetic fixed-column batches, ordered before/after evidence and explicit whole-dataset imports.
colors:
  primary: "#126653"
  primary-hover: "#0b5343"
  navy: "#183e60"
  ink: "#172e45"
  page: "#edf3f8"
  surface: "#ffffff"
  line: "#b9cbd9"
  navigation-surface: "#dce9f3"
  muted: "#46627a"
  input-stroke: "#7894aa"
  link: "#174e7e"
  pending: "#795200"
  error: "#942721"
  error-surface: "#fff0ee"
  focus: "#bd671a"
  selection-surface: "#b7ded2"
  selection-ink: "#132f29"
typography:
  primary-heading:
    fontFamily: 'system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif'
    fontSize: "2rem"
    lineHeight: 1.15
    letterSpacing: "-0.025em"
  section-heading:
    fontSize: "1.3rem"
  brand:
    fontSize: "1.4rem"
    fontWeight: 740
  body:
    fontFamily: 'system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif'
  label:
    fontWeight: 600
  supporting:
    fontSize: "0.9rem"
  exact-json:
    fontSize: "0.85rem"
rounded:
  control: "7px"
  panel: "12px"
spacing:
  evidence-gap: "0.4rem"
  inline-gap: "0.5rem"
  action-gap: "0.6rem"
  control-inset: "0.7rem"
  unit: "1rem"
  page-inline: "1.25rem"
  panel-inset: "1.4rem"
  section: "2rem"
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.surface}"
    rounded: "{rounded.control}"
    padding: "0.65rem 1rem"
  button-primary-hover:
    backgroundColor: "{colors.primary-hover}"
  button-secondary:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.navy}"
    rounded: "{rounded.control}"
    padding: "0.65rem 1rem"
  button-default:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.surface}"
    rounded: "{rounded.control}"
    padding: "0.65rem 1rem"
  field:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    rounded: "{rounded.control}"
    padding: "{spacing.control-inset}"
    width: "100%"
  panel:
    backgroundColor: "{colors.surface}"
    rounded: "{rounded.panel}"
    padding: "{spacing.panel-inset}"
  navigation-current:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.navy}"
    rounded: "{rounded.control}"
    padding: "0.65rem 1rem"
  exact-chain-disclosure:
    padding: "0.7rem 0"
  stage-disclosure:
    padding: "0.7rem 0"
---

# Design System: TazaBatch

## Overview

**Creative North Star: "The Shared Work Cabinet"**

TazaBatch extends the documented QuralGate Shared Work Cabinet. It keeps the navy identity and navigation, pale blue workspace, white labelled forms, green explicit actions, system typography, and native controls. The incumbent system remains the visual authority for this original bounded synthetic batch-cleaning workspace.

Its character is direct, flat, and readable. Published version, run author and current state lead; the saved run outcome, exact final output, ordered before/after evidence and explicit local import remain distinct. The signature is a first failed stage with zero output, alongside a successful whole-package result that its original author can import once.

**Key Characteristics:**

- Inherited navy navigation and pale blue workspace.
- Green labelled submit actions and white bordered native forms.
- System typography with a fixed-size task heading.
- Current local-dataset status separated from the saved run outcome.
- Exact input, final output and native ordered before/after disclosures.
- First failed stage, later-stage stop statement and zero-output boundary together.
- Wrapping authored RU/KK text, timestamps and publication digests; exact saved step positions.

## Colors

The cool inherited palette uses navy for orientation and Working Green for explicit actions. The frontmatter owns implemented values. Sidecar tonal strips are inherited derived inspection metadata, not additional interface colors.

### Primary

- **Working Green** (`primary`, `primary-hover`): native submits and explicitly primary actions, including publication, saving the synthetic run report and importing the whole package. The retained status utility shares this green; current outcome headings themselves are explicit text.

### Secondary

- **Cabinet Navy** (`navy`): header, baseline filled buttons, navigation text and secondary-control borders.
- **Link Blue** (`link`): links and field carets.

### Tertiary

- **Pending Amber** (`pending`): retained inherited pending utility; outcome headings do not rely on it.
- **Error Red / Pale Error** (`error`, `error-surface`): refused-action notices; saved stage diagnostics remain readable text on the page ground.
- **Focus Amber** (`focus`): visible keyboard focus.
- **Soft Selection Green / Selection Ink** (`selection-surface`, `selection-ink`): native text selection.

### Neutral

- **Cabinet Ink** (`ink`): root text and outcome headings.
- **Cool Workspace** (`page`): page ground and scrollbar track.
- **White Surface** (`surface`): native fields, form panels, ordinary notices and current navigation.
- **Divider Blue** (`line`): containers, tables and evidence dividers.
- **Navigation Mist** (`navigation-surface`): navigation strip and table headings.
- **Supporting Slate** (`muted`): boundary statements, helper copy, digest and footer.
- **Field Slate** (`input-stroke`): field borders and scrollbar thumb.

**The Inherited Shell Rule.** Extend the current QuralGate cabinet instead of replacing its palette, typography, or navigation grammar.

## Typography

The recorded system stack serves task headings, body and controls. No webfont is loaded. A fixed-size main heading, smaller section headings and heavier brand establish hierarchy. Unspecified body size, heading weights and line heights retain browser defaults. Exact JSON uses the browser's native preformatted face at the recorded smaller size; it is not a separate display identity.

Paragraphs have maximum measure (72ch) and line height (1.6). Labels and buttons use weight (600). Authored descriptions preserve line breaks through `white-space: pre-wrap`; JSON also preserves whitespace and wraps anywhere. Tables retain tabular numerals. Status is a written heading, and the saved run gets its own named evidence section.

The document uses `lang="ru"`. Pipeline description editors mark `descriptionRu` and `descriptionKk` as `ru` and `kk`. `pipelineView` and `runDetail` render each authored description in a separate paragraph with its respective language attribute. Operation names, row/field diagnostics and other controls remain Russian interface text. Authored content is neither language-detected nor translated.

**The Authored Language Rule.** Keep authored RU/KK descriptions in their own language nodes; labels, operation names, diagnostics and status copy remain Russian interface text.

## Layout

Header and navigation share inline padding (`max(1.25rem, calc((100% - 1160px) / 2))`). Main is centered with maximum width (1200px), padding (`2rem 1.25rem`) and minimum height (75vh). Header uses a spaced flex row; navigation has the recorded inline gap. The retained optional work grid uses columns (`minmax(0, 1fr) minmax(260px, 0.8fr)`); paired rows use equal columns. TazaBatch run detail follows a vertical reading order, with white panels for available forms.

At the stacked breakpoint (700px and below), retained grids stack, main padding becomes (`1.4rem 1rem`), panel padding becomes (1rem), and navigation wraps with padding (0.6rem). Header identity aligns to the top with size (0.8rem) and maximum width (140px). At the narrow table/search breakpoint (600px and below), search tools stack, navigation buttons use `flex: auto`, and table cells receive minimum width (140px). A focusable labelled table wrapper owns horizontal scrolling and has a narrow-screen hint.

Action rows wrap. Headings, identity, evidence, disclosures and footer allow long text to wrap. Direct screen paragraphs and diagnostic list items explicitly wrap anywhere; preformatted JSON does too. Evidence has a top divider, unit top margin/padding and the recorded evidence gap. The exact final output precedes the available owner-import form. The refresh action and original JSON then precede ordered stage disclosures and the exact published-chain disclosure; the publication digest and synthetic boundary follow it.

The supplied seven-file packet is enumerated in [finish-review.json](docs/finish-review.json): imported v8 result at 1440, 1280 and 390px; rejected v11 result at 1440 and 390px; ready v11 owner-import form before submission at 1440 and 390px. The reviewer independently opened all seven images and recorded `ship` with no material fixes. [Capture provenance](docs/capture-provenance.json) maps them to seven own synthetic shipping JPEG aliases with `.jpg` filenames. The original `.impeccable/review/*.png` source filenames contain JPEG/JFIF bytes; each shipping alias preserves those bytes exactly. This scan documentation uses that supplied review and current frontend source; it did not rerun context, detector, browser or interaction checks. The verdict does not establish every form/state/width, full mobile or touch coverage, a screen-reader audit, backend correctness, security, real-data suitability or a delivered service outcome.

## Elevation & Depth

No box shadow, backdrop effect, transition or animation is defined. White panels, pale fills, one-pixel borders and whitespace separate regions. Hover changes brightness and primary fill without motion. Replacing screen content and focusing a task or preview heading provides continuity without animation. No decorative raster is used. The screenshots are evidence assets with origin, supplied state and shipping aliases recorded in [capture-provenance.json](docs/capture-provenance.json); their independent review is recorded in [finish-review.json](docs/finish-review.json).

## Shapes

Controls and notices use the smaller recorded radius; panels and table wrappers use the larger one. Borders are one pixel. Textareas start at height (100px) and resize vertically. Buttons and native disclosure summaries have minimum height (44px). Native disclosure markers remain visible. The published chain uses an ordinary ordered list with padding (1.5rem); each item receives its saved `position` through `li.value`, so positions are not silently renumbered. Retained fieldset styles do not define the run-detail composition.

## Components

### Buttons

Native labelled actions use padding (`0.65rem 1rem`) and recorded label weight. Explicit primary and all submit buttons use Working Green with white text; hover combines the deeper primary fill with brightness (1.13). Secondary refresh, return, archive and settings actions use white with navy text and border. The retained baseline button rule is navy filled. Disabled buttons use opacity (0.55) and `cursor: not-allowed`. Focus-visible is an amber outline (3px) with offset (3px); narrow buttons have maximum width (100%). The initiating button is disabled while its request runs.

### Cards / Containers

Flat white form panels use a Divider Blue border, the panel radius and recorded inset, reduced at the stacked breakpoint. Login is capped at width (480px). Run metadata, saved report, exact JSON, stage traces and exact chain stay on the page ground. Preview evidence follows its form rather than opening a modal or a second workspace.

### Inputs / Fields

Native inputs, selects and textareas use White Surface, Cabinet Ink, Field Slate borders and Link Blue carets. Every generated field has a connected label and ID. Archived or role-protected editors retain values through native read-only fields or disabled selectors. Integer editors use native number inputs with step (1) and source-supplied `min`/`max`; configured length bounds use `maxLength`.

Pipeline description editors carry explicit RU/KK language attributes. The synthetic input uses a required labelled textarea with spellcheck disabled and maximum length (50000). The owner import reason is a separate required textarea. Failed requests retain the form and focus the shared polite status notice. These are source-supported semantics, not interaction tests rerun by this documentation pass.

### Navigation and Notices

The linked brand and current user/role lead the navy header. Inactive section controls are transparent on the pale strip; the current collection is white bordered with `aria-current="page"`. The initial collection is runs (`runs`). The skip link becomes visible on focus. Task/detail changes focus the leading heading using `tabindex="-1"`; successful previews focus their result heading. The shared notice has `role="status"`, `aria-live="polite"` and a programmatic focus target. Empty notices are hidden. Refused-action notices use Pale Error and Error Red; normal notices use White Surface.

### Publication and Synthetic Run Preview

Publication preview uses a labelled chain selector and **Проверить цепочку**, then displays code/version, title, both authored descriptions, ordered operations and the fixed-column input boundary. **Опубликовать эту версию** follows that evidence. Selector changes clear the preview and a generation guard ignores obsolete responses.

The run form uses a labelled publication selector, **Синтетические строки JSON** and **Проверить весь пакет**. Preview shows the frozen publication identity, full report, **Сохранить этот отчёт** and ordered stage evidence. Editing the publication or JSON clears the old preview; the generation guard prevents an obsolete response being presented as current. Saving a report states that no local import has occurred yet.

### Current State and Saved Run Outcome

Run detail leads with code, saved version, original author, server timestamp and current state: **Локальный набор сохранён**, **Готов к локальному импорту** or **Пакет остановлен**. Both exact authored descriptions follow. A divided evidence section explicitly titled **Результат сохранённого прогона** then renders the persisted run outcome. A previously successful run continues to say **Все стадии пройдены** after its current state becomes imported; those are two distinct facts.

Successful saved evidence shows input row count, executed-stage count, whole-package statement, total qty and **Точный выходной пакет** in a `pre`. Existing dataset metadata adds importer, time, reason and **Открыть локальный набор**. The imported v8 captures show two exact output rows with numeric qty 2 and 3. The ready-form captures remain before import submission, so neither a visible form nor its draft reason establishes an import.

**The Saved Run Rule.** Show current imported, ready or rejected status first; label the saved run outcome separately so a successful historical run does not impersonate a pending import.

### First Failure and Native Before/After Evidence

Rejected reports name the first failed step and operation, state **Более поздние шаги не выполнялись.**, list every reported row/field error and say **Выходной набор пуст. Частичного импорта нет.** Input-parse refusals instead state that no steps ran. Error names cover JSON length/syntax, row count, flat objects, exact columns, string/cell requirements, repeated decoded keys, blanks, canonical qty and duplicate final code.

**Упорядоченный отчёт шагов** contains a real `details`/`summary` for each executed trace entry. Its summary keeps the actual saved position, operation and **Пройден** or **Остановлен**. **До шага** and **После шага** show exact serialized before/after arrays in separate `pre` elements; any step errors follow. Disclosures are closed by default in source. Later unexecuted stages are not fabricated.

In the rejected v11 captures, step 6 rejects row 1 qty while the trace's after array contains row 2 converted to numeric qty 3. That partial trace remains inspectable evidence; the separate failed-report wording still establishes zero final output. The imported v8 capture expands step 6 to show string quantities becoming numbers.

**The Stop Boundary Rule.** Keep the first failed stage, row or field error, later-stage stop statement and empty-output statement together; partial after-step evidence is never the final output.

### Explicit Owner Import

A ready, unarchived report with no existing dataset renders **Явный импорт всего пакета** only when the current user's name matches the run owner. It states the whole output row count and local synthetic boundary, requires **Основание локального импорта**, then offers **Импортировать весь пакет один раз**. The form follows exact final output and precedes ordered trace evidence. Other users receive the owner-only explanation, including that an administrator cannot bypass it. These are UI source conditions, not an independent authorization test.

A completed import shows its saved importer, time, reason and dataset action instead of the form. Dataset detail shows row count, total qty, reason, exact saved rows, source-report digest and a return link. Its boundary copy states that archive does not cancel the dataset or allow another import; matching code across separate datasets is allowed. This visual documentation does not independently test persistence or import concurrency.

**The Explicit Import Rule.** Keep the original owner’s required reason and one-time whole-package import action after the exact final output; another administrator does not replace that author.

### Exact Published Chain

**Точная опубликованная цепочка** is a native disclosure following the trace. It displays the saved code/version, title, authored RU/KK descriptions, ordered operations and fixed-column boundary. Each ordered-list item retains its actual position, including any gaps, through `li.value`. The publication SHA256 follows outside it. The digest is inspectable evidence, not a signature or security guarantee.

**The Exact Chain Rule.** Preserve saved publication identity and actual step positions in native disclosures; later draft edits must not visually replace the frozen chain.

### Tables and Data Disclosure

Native record tables use collapsed borders, left/top aligned cells, padding (0.9rem), wrapping values, maximum cell width (28ch) and pale headings. Headers have column scope; each row has a labelled open action. The last row removes its bottom divider. Search and the archive checkbox retain native labels; an empty result has explanatory text. Run list cells derive the current imported label separately from saved report status.

The inherited data/access surface uses native account fields, labelled download/journal actions, a native recent-event disclosure and a file input followed by an explicit restore-confirmation panel. Its copy states the shared workspace and unsigned-copy boundary. Those source-visible controls do not establish account recovery, tenant isolation, security certification or a complete settings review. Synthetic-only and external-operation boundaries remain visible in the list, run, dataset and footer.

The source of this scan is [app.js](public/app.js), [styles.css](public/styles.css) and [index.html](public/index.html), with product truth in [PRODUCT.md](PRODUCT.md), the six-block surface direction in [public-app-js.md](.impeccable/surfaces/public-app-js.md), and inherited visual authority in [QuralGate DESIGN.md](../qural-gate/DESIGN.md). [.impeccable/design.json](.impeccable/design.json) contains ten self-contained static visual examples, extension metadata and this document's narrative; the examples have no application handlers or backend execution.

## Do's and Don'ts

### Do:

- **Do** inherit the navy header, pale workspace, white form surfaces and green primary action.
- **Do** keep connected labels, native controls, native disclosure markers and visible focus.
- **Do** preserve authored RU/KK descriptions within Russian interface copy.
- **Do** distinguish current local-dataset status from the saved run outcome.
- **Do** show exact raw input, exact final output, actual step positions and before/after evidence.
- **Do** keep first-failure errors, later-stage stop and zero-output wording together.
- **Do** keep the required owner reason and whole-package import action after the final output.
- **Do** allow long descriptions, timestamps, exact JSON and SHA256 digests to wrap.

### Don't:

- **Don't** replace the inherited cabinet with a new visual identity, ornamental assets or animation.
- **Don't** hide field labels or replace native disclosure controls with a decorative imitation.
- **Don't** present a partially transformed failed-stage trace as an output or partial import.
- **Don't** substitute current drafts for the saved publication, report or exact step positions.
- **Don't** present a ready report or filled import reason as proof that a dataset was imported.
- **Don't** imply an n8n integration, connector, real-data suitability, external write or delivered service outcome.
- **Don't** present the displayed SHA256 digest as a signature or security certification.
