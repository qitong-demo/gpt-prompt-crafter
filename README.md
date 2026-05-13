# GPT Prompt Crafter

`gpt-prompt-crafter` is a Codex Skill for turning vague, incomplete, or conversational requirements into structured prompts for GPT-5.4.

It helps users produce clear, reusable prompts with role framing, task goals, background context, output format, constraints, quality standards, and style requirements.

## When to Use

Use this Skill when you need to:

- Write a new prompt from a rough idea.
- Rewrite or improve an existing prompt.
- Create a system prompt, role prompt, task prompt, or reusable workflow prompt.
- Add output format, constraints, quality standards, or edge cases.
- Convert casual requirements into an executable instruction set.

## Example Prompt

```text
Use $gpt-prompt-crafter to turn my rough task idea into a structured prompt.
```

Then provide your rough goal, target model, audience, desired output, constraints, and any examples you already have.

## Output Structure

The Skill responds in Chinese by default and uses this structure:

1. 需求理解
2. 最终提示词
3. 优化说明
4. 可选增强版

## Files

- `SKILL.md`: Skill definition and prompt-crafting workflow.
- `agents/openai.yaml`: Agent display metadata and default prompt.
