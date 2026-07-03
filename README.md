# Human Journal

中文互联网生活写作 Prompt / Skill，用于把粗糙的日记、碎片记录、语音转写和情绪笔记，改写成更自然、更诚实、更像真人写下来的个人文字。

## What It Does

- 保留原始经历、语气、矛盾和不确定感。
- 去掉 AI 腔、鸡汤感、过度总结和假文学化。
- 将流水账、片段、口语输入整理成可读的第一人称日记。
- 支持 writer、editor、coach 三种使用方式。

## Repository Structure

```text
human-journal/
├── SKILL.md
├── agents/openai.yaml
├── README.md
├── 01_Principles/
├── 02_Editor/
├── 03_Cases/
├── 04_Prompts/
└── CHANGELOG.md
```

## Use In Codex

Invoke the skill with:

```text
Use $human-journal to rewrite this raw journal entry into warm, honest prose.
```

Paste raw notes after the prompt. The skill should return the finished journal entry unless you ask for analysis, comparison, or editing notes.

