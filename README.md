# 课程作业 AI Skills

这套规则来自我用 AI 改读书报告、写实验报告和做课堂展示时遇到的问题。每个 Skill 都说明该先给 AI 看哪些材料、怎么协作，以及交付前要怎么检查。

| 我想做什么 | 入口 |
| --- | --- |
| 完成《东方文明史》分周讨论、查证引用、制作个人展览海报和 AI 使用展示 | [东方文明史](.agents/skills/eastern-civilization/SKILL.md) |
| 按课表、讲义和记录准备大学物理实验报告 | [物理实验](.agents/skills/physics-lab-report/SKILL.md) |
| 用代码、命令和调试记录写系统二实验报告 | [系统二](.agents/skills/sys2-lab-report/SKILL.md) |
| 用自己的经历和判断写读书报告、课程论文或反思 | [中文写作](.agents/skills/personal-writing/SKILL.md) |
| 先定讲述顺序和视觉参考，再做课堂 PPT | [课堂 PPT](.agents/skills/classroom-presentation/SKILL.md) |

在 Codex 里打开本仓库，选用对应 Skill，再提供你这一次的材料。也可以把具体的 `SKILL.md` 链接交给能读取网页的 AI，注明它是本次任务的要求。使用课堂 PPT 规则时，PPT Master 可以负责制作和导出。

手上只有题目也可以开始。先给作业要求或现有片段，AI 会读已有材料，再针对缺少的观点、现场观察或证据提一两个具体问题。你可以直接说自己的想法，也可以让 AI 先指出有哪些值得讲的线索。材料已经齐全时，可以直接一起梳理主线，再从最容易写偏的一段试写。 [协作流程和实例](.agents/skills/personal-writing/references/coauthoring.md)

需要跨周使用同一套要求，可以在固定课程项目中保存私有的 `.course-context/`。复制设置示例后可直接编辑。新对话先读记录，再打开当次需要的模板和资料。切换到别的项目时可以直接提供记录文件或目录。 [用户可编辑的设置样例](course-context.example.md) · [课程资料与偏好记录](.agents/skills/personal-writing/references/course-context.md)

刚开始可以试一句：「帮我写读书报告。我还没有提纲，先问我一个能找到写作切入点的问题。」已经有手改稿的，可以给同一模型两份相同的材料，在两个新对话中分别启用和不启用中文写作 Skill，比较它能否保住原意、接顺逻辑、减少手改。仓库也提供了一轮从原话到试写的示范。 [文风学习与试用案例](.agents/skills/personal-writing/references/writing-examples.md)

如果你想下次写报告时再用，可以点 Star 收藏。

## 外部 Skill

| 入口 | 适合什么时候用 |
| --- | --- |
| [PPT Master](https://github.com/hugohe3/ppt-master/blob/main/skills/ppt-master/SKILL.md) | 制作或修改可编辑 PPTX。课堂 PPT Skill 负责讲述顺序、文案和放映检查。 |
| [OpenAI Image Generation](https://github.com/openai/skills/blob/main/skills/.system/imagegen/SKILL.md) | 需要生成或编辑海报、PPT 的图片时，使用当前环境可用的图像生成能力。 |
| [PPT Master 配图流程](https://github.com/hugohe3/ppt-master/blob/main/skills/ppt-master/references/image-generator.md) | 已用 PPT Master 制作演示，并需要管理配图时，查看它的图像生成流程。 |
| [ConardLi 的 GPT Image 2](https://github.com/ConardLi/garden-skills/blob/main/skills/gpt-image-2/SKILL.md) | 按海报和配图模板组织提示词，也可以指导局部编辑。 |
| [JimLiu 的 Baoyu Infographic](https://github.com/JimLiu/baoyu-skills/blob/main/skills/baoyu-infographic/SKILL.md) · [Baoyu Image Gen](https://github.com/JimLiu/baoyu-skills/blob/main/skills/baoyu-image-gen/SKILL.md) | 前者组织信息图的布局与风格，后者对接已配置的生成服务。 |

先按交付物进入对应任务流程。该流程列出的模板、资料和用语检查都需要打开并执行。流程要求用外部 Skill 时，先加载当前可用的对应 Skill；未安装时先尝试阅读上游的相关步骤，用现有工具完成可交付部分。缺少当前课件、原始数据或出图工具时，继续处理能核实的内容，并明确还有哪一步缺材料。

写作协作也参考了 Anthropic 的独立读者试读和 Superpowers 的提问方式。这两份适合按需要阅读。 [Doc Co-Authoring](https://github.com/anthropics/skills/blob/main/skills/doc-coauthoring/SKILL.md) · [Superpowers Brainstorming](https://github.com/obra/superpowers/blob/main/skills/brainstorming/SKILL.md) · [Agent Skills 评估指南](https://agentskills.io/skill-creation/evaluating-skills)
