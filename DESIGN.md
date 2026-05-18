# Storola

## Mission
Create implementation-ready, token-driven UI guidance for Storola that is optimized for consistency, accessibility, and fast delivery across marketing site.

## Brand
- Product/brand: Storola
- URL: https://storola.com/
- Audience: readers and knowledge seekers
- Product surface: marketing site

## Style Foundations
- Visual style: structured, tokenized, content-first
- Main font style: `font.family.primary=Prompt`, `font.family.stack=Prompt, Poppins, Inter, sans-serif, Anek Bangla, system-ui, -apple-system, Segoe UI, Roboto, Arial, Noto Sans Bengali, sans-serif`, `font.size.base=16px`, `font.weight.base=400`, `font.lineHeight.base=24px`
- Typography scale: `font.size.xs=13px`, `font.size.sm=14px`, `font.size.md=15px`, `font.size.lg=16px`, `font.size.xl=17px`, `font.size.2xl=18px`, `font.size.3xl=20px`, `font.size.4xl=21px`
- Color palette: `color.text.primary=#0f172a`, `color.surface.muted=#ffffff`, `color.text.tertiary=#174e9d`, `color.text.inverse=#212529`, `color.surface.base=#000000`, `color.surface.raised=#0b56e0`, `color.surface.strong=#fff7f0`, `color.border.strong=#e7ecf4`
- Spacing scale: `space.1=4px`, `space.2=5px`, `space.3=6px`, `space.4=8px`, `space.5=8.8px`, `space.6=9px`, `space.7=10px`, `space.8=12px`
- Radius/shadow/motion tokens: `radius.xs=6px`, `radius.sm=8px`, `radius.md=10px`, `radius.lg=12px`, `radius.xl=15px`, `radius.2xl=18px`, `radius.step7=22px`, `radius.step8=50px` | `shadow.1=rgba(2, 6, 23, 0.12) 0px 14px 36px 0px`, `shadow.2=rgba(2, 6, 23, 0.1) 0px 10px 24px 0px`, `shadow.3=rgba(2, 6, 23, 0.05) 0px 6px 16px 0px`, `shadow.4=rgba(0, 0, 0, 0.18) 0px 8px 18px 0px` | `motion.duration.instant=150ms`, `motion.duration.fast=200ms`, `motion.duration.normal=300ms`

## Accessibility
- Target: WCAG 2.2 AA
- Keyboard-first interactions required.
- Focus-visible rules required.
- Contrast constraints required.

## Writing Tone
Concise, confident, implementation-focused.

## Rules: Do
- Use semantic tokens, not raw hex values, in component guidance.
- Every component must define states for default, hover, focus-visible, active, disabled, loading, and error.
- Component behavior should specify responsive and edge-case handling.
- Interactive components must document keyboard, pointer, and touch behavior.
- Accessibility acceptance criteria must be testable in implementation.

## Rules: Don't
- Do not allow low-contrast text or hidden focus indicators.
- Do not introduce one-off spacing or typography exceptions.
- Do not use ambiguous labels or non-descriptive actions.
- Do not ship component guidance without explicit state rules.

## Guideline Authoring Workflow
1. Restate design intent in one sentence.
2. Define foundations and semantic tokens.
3. Define component anatomy, variants, interactions, and state behavior.
4. Add accessibility acceptance criteria with pass/fail checks.
5. Add anti-patterns, migration notes, and edge-case handling.
6. End with a QA checklist.

## Required Output Structure
- Context and goals.
- Design tokens and foundations.
- Component-level rules (anatomy, variants, states, responsive behavior).
- Accessibility requirements and testable acceptance criteria.
- Content and tone standards with examples.
- Anti-patterns and prohibited implementations.
- QA checklist.

## Component Rule Expectations
- Include keyboard, pointer, and touch behavior.
- Include spacing and typography token requirements.
- Include long-content, overflow, and empty-state handling.
- Include known page component density: links (41), cards (39), buttons (30), lists (8), navigation (1).


## Quality Gates
- Every non-negotiable rule must use "must".
- Every recommendation should use "should".
- Every accessibility rule must be testable in implementation.
- Teams should prefer system consistency over local visual exceptions.
