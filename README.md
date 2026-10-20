# jobhunter

A focused, tool-independent job-hunting skill for ChatGPT and Codex: tailor CVs from real evidence, find relevant roles, draft letters, track applications and prepare for interviews.

Inspired by [soheilfallah/jobxhunter](https://github.com/soheilfallah/jobxhunter). This is an independent adaptation, not an official release or an OpenAI-endorsed integration.

## Use in ChatGPT

Open [SKILL.md](skills/jobhunter/SKILL.md), copy the instructions below the YAML frontmatter into your chat or project instructions, and supply your CV/profile and the target job description privately. Upload the reference templates when needed, or paste their content. Tell ChatGPT to use these instructions for the task. Merely linking this repository does not install a plugin or grant tool access.

Example requests:

- “Tailor my CV to this advert. Use only supported facts and list gaps.”
- “Find five relevant roles in my target location and verify the vacancy links.”
- “Draft a cover letter using my experience, then prepare interview questions.”

For environments supporting local Codex skills, copy the `skills/jobhunter` folder into your configured skills directory. Invoke `$jobhunter` where supported. Consult current [OpenAI skills and plugins guidance](https://learn.chatgpt.com/docs/skills-and-plugins) for your environment; this repository is a skill source, not a packaged or marketplace-published ChatGPT plugin.

## What is included

- `skills/jobhunter/SKILL.md`: the workflow and evidence rules.
- `references/profile-template.md` inside the skill: a blank private profile template.
- `references/tracker-template.csv` inside the skill: an empty tracker schema.
- `UPSTREAM.md` and `LICENSE`: provenance, scope and licence notice.

No dependencies or API keys are required for the text workflow. Live search, file creation, messaging and scheduling depend on tools available in the host. No Claude commands, connectors, scripts, agents, scraped datasets or personal profiles are bundled. Application submission, outreach and recurring runs require separate user instructions and appropriate tools.

## Privacy

Keep real CVs, contact details and application records outside this repository, preferably in a private workspace. The ignore rules reduce accidental commits but are not a privacy guarantee. The shipped templates contain no candidate data.

## Validation

The skill frontmatter and reference links were checked locally. The repository has not been tested as an installed ChatGPT plugin or against live job-board, email or document integrations. It does not guarantee ATS performance or employment outcomes.

## Licence and attribution

MIT; see [LICENSE](LICENSE). The upstream copyright and permission notice are retained. [UPSTREAM.md](UPSTREAM.md) records the source review and adaptation boundaries.
