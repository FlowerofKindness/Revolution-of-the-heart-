# Copilot instructions — Revolution of the Heart

Purpose
- Help AI coding/content agents be immediately productive by documenting repo structure, conventions, and safe edit boundaries.

Big picture
- Content-first: this repository is primarily Markdown and co-located assets (images, PDFs). There is no build system, runtime, or tests.
- Major modules: [Core/README.md](Core/README.md), [reBElious-ME/README.md](reBElious-ME/README.md), [Everyday-Angels/README.md](Everyday-Angels/README.md), [Courses-Education/README.md](Courses-Education/README.md), [444-Generations-Jewelry/README.md](444-Generations-Jewelry/README.md).
- Structure: each module is self-contained — a module README describes its intended content and file conventions. Keep changes localized to the relevant module folder.

What you may change (agent scope)
- Allowed: create and edit Markdown content, update or add images/PDFs next to the Markdown that references them, and fix simple typos or formatting.
- Disallowed: adding compiled code, services, CI/workflows, packaged apps, or significant structural refactors without an issue and owner sign-off.
- Naming: use lowercase, hyphen-separated filenames and folders (example: [Courses-Education/course-001/module-1/lesson-1.md](Courses-Education/course-001/module-1/lesson-1.md)).

Tone & editorial guidelines
- Maintain a trauma-informed, invitational voice consistent with [Core/README.md](Core/README.md) and the top-level README.
- Preserve original phrasing where intent or tone is important; when improving copy, make minimal edits and explain them in the PR description.

Developer workflows (practical)
- No build step: preview by opening files in VS Code or viewing them on GitHub.
- Quick start:
  - git clone https://github.com/FlowerofKindness/Revolution-of-the-heart-.git
  - cd Revolution-of-the-heart-
  - code .
- Branching & PRs: use short descriptive branches (e.g., feature/add-course-module). In PR descriptions link the module README and summarize content/tone changes.

Patterns & concrete examples
- Course lesson skeleton: see [Courses-Education/course-001/module-1/lesson-1.md](Courses-Education/course-001/module-1/lesson-1.md) for structure and front-matter patterns.
- Asset placement: place media files adjacent to the Markdown that references them (example: Courses-Education/course-001/module-1/hero.jpg).

Integration points & dependencies
- There are no runtime services or external package manifests in this repo. Treat integrations as editorial references (links, embeds, PDFs).

When to open an issue or ask an owner
- Open an issue before making substantive structural changes (new top-level folders, global renames, or adding CI/tests).
- Request owner review for changes to owner-curated areas: [Courses-Education/](Courses-Education/README.md) and [444-Generations-Jewelry/](444-Generations-Jewelry/README.md).

Files to consult
- Start with: [README.md](README.md) and [Core/README.md](Core/README.md) for voice and high-level intent.
- Module guidance lives in each module's README (e.g., [Courses-Education/README.md](Courses-Education/README.md)).

Final notes
- Keep edits small, localized, and reviewable. In PRs, list changed files and explain any editorial choices.
- If you'd like, I can run a pass that standardizes a single module's lesson skeleton—say which module to update.

Feedback
- Tell me which sections are unclear or missing and I will iterate.
