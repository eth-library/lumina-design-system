# Output Format

This file defines the standard output format for image-generation prompts created from the Lumina Design System.

The goal is to make prompt outputs consistent, practical and easy to reuse across different image generation models.

Every generated prompt should be clear enough to use directly, but structured enough to review and adapt.

---

## Core Principle

The output should not only provide a prompt.

It should also explain the visual concept behind the prompt.

A good Lumina prompt output helps the user understand:

- what the image should communicate
- why the composition fits the topic
- how the Lumina visual language is applied
- which colours should dominate
- what the image model should avoid

---

## Standard Output Structure

For image-generation tasks, use the following structure:

1. Concept title
2. Use case
3. Visual concept
4. Main image prompt
5. Negative prompt
6. Suggested aspect ratio
7. Colour notes
8. Design-system check
9. Optional variants

The output should be practical and ready to use.

---

## 1. Concept Title

Provide a short, descriptive title.

The title should describe the visual idea, not just the topic.

Good examples:

- Semantic Discovery Workspace
- Trusted Core Service Layer
- Human-in-the-Loop Subject Review
- Metadata Enrichment Pipeline
- Connected Research Landscape

Avoid vague titles such as:

- AI Image
- Lumina Graphic
- Nice Illustration
- Future Library

---

## 2. Use Case

State the intended use case.

Examples:

- Presentation hero
- Web hero
- Concept explainer
- Architecture diagram
- Workflow illustration
- Dashboard illustration
- Infographic
- Documentation visual
- Social media visual

If the use case was not specified, infer the most likely use case from the request.

If the request is ambiguous and the medium matters, ask a short clarification question before generating the final prompt.

---

## 3. Visual Concept

Describe the image in a short paragraph.

The visual concept should explain:

- the main idea
- the focal point
- the relationship between people, knowledge and technology
- the composition pattern
- the intended tone

The visual concept should not be overly poetic.

It should help the user judge whether the image idea is appropriate before using the prompt.

Example:

A calm presentation hero showing a library expert reviewing AI-generated subject suggestions. Bibliographic records enter a semantic matching workflow, are compared with a controlled vocabulary, and become ranked subject candidates. The image emphasises transparency, human review and reusable semantic infrastructure.

---

## 4. Main Image Prompt

Provide the final image-generation prompt.

The prompt should be written as one coherent block of text.

It should include:

- image type
- Lumina topic
- main message
- audience or use case
- composition
- visual elements
- colour direction
- illustration style
- constraints and avoidances

The prompt should be detailed enough to guide the image model, but not overloaded with too many small requirements.

---

## 5. Negative Prompt

Always provide a negative prompt.

The negative prompt should protect the Lumina visual identity.

Use the default negative prompt from `prompt-system/prompt-generator.md` and adapt it to the specific topic when needed.

The negative prompt should usually include exclusions such as:

- photorealism
- 3D render
- robots
- glowing AI brains
- cyberpunk aesthetics
- binary-code backgrounds
- rainbow palettes
- cluttered dashboards
- unreadable text
- distorted logos
- fake product screenshots
- chaotic networks

Do not make the negative prompt so broad that it prevents useful visual elements.

For example, when creating a Lumina Studio dashboard visual, do not exclude dashboards entirely. Exclude only cluttered, dense or alarm-heavy dashboards.

---

## 6. Suggested Aspect Ratio

Always provide a suggested aspect ratio.

Common options:

### 16:9

Best for presentation slides.

Use for:

- slide heroes
- concept explainers
- architecture diagrams
- workflow illustrations
- infographics

### Wide hero

Best for web pages.

Use for:

- landing page headers
- service pages
- campaign visuals
- wide atmospheric compositions

Suggested ratios:

- 21:9
- 3:1
- 16:6

### Square

Best for compact visuals.

Use for:

- social media
- thumbnails
- cards
- internal documentation previews

Suggested ratio:

- 1:1

### Portrait

Best for vertical layouts.

Use for:

- posters
- vertical web sections
- handouts
- mobile-first layouts

Suggested ratios:

- 4:5
- 3:4
- 9:16

---

## 7. Colour Notes

Provide short colour guidance.

Colour notes should mention:

- dominant colours
- secondary colours
- accent colours, if any
- colour meaning
- restrictions

Example:

Dominant white background with ETH Blue as the main structural colour. Use ETH Petrol for semantic connections and data flows. Use ETH Grey for secondary interface elements. Use ETH Green only for validated or accepted suggestions. Avoid ETH Red unless showing warnings or rejected candidates.

Do not repeat the full colour system in every output.

Keep colour notes practical.

---

## 8. Design-System Check

Provide a short checklist showing that the prompt follows the Lumina Design System.

Use this format:

- Knowledge, people or library services are central.
- Technology supports the story rather than dominating it.
- ETH Blue, black and white form the primary colour basis.
- Secondary colours are used with restraint.
- The composition is calm and readable.
- AI clichés are avoided.
- The image is suitable for the intended medium.

If the prompt intentionally deviates from the design system, state the reason clearly.

---

## 9. Optional Variants

When useful, provide up to three optional variants.

Variants should differ in communication strategy, not only in style.

Good variant types:

### Strategic Variant

More suitable for leadership or high-level presentations.

Focuses on value, trust and system role.

### Operational Variant

More suitable for library staff or service owners.

Focuses on workflows, review and quality.

### Technical Variant

More suitable for technical teams.

Focuses on architecture, APIs, pipelines and data flows.

### User-Facing Variant

More suitable for web, discovery and researcher communication.

Focuses on user benefit, search, exploration and understanding.

Do not provide variants if the user asked for one specific final prompt only.

---

## Standard Response Template

Use this structure for normal prompt-generation responses:

```text
# Concept Title

[Short title]

## Use Case

[Intended use case]

## Visual Concept

[Short explanation of the visual idea]

## Main Image Prompt

[Full prompt ready to paste into an image-generation model]

## Negative Prompt

[Negative prompt]

## Suggested Aspect Ratio

[Aspect ratio]

## Colour Notes

[Practical colour guidance]

## Design-System Check

- [Checklist item]
- [Checklist item]
- [Checklist item]

## Optional Variants

[Optional variants, only if useful]
```

---

## Short Response Format

Use this shorter format when the user explicitly asks for a quick prompt:

```text
Concept: [short concept title]

Prompt:
[main image prompt]

Negative prompt:
[negative prompt]

Aspect ratio:
[suggested aspect ratio]
```

The short format should still follow the Lumina Design System.

---

## Direct Image Generation

If the current environment can generate images directly, the assistant may generate the image.

Before generating the image, the assistant should still internally apply the Lumina Design System.

If the environment cannot generate images directly, the assistant should provide a complete prompt that can be used in another image-generation model.

Do not claim that an image has been generated unless an image-generation tool was actually used.

---

## Image Review Output

When reviewing an existing Lumina image, use this structure:

```text
# Image Review

## Overall Assessment

[Short assessment]

## What Works

- [Observation]
- [Observation]

## What Should Be Improved

- [Observation]
- [Observation]

## Design-System Alignment

- Colour system: [assessment]
- Illustration style: [assessment]
- Composition: [assessment]
- Lumina concept: [assessment]
- Avoidance of clichés: [assessment]

## Recommended Prompt Adjustments

[Concrete changes for the next generation]
```

Reviews should be specific and constructive.

Avoid vague comments such as "make it better" or "more modern".

---

## Editing Existing Prompts

When improving an existing prompt, preserve the user’s intent.

Improve:

- clarity
- composition
- Lumina alignment
- colour guidance
- negative prompt
- audience fit
- use-case specificity

Do not rewrite a prompt into a different concept unless the user asks for a new direction.

---

## Quality Standard

A good Lumina prompt output is:

- clear
- specific
- reusable
- visually consistent
- aligned with ETH colours
- grounded in the Lumina Design System
- free of generic AI clichés
- suitable for the intended medium

The final output should help create an image that feels recognisably Lumina.

## Output Modes

The Lumina Design System supports two output modes:

1. Prompt-based output
2. Direct image generation

The correct mode depends on the capabilities of the environment.

---

### Prompt-Based Output

Use this mode when the system cannot generate images directly.

Output:

- structured prompt (according to this file)
- negative prompt
- aspect ratio
- colour notes
- design-system check

This mode is model-neutral and can be used with any image generation tool.

---

### Direct Image Generation

Use this mode when the system can generate images directly (e.g. Codex, GPT-based image generation tools).

Output:

- the generated image
- optionally a short explanation of the concept
- optionally the underlying prompt (for reuse)

In this mode:

- the full prompt structure does not need to be shown to the user
- the assistant should still internally apply the Lumina Design System
- the assistant should ensure that the generated image follows:
  - Lumina visual principles
  - ETH colour system
  - composition rules
  - do’s and don’ts

---

### Recommended Behaviour

When direct image generation is available:

- Default to generating the image
- Provide a short concept description (1–3 sentences)
- Optionally include the prompt if the user might reuse it

When prompt-only output is required:

- Use the full structured format defined above

---

### Hybrid Mode (Recommended)

In advanced environments (e.g. Codex):

Provide:

1. the generated image
2. a short concept description
3. the prompt used internally (optional but recommended)

This allows:

- immediate visual output
- reproducibility
- iterative refinement

---

### Important Constraint

Even in direct generation mode:

- do not switch to generic AI styles
- do not optimise only for visual appeal
- always prioritise Lumina identity and clarity

The design system must remain the source of truth.

---

### Quality Check for Direct Generation

Before returning an image, verify:

- Does the image reflect a Lumina concept clearly?
- Are knowledge, people or library services central?
- Are ETH colours used correctly?
- Is the composition calm and structured?
- Are AI clichés avoided?
- Is the image usable in the intended context (slide, web, etc.)?

If not, regenerate or refine.
