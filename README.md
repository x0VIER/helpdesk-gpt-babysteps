# Help Desk Baby Steps GPT

A beginner-friendly, CompTIA-aligned Help Desk assistant GPT that walks users step-by-step with exact clicks, what each action does, and why we do it.

## What's included
- Knowledge base (baby-step style) for OS, networking, security, and operations
- Realistic help desk scenarios with click-by-click instructions
- Prompt templates (JSON) to import into Custom GPT builders
- License: MIT

## Quick start
1. Download the repo.
2. Import the `prompts/babysteps_prompt.json` into your Custom GPT builder (e.g., OpenAI's GPT builder) or use the prompt text in `prompts/helpdesk_prompt.json`.
3. Upload the `knowledge_base/` and `scenarios/` files into the GPT builder as reference docs (up to 20 files supported by OpenAI). See OpenAI docs for file limits.
4. Publish or test privately and iterate.

## Files of interest
- `prompts/babysteps_prompt.json` — primary instruction set for the baby-steps behavior.
- `knowledge_base/` — modular reference articles used as the GPT's knowledge.
- `scenarios/` — PBQ-style practice problems and full solutions.

## License
MIT License

## Maintainer
X0VVIER
