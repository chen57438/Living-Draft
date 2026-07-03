# Living Draft

Living Draft 不是 Prompt 库，也不是写作模板。

它是一套帮助 AI 成为编辑，而不是代笔的中文生活随笔写作系统。

大多数 AI Prompt 都在教模型如何写。

Living Draft 更关心模型如何删除、如何保留、如何克制。

## Philosophy

**写作不是创造观点。**

**写作是记录那些让你停下来想了一会儿的瞬间。**

## What It Does

- 从生活开始，不从观点开始。
- 帮作者保留自己的表达，而不是替作者发言。
- 找出最像作者的一句，也删掉最像 AI 的一句。
- 优先编辑、删减、重排，最后才润色。
- 把每次修改沉淀成可复用的 Rule。

## Structure

```text
Living-Draft/
├── README.md
├── CONSTITUTION.md
├── EDITOR.md
├── CASES/
└── CHANGELOG.md
```

`SKILL.md` and `agents/openai.yaml` are included so Codex can invoke this repository as a skill.

## Use In Codex

```text
Use $living-draft to edit this draft. Help me keep what sounds like me and remove what sounds like AI.
```

Paste a raw draft or notes after the prompt.
