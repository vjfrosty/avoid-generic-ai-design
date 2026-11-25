---
name: "avoid-generic-ai-design"
description: "Design, build or review websites, landing pages, dashboards and app UIs so they look product-specific rather than templated. Use whenever the user builds or restyles any interface, asks to avoid AI slop or a vibe-coded/generic look, wants a design audit or critique, or asks for typography, color and accessibility polish, even if they don't mention AI."
---

# Avoid Generic AI Design

## Why this exists

Generated interfaces converge on the same defaults: one font, one purple, one card grid, one fade-in. Each default is harmless alone; stacked, they tell the visitor nobody made a decision. The fix is never to swap one default for another (cream for purple, serif for Inter). It is to make each element earn its place through the product, audience and task.

Two things matter more than any visual tell, because they damage trust and use rather than taste:

1. **Invented evidence** (stats, logos, testimonials, ratings).
2. **Things that don't work** (dead buttons, missing states, content hidden behind animation, inaccessible controls).

Treat those as blockers. Treat the stylistic tells as defaults to question.

## Operating rules

- **Required:** factual integrity, working interactions, accessibility. Never invent evidence or claim a check you did not perform.
- **Default:** avoid the patterns below unless the brief, an existing design system or the task gives them a purpose.
- **Exception:** keep a pattern when its benefit is clear, and note material exceptions in the delivery summary. Do not ask approval for routine choices.
- Follow the user's requested visual direction. Never replace an established brand to make it look less generated.
- These patterns are editorial heuristics, not an authorship detector. Human-made sites use them too, and automated detectors report false positives. Do not call a design AI-generated and do not produce a numeric "slop score".

## Workflow

1. **Understand.** Audience, primary task, essential content, brand constraints, available evidence. Inspect supplied screens and components. Ask only what would materially change the result; otherwise state assumptions and proceed.
2. **Define.** Write a 3 to 6 line design direction: content hierarchy, layout, type, color roles, imagery. Use concrete choices ("two-column comparison table, one accent used only for the primary action"), not adjectives like premium or modern. If the direction would fit any other product unchanged, it is not a direction yet.
3. **Structure.** Arrange real content before decoration. Tables for comparison, lists for scanning, prose for explanation, cards for distinct units. Let content count decide column count.
4. **Build or revise.** Apply the pattern tables and functional requirements. In existing products make targeted improvements and reuse sound components.
5. **Review.** Check the rendered result at about 320px and at wide width, at 200% zoom, with keyboard only, and with realistic data. For design-only work, list the implementation checks left unverified.
6. **Deliver.** Summarize the result, meaningful exceptions, checks actually performed, and open limitations. A checklist never proves WCAG conformance; say so if asked.

## Core patterns to question

| # | Avoid by default | Do instead | Keep when |
| --- | --- | --- | --- |
| 1 | Arrow on every button | Descriptive labels: "Save changes", "Download report" | Back, next or navigation where direction clarifies behavior |
| 2 | Decorative dots between words | Natural copy or a semantic list | Separating independent metadata (author, date) |
| 3 | Eyebrow label above every heading | Let headings carry hierarchy | It adds context: product family, article category |
| 4 | Cream or beige as automatic sophistication | Surfaces chosen from brand needs and verified contrast | Part of an intentional, accessible palette |
| 5 | One italic (often serif) word per headline | Hierarchy through scale, weight, spacing, meaning | Editorially meaningful emphasis or an established type system |
| 6 | Sparkle icons as filler or as "AI" | Name the action; use a relevant symbol | An established AI-action convention with a clear label |
| 7 | Everything in a card, borders inside borders | Proximity, alignment, whitespace, dividers | Distinct, independently actionable units |
| 8 | "Quiet intelligence", "quiet confidence" | Say what the product does | Literal use or a defined brand voice |
| 9 | Decorative 01 / 02 / 03 numbering | Unnumbered sections | Ordered steps, rankings, chapters, referenced items |
| 10 | Pulsing green status dot | Real state with a readable label; show unknown or stale | Backed by live data; animate only if motion informs |
| 11 | Blurred glow or gradient blob behind the hero | Hero built on the message and real product imagery | Deliberate brand treatment that keeps legibility and performance |
| 12 | A fashionable typeface by reflex (Instrument Serif, Space Grotesk, Geist, Inter for everything) | Type chosen for content, readability and language coverage | It fits the approved type system. None of these is a bad typeface |
| 13 | Colored left or top border on every block | Grouping without decoration | Quotes, selected items, semantic callouts with meaning beyond color |
| 14 | Three identical icon cards in a row | Layout that follows the real number and kind of items | Three real peer items that work responsively |
| 15 | Pill badge above every headline | Remove redundant badges | A real release, category, status or announcement |
| 16 | "Real results", "real impact" | State the capability or supported outcome | Distinguishing factual from simulated; verify "real-time" |
| 17 | **Invented proof** | Traceable evidence or no claim | Sample data visibly labeled as sample in prototypes. Never as customer evidence |
| 18 | Stacked two-word slogans: "Work smarter. Go further." | Who can do what, and why it helps | Concise control labels and the occasional brand phrase |
| 19 | Every section fading or sliding in on scroll | Content visible immediately | Limited, purposeful motion that never delays reading; honor reduced motion |
| 20 | Default grain or dithering | A coherent layout and relevant assets first | Intentional texture that does not obscure text, controls or data |

## Further patterns from wider research

Independent lists and one measured audit of launch pages converge on these as well. Same rule applies: question the default, keep the justified use.

| Avoid by default | Do instead |
| --- | --- |
| Lavender or purple-to-blue accent and gradient text on headlines | Color roles derived from the brand; solid text with verified contrast |
| Permanent dark mode with mid-grey body text | Pick the theme for the context; measure body text contrast on every surface |
| Glassmorphism and glowing borders on every panel | One elevation system; blur only where layering carries meaning |
| Emoji as navigation or feature icons | One coherent icon set matched to the type weight, with text labels |
| One radius and one soft shadow on everything | Radius and elevation that vary by role (control, panel, media) |
| Everything centered: hero, sections, body copy | Alignment that follows reading and scanning; left-align long text |
| All-caps, letter-spaced labels and headings everywhere | Sentence case; caps only for short labels where the type system defines them |
| Stat banner row ("10x faster", "99.9%", "500+") | Only sourced numbers, placed where they support a claim |
| Bento grid as the default feature layout | A layout chosen from content relationships |
| "Get started" and "Learn more" on every button | Label the actual outcome: "Create account", "See pricing" |
| Copy that fits any company: "seamless", "supercharge", "unlock the power" | A sentence only this product could publish: what, for whom, with what constraint |
| Abstract 3D blobs, stock teams, fake dashboards, generated faces | Real screenshots, domain-specific illustration, real people only with consent |
| Em dashes scattered through UI copy | Plain sentences; commas, periods, colons |
| Hover effects that do nothing; cards that grow on hover without being clickable | Affordances only on interactive elements, with visible focus as well as hover |
| Layout that only holds at demo dimensions | Design against long names, two rows and ten thousand rows, negative and missing values |

## Typography techniques (optional)

Use one only when it fixes a visible problem. All are progressive enhancements: the layout must be acceptable without them.

| Technique | Use for | Implementation and restraint |
| --- | --- | --- |
| Reserved bold width | Tabs or nav that shift when the active label turns bold | Reserve the widest state (hidden duplicate via `aria-hidden` pseudo-content or a grid overlay), or use a variable-font grade axis. Do not expose duplicate text to assistive tech |
| Text-box trim | Optical alignment of display text or button labels with adjacent shapes | `text-box: trim-both cap alphabetic`. Supported in current Chrome, Safari and Firefox (Baseline newly available since August 2026), so older browsers simply keep normal leading. Do not trim multi-line body text |
| Balanced and pretty wrapping | Lopsided headings; single-word last lines in paragraphs | `text-wrap: balance` on short headings only (it is costly and line-limited); `text-wrap: pretty` on body text as an enhancement. Never apply either to `*` |
| Underline offset | Underlines crowding descenders | Small `text-underline-offset` and `text-decoration-thickness`. Links must stay recognizable without relying on color |
| Superscript spacing | Footnote markers, ordinals, exponents | Semantic `<sup>`; tune size and position so line height does not jump. Not a decorative label system |
| Fluid type | Large headings across viewport widths | `clamp(min, preferred, max)` with a rem-based term so user zoom still scales it. Test 200% zoom and long translated strings. Never shrink essential text to keep one line |
| Tabular numbers | Columns of figures, timers, prices that jitter | `font-variant-numeric: tabular-nums` where the font supports it; right-align numeric columns |
| Small caps acronyms | Softening a short acronym in running text | `font-variant-caps: all-small-caps` only if the font has real small caps for the script in use. Keep the true acronym in source text |
| Locale quotes | Editorial copy | Correct marks per language (English curly quotes, Bulgarian „…“). Keep straight quotes in code, data, identifiers and user input |
| Middle truncation | Long filenames where start and extension both matter | Needs content-aware logic, not `text-overflow`. Keep the full value reachable. Never hide the distinguishing segment |
| Auto hyphenation | Long-form prose in narrow columns | Correct `lang` attribute plus `hyphens: auto`; inspect the result per language. Exclude names, URLs, short labels |
| Line-clamped titles | Repeated preview tiles with uneven titles | Prefer wrapping. If clamping, use the prefixed set (`display: -webkit-box; -webkit-box-orient: vertical; -webkit-line-clamp: N; overflow: hidden`), since unprefixed `line-clamp` is still not Baseline. Full title must be available at the destination |

## Visual techniques (optional)

| Technique | Good use | Check before shipping |
| --- | --- | --- |
| Concentric radius | A rounded element nested in a rounded surface | Inner radius = outer radius minus the inset. Inspect at real size |
| Alpha borders | Gentle separation on changing surfaces | Visible on every background and theme. Alpha does not guarantee the 3:1 needed for control boundaries |
| OKLCH palettes | A controlled ramp of lightness, chroma and hue | Check gamut clipping and the measured contrast of every text and control pair. Equal lightness is not accessible contrast |
| OKLCH gradients | A gradient the brand or content calls for | `linear-gradient(in oklch, ...)`; inspect midpoint colors and any overlaid text |
| Matched icon weight | Icons beside text | One icon set; stroke, size and optical alignment tuned to the type. Never an icon alone for a non-obvious action |
| Masked edges | Fading decorative imagery into a surface | `mask-image` on decoration only; nothing important in the faded zone |
| Blurred icon swaps | Closely related icon states (copy to copied) | State understandable without animation; under about 200ms; disabled for reduced motion |
| Dark mode depth | Hierarchy between dark surfaces | Step surface lightness, borders and spacing rather than shadows; verify text and focus on each layer |
| Dynamic viewport | Full-height mobile panels | `100dvh` to track browser chrome, `100svh` to avoid resize jumps. Test with the on-screen keyboard |
| Multiply blending | Product imagery on a tinted background | `mix-blend-mode: multiply` with `isolation: isolate`; compare against the unblended image in both themes |

## Functional and accessibility requirements

These are requirements, not taste.

- **Honest controls.** A button does what its label says. Links navigate, buttons act, native elements first. No clickable-looking decoration. State prototype limitations explicitly.
- **One clear primary action** per decision area; secondary actions visibly secondary.
- **Text contrast.** At least 4.5:1 for normal text and 3:1 for large text (about 24px regular or 18.7px bold) under WCAG 2.2. Measure, do not estimate. APCA can inform perceptual tuning, but WCAG 3 has not settled its contrast method, so colors must still pass the WCAG 2 ratios.
- **Non-text contrast.** 3:1 against adjacent colors for what is needed to identify controls, states and meaningful graphics. Decorative borders are exempt.
- **Keyboard.** Everything reachable and operable, visible focus, logical order, meaningful accessible names. Nothing essential on hover only.
- **Status.** Pair color with text or another cue.
- **Target size.** WCAG 2.2 AA asks for 24 by 24 CSS px or sufficient spacing (a 24px circle centered on each undersized target must not touch another target). Prefer about 44 by 44 for frequent touch controls; that is a preference, not the AA minimum.
- **Motion.** Wrap nonessential animation in `prefers-reduced-motion`. Content must be present in the DOM and visible without waiting for an observer or scroll trigger; a trigger that never fires must not leave a blank section.
- **States.** Design empty (with a sentence of help), loading (including slow), partial failure, permission denied, validation error and success. These are where generated interfaces most often fail and where screenshots never look.
- **Real content.** Long headings and names, translated labels, very few and very many rows, negative and missing numbers. For Bulgarian or other non-Latin interfaces verify glyph coverage and readability in the chosen fonts, including bold, italic and small caps.
- **Responsive.** No clipped content, overlapping controls or accidental horizontal page scroll at 320px or 200% zoom. Give wide tables an intentional treatment. Content must survive increased text spacing.
- **Relevant assets.** Real screenshots and meaningful data over stock imagery, fake dashboards or filler animation.

## Rewrites

Use a capability claim only if the product supports it.

| Generic | Replacement |
| --- | --- |
| "Quiet intelligence. Real impact." | "Draft support replies from your approved help articles." |
| "Trusted by 10,000+ teams" with no source | Remove. Add verified evidence only when supplied |
| Cards titled Fast, Smart, Powerful | Describe actual features; pick list, comparison, workflow or screenshot by content |
| Green pulsing dot, "All systems operational", no data source | Show monitored state, or label it sample data |
| Staggered reveal on every paragraph | Render immediately; keep animation for interaction feedback |
| "Get started" as the only CTA text | "Create a free workspace" |
| Replacing every beige surface and serif to look less generated | Keep brand-appropriate choices; fix unsupported decoration, hierarchy and usability |

## Review output

Report each finding as:

**location → observed problem → user consequence → specific fix → severity**

Severity:

- **Blocker:** fabricated evidence, inaccessible or nonfunctional primary action, broken core flow, essential content hidden or unreadable.
- **Major:** missing states, contrast or target failures on secondary paths, layout breaking with real content.
- **Improvement:** unsupported decorative repetition that does not obstruct use.

Order by severity, then by how many screens are affected. End with the checks performed and the checks not performed.

## Checklist

- [ ] A named audience, task and concrete visual direction exist, and the direction would not fit a different product unchanged.
- [ ] Headings and calls to action describe actual content and behavior.
- [ ] Every number or credibility claim has a source or is visibly marked sample.
- [ ] Cards, badges, icons, borders, gradients and textures each serve a purpose.
- [ ] Layout follows the content, not a three-card or bento template.
- [ ] Essential content is readable without animation or scroll triggers.
- [ ] Keyboard, focus, contrast, target size and reduced motion checked where implemented.
- [ ] 320px, wide, and 200% zoom handle realistic content with key actions intact.
- [ ] Empty, loading, error, permission and success states are covered.
- [ ] Typography and color enhancements solve a visible problem, degrade gracefully and preserve full meaning.
- [ ] Remaining problems and unperformed checks are disclosed.

## Evidence and limits

Research checked 25 November 2026. Browser support moves; re-check MDN or caniuse before relying on a newer CSS feature in a project with an older support floor.

- The core 20 patterns originate from a list titled "20 AI Design Slop Indicators" attributed to Charles Liu, and the optional techniques from two companion lists of typography and design "hacks". Original posts were not independently verified. They are editorial heuristics.
- Adrian Krebs, [Scoring Show HN submissions for AI design patterns](https://www.adriankrebs.ch/blog/design-slop/): deterministic DOM and CSS checks over about 1,590 launch pages, with a reported 5 to 10% false-positive rate. Supports the "further patterns" table and the warning against treating tells as proof.
- Nielsen Norman Group: [Cards](https://www.nngroup.com/articles/cards-component/), [Scroll-Triggered Text Animations Delay Users](https://www.nngroup.com/articles/scroll-animations/). Support restraint, not bans.
- GOV.UK Design System: [Button](https://design-system.service.gov.uk/components/button/). Action-specific labels and one primary action.
- W3C WCAG 2.2 Understanding documents: [1.4.3 Contrast](https://www.w3.org/WAI/WCAG22/Understanding/contrast-minimum.html), [1.4.11 Non-text Contrast](https://www.w3.org/WAI/WCAG22/Understanding/non-text-contrast.html), [1.4.12 Text Spacing](https://www.w3.org/WAI/WCAG22/Understanding/text-spacing.html), [2.3.3 Animation from Interactions (AAA)](https://www.w3.org/WAI/WCAG22/Understanding/animation-from-interactions.html), [2.5.8 Target Size](https://www.w3.org/WAI/WCAG22/Understanding/target-size-minimum).
- [WCAG 3 Introduction](https://www.w3.org/WAI/WCAG3) and Adrian Roselli, [WCAG3 Contrast as of April 2026](https://adrianroselli.com/2026/04/wcag3-contrast-as-of-april-2026.html): WCAG 3 is a working draft with no settled contrast algorithm.
- [web.dev, New to the web platform in August 2026](https://web.dev/blog/web-platform-08-2026): text-box properties reach Baseline.
- MDN: [line-clamp](https://developer.mozilla.org/docs/Web/CSS/line-clamp), [text-wrap](https://developer.mozilla.org/docs/Web/CSS/text-wrap), [clamp()](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Values/clamp), [oklch()](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Values/color_value/oklch), [mask-image](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/mask-image), [mix-blend-mode](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/mix-blend-mode), [hyphens](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/hyphens), [length units](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Values/length).
- Ralabs, [How to review an AI-generated interface](https://ralabs.org/blog/ai-design-slop-how-to-review-ai-generated-interfaces/): states and real-data checks.

The workflow, severity scale and rewrites are a practical synthesis, not a published framework.