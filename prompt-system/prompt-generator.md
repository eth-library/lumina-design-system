# Prompt Generator

This file defines how to generate image prompts from the Lumina Design System.

It is model-neutral.

It can be used with different AI assistants and image generation models.

The goal is not to create generic beautiful images.

The goal is to create visuals that are recognisably part of the Lumina ecosystem.

---

## Core Principle

A Lumina image prompt should be derived from the design system.

Do not start with a visual trend.

Do not start with a generic AI image style.

Start with:

1. the Lumina purpose
2. the intended audience
3. the communication goal
4. the relevant Lumina component or functional area
5. the visual principles
6. the colour system
7. the appropriate composition pattern

The final image should make a Lumina concept easier to understand.

---

## Standard Prompt Generation Workflow

Use this workflow for every image prompt.

---

### Step 1: Understand the Request

Identify the following:

- topic
- intended use case
- audience
- medium
- aspect ratio
- Lumina component or functional area
- desired level of detail
- main message

Typical use cases:

- presentation hero
- web hero
- concept explainer
- architecture diagram
- workflow illustration
- infographic
- documentation visual
- social media visual

Typical audiences:

- ETH Library leadership
- library staff
- researchers
- students
- technical teams
- project stakeholders
- external partners
- general academic audience

If the request is unclear, ask a short clarification question.

If enough information is available, continue without asking.

---

### Step 2: Select the Relevant Design Sources

Always apply the foundation files:

- `foundation/philosophy.md`
- `foundation/colours.md`
- `foundation/visual-principles.md`
- `foundation/illustration-style.md`
- `foundation/composition.md`
- `foundation/dos-and-donts.md`

Then select the relevant Lumina file:

- `lumina/lumina-core.md`
- `lumina/lumina-engine.md`
- `lumina/lumina-studio.md`
- `lumina/lumina-experience.md`
- `lumina/embedding-based-subject-indexing.md`

Use the selected files to determine:

- visual story
- typical elements
- composition
- colour emphasis
- things to avoid

Do not invent a new visual language when an existing definition applies.

---

### Step 3: Define the Visual Concept

Before writing the final prompt, define a visual concept.

A good visual concept includes:

- one clear focal point
- the main visual metaphor
- the relationship between people, knowledge and technology
- the most important visual elements
- the composition pattern
- the intended emotional tone

The visual concept should be short and practical.

It should explain what the image is about before describing how it looks.

---

### Step 4: Choose the Composition Pattern

Select one primary composition pattern.

Common patterns:

#### Presentation Hero

Use for opening slides or high-level storytelling.

Characteristics:

- spacious layout
- one clear focal point
- room for slide title
- calm background
- minimal detail

#### Web Hero

Use for websites and landing pages.

Characteristics:

- wide horizontal layout
- atmospheric but restrained
- space for headline and call to action
- strong but calm visual identity

#### Concept Explainer

Use for explaining a single idea.

Characteristics:

- central concept
- few meaningful supporting elements
- clear relationships
- easy to understand quickly

#### Workflow or Pipeline

Use for processes.

Characteristics:

- left-to-right or top-to-bottom flow
- clear steps
- transformation from input to output
- optional human review checkpoint

#### Architecture Diagram

Use for system explanations.

Characteristics:

- layered structure
- modular components
- simplified connections
- abstract service blocks

#### Dashboard Illustration

Use for Lumina Studio and monitoring topics.

Characteristics:

- large dashboard panel
- supporting cards
- status indicators
- calm interface
- optional human operator

#### Knowledge Network

Use for semantic relationships and knowledge graphs.

Characteristics:

- readable node clusters
- meaningful connections
- document or concept cards
- no chaotic network density

---

### Step 5: Define the Visual Elements

Select only the elements needed to communicate the main message.

Common Lumina elements:

- document cards
- metadata panels
- search fields
- result cards
- knowledge graph nodes
- semantic clusters
- subject labels
- API cards
- service modules
- workflow steps
- dashboard panels
- review checkpoints
- data flows
- recommendation cards
- abstract assistant panels
- people working with knowledge systems

Avoid including too many elements.

A strong Lumina image is selective.

---

### Step 6: Define the Colour Direction

Use the Lumina colour system.

Default colour direction:

- white as primary background
- ETH Blue as dominant brand colour
- black for structure and contrast
- ETH Petrol for semantic relationships, APIs and data flows
- ETH Grey for secondary UI elements and neutral structures

Use accent colours only when they add meaning:

- ETH Green for validated, successful or completed states
- ETH Purple for advanced AI or semantic intelligence
- ETH Bronze for categories, domains or highlighted subject areas
- ETH Red only for warnings or errors

Avoid rainbow palettes and colourful SaaS-style gradients.

---

### Step 7: Write the Main Prompt

The main prompt should include:

1. image type
2. Lumina topic
3. main message
4. audience or use case
5. composition
6. visual elements
7. colour direction
8. illustration style
9. constraints and avoidances

Use clear and direct language.

Do not make the prompt unnecessarily poetic.

Do not overload the prompt with too many details.

A good prompt is specific enough to guide the image model, but open enough to allow a coherent image.

---

## Main Prompt Template

Use this structure as a starting point:

```text
Create a [aspect ratio / format] modern corporate editorial vector illustration for ETH Lumina about [topic].

The visual should communicate [main message] for [audience/use case].

Use the Lumina visual language: calm, precise, trustworthy, academic, human-centred and knowledge-focused.

Composition: [composition pattern]. The focal point should be [focal point]. Include [main elements]. Show the relationship between [people/knowledge/technology] through [visual metaphor].

Use ETH Blue, black and white as the primary colour basis. Use ETH Petrol and ETH Grey as restrained secondary colours. Use accent colours only if they add semantic meaning.

Style: clean vector shapes, soft geometric forms, rounded UI cards, subtle gradients, restrained shadows, generous whitespace and minimal detail.

Avoid photorealism, heavy outlines, robots, glowing AI brains, cyberpunk aesthetics, binary-code backgrounds, rainbow palettes, cluttered dashboards, real product screenshots and generic AI clichés.
```

---

## Negative Prompt

Always provide a negative prompt.

The negative prompt should protect the Lumina visual identity.

Default negative prompt:

```text
photorealistic, 3D render, anime, childish cartoon, comic exaggeration, thick black outlines, glossy effects, neon sci-fi, cyberpunk, robot, humanoid AI, glowing brain, hologram, binary code background, matrix code, magical sparkles, cluttered dashboard, unreadable text, distorted logos, fake product screenshot, generic stock photo, rainbow palette, overly colourful gradients, chaotic network, server room, data centre, surveillance control room
```

Adjust the negative prompt when needed.

For example, if creating a dashboard illustration, keep `cluttered dashboard` but do not exclude all dashboard elements.

---

## Topic-Specific Prompt Guidance

### Lumina Core

Emphasise:

- trusted foundation
- reusable services
- APIs
- metadata
- semantic service layer
- central platform
- connection between Engine, Studio and Experience

Use composition patterns:

- layered architecture
- central hub
- service platform
- data-to-service flow

Avoid:

- single database icon
- server rooms
- cloud clutter
- black-box AI

---

### Lumina Engine

Emphasise:

- enrichment
- processing
- transformation
- embeddings
- semantic matching
- classification
- reusable outputs
- quality-aware workflows

Use composition patterns:

- enrichment pipeline
- semantic matching scene
- before-and-after structure
- modular service view

Avoid:

- literal engines
- gears
- industrial machinery
- uncontrolled automation

---

### Lumina Studio

Emphasise:

- monitoring
- review
- configuration
- quality assurance
- human-in-the-loop
- transparency
- responsible control

Use composition patterns:

- dashboard workspace
- review queue
- workflow monitoring
- quality overview
- orchestration view

Avoid:

- surveillance dashboards
- dark control rooms
- financial trading screens
- dashboards full of red alerts

---

### Lumina Experience

Emphasise:

- discovery
- semantic search
- recommendations
- research assistance
- knowledge exploration
- user-facing clarity

Use composition patterns:

- discovery interface
- research workspace
- knowledge map
- search journey
- assistant-supported interaction

Avoid:

- generic chatbot
- commercial search engine clone
- shopping recommendation style
- flashy AI assistant

---

### Embedding-Based Subject Indexing

Emphasise:

- bibliographic input
- controlled vocabulary
- semantic matching
- embedding space
- ranked subject candidates
- candidate evidence
- human review
- enriched metadata output
- reusable subject layer

Use composition patterns:

- end-to-end workflow
- semantic matching scene
- candidate evidence view
- human-in-the-loop review
- Lumina data flow positioning

Avoid:

- black-box classifier
- neural network diagram
- robot assigning subjects
- magical automation
- simple keyword search
- purely mathematical vector diagram
- fully autonomous replacement for cataloguers

---

## Audience Adaptation

Adapt the level of detail to the audience.

### Leadership Audience

Use:

- high-level visual story
- strategic value
- clear benefits
- calm hero or concept visual
- minimal technical detail

Avoid:

- detailed implementation structures
- algorithmic details
- dense diagrams

---

### Library Expert Audience

Use:

- metadata
- vocabularies
- subject labels
- review workflows
- evidence
- quality signals
- human judgement

Avoid:

- overpromising automation
- hiding expert review

---

### Technical Audience

Use:

- architecture layers
- APIs
- pipelines
- embeddings
- service modules
- workflow steps
- data flows

Avoid:

- decorative technology imagery
- unnecessary visual complexity

---

### General Academic Audience

Use:

- search
- discovery
- documents
- knowledge connections
- research workflows
- clear user benefit

Avoid:

- internal terminology unless needed

---

## Text and Logos

Do not rely on generated text inside images.

Image models often produce incorrect or unreadable text.

Use abstract text lines or very short labels only.

Important text should be added later in PowerPoint, Figma, HTML or another design tool.

Do not ask the image model to generate the ETH logo or Lumina logo unless explicitly required.

Official logos should usually be added separately in the final design environment.

---

## Prompt Quality Checklist

Before finalising a prompt, check:

- Does the prompt communicate one clear main idea?
- Is the relevant Lumina component or functional area clear?
- Does the prompt centre knowledge, people or library services?
- Is technology supporting the story rather than dominating it?
- Is the composition suitable for the intended medium?
- Are ETH colours used with restraint?
- Are the requested visual elements meaningful?
- Are AI clichés explicitly avoided?
- Is the prompt specific without becoming overloaded?
- Would the resulting image feel like part of the Lumina ecosystem?

If several answers are no, revise the prompt before using it.

---

## Output

A generated prompt should usually be returned together with:

1. concept title
2. visual concept
3. main image prompt
4. negative prompt
5. suggested aspect ratio
6. colour notes
7. design-system check

The exact output format is defined in:

`prompt-system/output-format.md`
