# Icons — substitution flag

**No SAM-Play-specific icon set was provided in the brief.** The closest free CDN match is **Lucide** — geometric, 1.75px stroke, generous corners — which aligns with the brand's "tidy but a little hand-set" feel.

## How to use Lucide

```html
<script src="https://unpkg.com/lucide@latest/dist/umd/lucide.min.js"></script>
<i data-lucide="circle"></i>
<script>lucide.createIcons();</script>
```

Or inline SVG directly: <https://lucide.dev/icons/>

## Brand-specific icon shapes (use these meanings when picking from Lucide)

| Concept | Icon | Lucide name |
| --- | --- | --- |
| "You" / a person | ◯ | `circle` |
| Room / location | ▢ | `square` |
| Moment / collectible | ◇ | `diamond` |
| Conversation / prompt | speech | `message-circle` |
| Save / take away | bookmark | `bookmark` |
| Friend / group | overlapping circles | `users` |
| Time / dwell | clock | `clock` |
| Direction | arrow | `arrow-right`, `move-up-right` |
| Close | × | `x` |
| More | … | `more-horizontal` |
| AI / story | sparkle | `sparkles` |

**⚠️ Please confirm Lucide as the production icon set, or provide a custom SAM Play icon library.**

## Unicode glyphs allowed as text-icons

`→ ← ↗ ↘ ✕ ✓ ★ ✱ ◦ • — ·`

These should be set in **Cosmica Mono** at body-text size; they read as type, not iconography.

## Emoji policy

System UI: **no**. User-generated content (reactions, chat replies, friend captions): **yes** — emoji from the user's native keyboard, rendered as text (not stylized).
