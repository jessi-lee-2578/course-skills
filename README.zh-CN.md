# 课程作业 AI Skills

[English](README.md)

一套用于课程作业、实验报告和课堂展示的 AI 协作流程。每个 Skill 都说明该提供哪些材料、怎样和 AI 一起完成任务，以及交付前要检查什么。Skill 正文使用中文。

| 我想做什么 | 入口 |
| --- | --- |
| 完成《东方文明史》讨论题、查证引用、制作展览海报 | [东方文明史](.agents/skills/eastern-civilization/SKILL.md) |
| 准备大学物理实验记录表、预习报告或正式报告 | [物理实验](.agents/skills/physics-lab-report/SKILL.md) |
| 用代码、命令、日志和调试证据写系统二实验报告 | [系统二](.agents/skills/sys2-lab-report/SKILL.md) |
| 用自己的写法完成读书报告、课程文章或反思 | [中文写作](.agents/skills/personal-writing/SKILL.md) |
| 策划课堂展示，先审文稿和模板再做 PPT | [课堂 PPT](.agents/skills/classroom-presentation/SKILL.md) |

## 怎么开始

在 Codex 里打开本仓库，选用对应 Skill。用其他 AI 时，把对应的 `SKILL.md` 链接交给它，请它打开其中的参考文件，再提供当次材料。工具打不开链接时，可以上传需要的文件。

先告诉 AI 这份作业给谁看、由谁评阅。需要写自己的判断时，先用自己的话说说想法。这些信息缺失时，AI 应结合题目问你一个具体问题。等你回复时，它可以读材料、查证、列提纲。新写或大改长文时，先一起看提纲和试写，再展开全稿。[协作流程](.agents/skills/personal-writing/references/coauthoring.md)

写物理实验报告时，先提供本次实验在预约或教学网站上的详情页截图。做新 PPT 时，先看实际模板和完整文稿，再开始制作。

把长期课程要求和写作偏好保存到自己项目的 `.course-context/` 目录。评阅记录和个人材料留在自己的工作区。[可编辑设置样例](course-context.example.md) · [课程资料与偏好记录](.agents/skills/personal-writing/references/course-context.md)

想试写作流程，可以拿一道真实题目，让 AI 帮你找到自己最想讲的一点。有手改稿时，可以把修改前后两版给它，看看下次试写能否保留你的改法。[文风学习与试用案例](.agents/skills/personal-writing/references/writing-examples.md)

觉得用得上，可以点 Star，方便下次找到。

## 外部 Skill 和资料

| 入口 | 用途 |
| --- | --- |
| [PPT Master](https://github.com/hugohe3/ppt-master/blob/main/skills/ppt-master/SKILL.md) | 逐页内容和版式确认后，制作或修改可编辑 PPTX。 |
| [OpenAI Image Generation](https://github.com/openai/skills/blob/main/skills/.system/imagegen/SKILL.md) | 用当前环境中的图像工具生成或编辑图片。 |
| [PPT Master 配图流程](https://github.com/hugohe3/ppt-master/blob/main/skills/ppt-master/references/image-generator.md) | 在用 PPT Master 制作演示时管理配图。 |
| [ConardLi 的 GPT Image 2](https://github.com/ConardLi/garden-skills/blob/main/skills/gpt-image-2/SKILL.md) | 提供图片提示词模板，指导局部编辑。 |
| [Baoyu Infographic](https://github.com/JimLiu/baoyu-skills/blob/main/skills/baoyu-infographic/SKILL.md) 和 [Baoyu Image Gen](https://github.com/JimLiu/baoyu-skills/blob/main/skills/baoyu-image-gen/SKILL.md) | 组织信息图的布局与风格，调用已配置的图片生成服务。 |

独立读者试读和提问方法可参阅 [Doc Co-Authoring](https://github.com/anthropics/skills/blob/main/skills/doc-coauthoring/SKILL.md)、[Superpowers Brainstorming](https://github.com/obra/superpowers/blob/main/skills/brainstorming/SKILL.md) 和 [Agent Skills 评估指南](https://agentskills.io/skill-creation/evaluating-skills)。
