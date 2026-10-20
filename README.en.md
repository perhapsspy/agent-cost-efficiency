# Agent Cost Efficiency

[한국어](README.md) | [English](README.en.md)

A skill that reduces avoidable token, time, and tool-execution cost in agent work while preserving required verification and result quality. Narrow and reuse evidence, bound execution, observation, and delegation, and leave the state needed for the next phase.

## Quick Start

```bash
npx skills add perhapsspy/agent-cost-efficiency
```

Or copy `skills/agent-cost-efficiency` into your agent's skill directory.

Request work normally; the skill participates when there is clear excess-cost risk. You can also ask for it directly:

```text
Use the agent-cost-efficiency skill to reduce reading, output, and retry cost in this long investigation while completing the required verification.
```

## Use When

- Repository exploration is broad, or diffs, logs, or test outputs are large.
- Execution or retry loops are costly even with small output, and prior results should guide the next execution or observation.
- Browser checks, UI checks, or progress observations repeat.
- Delegation cost and duplicated work need bounds.
- A long task changes phase and needs resumable state.
- Always-read instructions or always-available tools and skills are expanding and need a recurring-cost check.

Handle small edits, direct answers, and routine test runs through the existing workflow.

## More

- Skill rules: [English](skills/agent-cost-efficiency/SKILL.md) | [한국어](skills/agent-cost-efficiency/SKILL.ko.md)
- Evolution and maintenance: [Skill direction](docs/skill-direction.md)
- Cost-risk assessment: [Work cost signals](docs/reference/observed-token-patterns.md)

## Support

[![Buy Me A Coffee](https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png)](https://www.buymeacoffee.com/perhapsspy)

## License

[MIT](LICENSE)
