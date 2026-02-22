# Lessons Learned

Date: 2026-02-22

## Scope and Terminology
- Treat **Lean Ethereum** as an Ethereum protocol direction, not as the Lean programming language.
- Do not add generic Lean language learning resources when curating Lean Ethereum materials unless explicitly requested.

## Structure and De-duplication
- Avoid duplicate sections across the document.
- If content is already covered in `Official entry points` or another top-level section, do not repeat it in `Call series` or `Updates`.
- Respect user deletions: when the user removes a section (for example, `## 8. Updates`), do not reintroduce it implicitly.

## Collaboration Behavior
- Follow the user's provided framework first, then extend it.
- Keep corrections persistent by recording them in `tasks/lesson.md` for future iterations.

## README Link Style
- Prefer the Awesome-list format: `[Name](URL) - One-line description`.
- In video collections, always include a readable title before each URL.
- Avoid bare URLs in bullet lists unless explicitly required.
- Keep link names short; move explanatory details to the trailing description.
- Link titles must start with an uppercase letter for consistent formatting.

## Video Curation
- Prefer official playlists over listing every individual recording when both are available.
- Use playlist links to reduce duplication and keep the list compact.

## Taxonomy and Placement
- When the user asks to move resources across sections (for example, splitting implementations into Consensus/Data/Execution), apply the reclassification directly instead of keeping a global bucket.
- Map implementations to the closest protocol domain (for example, Ream -> Lean Consensus) and remove duplicates from the original section.
- After each user correction about structure, immediately persist the rule in lessons without requiring a reminder.

## Source-of-Truth Completeness Checks
- When the user asks to verify completeness against a specific source page, mirror that source taxonomy first and do a one-to-one coverage check.
- Do not keep a custom grouping if it hides missing source-defined tracks; prioritize source-aligned section headers.
- Treat [leanroadmap.org](https://leanroadmap.org/) as the default source of truth for Lean Ethereum research/status tracking.
- On each future README refresh, check leanroadmap.org for newly added tracks/resources and append missing items.
- Source-of-truth diffs may include both additions and removals, but these edits must be proposed for user review first.
- Do not apply source-driven content changes silently; wait for explicit user approval before finalizing README modifications.
