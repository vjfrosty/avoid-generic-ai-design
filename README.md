# avoid-generic-ai-design

An agent skill for designing, building and reviewing interfaces that look product-specific instead of templated.

It covers:

- 20 core "AI design slop" patterns, each with a preferred alternative and a justified exception
- 15 further patterns drawn from independent lists and a measured audit of launch pages
- 12 optional typography techniques and 10 optional visual techniques, with current browser-support notes
- Functional and accessibility requirements (WCAG 2.2 contrast, target size, keyboard, motion, states, real content)
- A review format: location → problem → user consequence → fix → severity

The patterns are editorial heuristics, not an authorship detector. The skill does not produce a "slop score".

## Install

Claude Code:

```bash
git clone https://github.com/vjfrosty/avoid-generic-ai-design.git
cp -r avoid-generic-ai-design/avoid-generic-ai-design ~/.claude/skills/
```

Any other agent: use `avoid-generic-ai-design/SKILL.md` as an instruction brief.

## Use

> Apply these guidelines to the interface. Preserve the product's brand and working behavior. Replace unsupported decorative patterns with content-driven choices, verify factual claims, and check accessibility and responsive use.

## Sources and limits

Research checked 25 November 2026. The core list originates from "20 AI Design Slop Indicators" attributed to Charles Liu; the original post was not independently verified. Full source list is at the end of `SKILL.md`. Browser support changes, so re-check MDN or caniuse before relying on newer CSS in a project with an older support floor.

## License

MIT. See `LICENSE`.
