# Course Skills

[简体中文](README.zh-CN.md)

Reusable AI workflows for coursework, lab reports, and classroom presentations. Each skill explains what materials to share, how to work through the assignment together, and what to check before handing it in. The skill instructions are written in Chinese.

| What you want to do | Skill |
| --- | --- |
| Work through Eastern Civilization discussion questions, verify citations, or design an exhibition poster | [Eastern Civilization](.agents/skills/eastern-civilization/SKILL.md) |
| Prepare a university physics lab worksheet, preview report, or formal report | [Physics Lab Reports](.agents/skills/physics-lab-report/SKILL.md) |
| Write a Systems II lab report from code, commands, logs, and debugging evidence | [Systems II Lab Reports](.agents/skills/sys2-lab-report/SKILL.md) |
| Write a reading report, essay, or reflection in your own voice | [Personal Writing](.agents/skills/personal-writing/SKILL.md) |
| Plan a classroom talk and review its script and template before making the deck | [Classroom Presentations](.agents/skills/classroom-presentation/SKILL.md) |

## Getting started

Open this repository in Codex and choose the skill that fits your assignment. In another AI tool, give it the relevant `SKILL.md` link, ask it to read the linked references, and share your assignment materials. If the tool cannot open links, upload the files it needs.

Start by telling the AI who will read or assess your submission. For an assignment that calls for your own judgment, share what you think in your own words. The AI should ask a question tied to the assignment when that information is missing. It can read sources and prepare an outline while it waits. For a new draft or substantial rewrite, review the outline and a short sample before asking for the full text. [Co-authoring workflow](.agents/skills/personal-writing/references/coauthoring.md)

For a physics lab report, share a screenshot of the current experiment details from your booking or course portal. For a new slide deck, review the actual template and full script before production.

Save recurring course requirements and writing preferences in your own project's `.course-context/` directory. Keep review notes and personal materials there. [Editable settings example](course-context.example.md) · [Course context guide](.agents/skills/personal-writing/references/course-context.md)

To try the writing workflow, start with a real assignment and ask the AI to help find a point you want to make. If you have edited a draft by hand, share both versions and see whether the AI can carry your changes into the next sample. [Writing samples and examples](.agents/skills/personal-writing/references/writing-examples.md)

If you find the workflows useful, star the repository to find them again.

## Related skills and guides

| Resource | What it does |
| --- | --- |
| [PPT Master](https://github.com/hugohe3/ppt-master/blob/main/skills/ppt-master/SKILL.md) | Builds or edits an editable PowerPoint deck after you confirm the content and layout. |
| [OpenAI Image Generation](https://github.com/openai/skills/blob/main/skills/.system/imagegen/SKILL.md) | Generates or edits images using the image tools available in your environment. |
| [PPT Master image workflow](https://github.com/hugohe3/ppt-master/blob/main/skills/ppt-master/references/image-generator.md) | Helps manage images while building a deck with PPT Master. |
| [ConardLi's GPT Image 2](https://github.com/ConardLi/garden-skills/blob/main/skills/gpt-image-2/SKILL.md) | Provides templates for image prompts and guidance on editing parts of an image. |
| [Baoyu Infographic](https://github.com/JimLiu/baoyu-skills/blob/main/skills/baoyu-infographic/SKILL.md) and [Baoyu Image Gen](https://github.com/JimLiu/baoyu-skills/blob/main/skills/baoyu-image-gen/SKILL.md) | Help design infographics and use a configured image-generation service. |

For more on writing with an independent reader and asking concrete questions, see [Doc Co-Authoring](https://github.com/anthropics/skills/blob/main/skills/doc-coauthoring/SKILL.md), [Superpowers Brainstorming](https://github.com/obra/superpowers/blob/main/skills/brainstorming/SKILL.md), and the [Agent Skills evaluation guide](https://agentskills.io/skill-creation/evaluating-skills).
