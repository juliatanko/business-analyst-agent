# Shared Agent Skills

A collection of reusable agent skills for sharing workflows across projects and teams. Each skill lives in its own folder under `.github/skills/` and contains a `SKILL.md` with the instructions and metadata needed for discovery.

## Skills

- [Business Analysis](.github/skills/business-analysis/SKILL.md): impartial BA workflows, templates, glossary, and examples for problem framing, requirements, process analysis, options, data/reporting, vendor evaluation, UAT, and change readiness.

## Use a Skill in Another Repository

Copy the skill's folder (for example, `.github/skills/business-analysis/`) into the target repository's `.github/skills/` directory. Copilot can then discover and invoke it from that repository.

## Add a Skill

1. Create `.github/skills/<skill-name>/SKILL.md`.
2. Use a lowercase, hyphenated folder name and make the frontmatter `name` match it.
3. Write a specific `description` with the tasks and phrases that should trigger the skill.
4. Keep `SKILL.md` concise; put detailed workflows, templates, glossaries, and illustrative examples in linked reference files.
5. Add the skill to the list above.

Keep each skill focused and self-contained. Put supporting references, templates, or scripts inside that skill's folder and link to them from `SKILL.md`.
