# Contributor Instructions

These rules apply to people and AI agents who edit this repository.

## Scope

- Keep this a Markdown repository. Do not add an app, database, framework, package manager, or CI pipeline.
- Change only the files needed for the task.
- Do not add speculative features.

## Writing style

- Use plain English and short sentences.
- Use hyphen lists.
- Do not use semicolons in explanatory prose.
- Do not assume a tennis background. Explain terms or link to [footwork basics](docs/footwork-basics.md).

## Drill cards

- Use the [drill template](templates/drill-template.md) for every drill.
- Keep stable drill IDs such as `FW-01`. Never reuse or renumber an ID. Add new drills with the next free ID.
- Label doses and success thresholds as practice suggestions or practice goals.
- Keep court geometry realistic. Kitchen dink feeds come from the kitchen area, not the baseline.
- Movement choice depends on distance, time, and the next shot. Do not turn a cue into an absolute rule.

## Sources and provenance

- Give every drill source IDs from [resources](docs/resources.md) and one provenance label: source summary, original drill, or original adaptation.
- For an adaptation, say what was adapted.
- Do not attribute an original drill to a person who did not publish it.
- Never invent access dates, page numbers, prices, citations, or study findings.
- Do not commit third-party PDFs, images, or video. Link to them instead.
- Keep the existing [LICENSE](LICENSE) (CC BY 4.0). It covers original text only. Do not change it or apply it to third-party material.
- Write summaries in original words. Use only short attributed quotations when needed.

## Claims

- Do not claim scientific validation or guaranteed rating improvements.
- Do not add a medical or rehabilitation program.

## Before you commit

- Check every relative link and anchor.
- Check that plan time blocks add up exactly.
- Run `git diff --check`.
