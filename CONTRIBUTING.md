# Contributing Guidelines

This document outlines the standards for transcribing and annotating the journal of Henry Rowe Schoolcraft's 1818‑1819 expedition through the Ozarks.

## Transcription

*   Retain the original spelling, punctuation, and capitalization of the manuscript.
*   Use a plain‑text format (UTF‑8). Do not apply modern spelling corrections.
*   Indicate illegible or damaged text with `[illegible]`.
*   Indicate editorial insertions with square brackets, e.g., `[sic]`.

## Annotation Format

Annotations are placed **inline** within the transcribed text, using the following markup:

*   **Glossary/Definition**: `[Gloss: term]` – define archaic, technical, or obscure terms.
    *   Example: `…a sparkling rock [Gloss: quartz]…`

*   **Geographic/Location**: `[Geo: modern place name]` – identify a modern place name for a historical site, trail, or feature.
    *   Example: `…followed the old trace [Geo: present‑day Missouri Route 19]…`

*   **Archaeological Context**: `[Arch: brief note]` – link a description to known archaeological sites, features, or material culture.
    *   Example: `…found several flint points [Arch: likely Late Woodland projectile points]…`

*   **Historical Context**: `[Hist: brief note]` – provide historical background, e.g., connections to fur‑trade posts, settler movements, or indigenous nations.
    *   Example: `…met a party of hunters [Hist: likely associated with the American Fur Company]…`

*   **Cross‑Reference**: `[Xref: other entry date]` – refer to another journal entry that discusses the same topic.
    *   Example: `…the same ridge mentioned earlier [Xref: 1818‑12‑05]…`

## Workflow

1.  Each journal entry will be tracked in a GitHub issue (e.g., `Task: Transcribe and Annotate Entry for December 10, 1818`).
2.  The issue will include a link to a public‑domain scan of the relevant page(s) and a list of expected annotations.
3.  Contributors should fork the repository, create a branch for the entry, and transcribe/annotate the text in the central `journal_entries.md` file.
4.  Submit a pull request with the new entry, referencing the issue number in the description.
5.  The lead archaeologist will review the PR, suggest clarifications or additional citations, and merge when the entry meets scholarly standards.

## File Organization

*   All transcribed entries are consolidated in `journal_entries.md`, with each entry headed by its date in ISO format (`1818‑12‑10`).
*   Supplementary materials (maps, artifact photographs, etc.) should be placed in the `supplementary/` directory.

## Citations

When adding annotations that rely on external sources, please include a brief citation in parentheses after the note, e.g., `[Arch: typical Mississippian platform mound (Smith 2005, p. 42)]`.

Thank you for helping to make this important primary source accessible to researchers and the public.