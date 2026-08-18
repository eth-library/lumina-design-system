# Lumina Design System

*A living visual design system for the ETH Lumina ecosystem, designed for both human designers and AI assistants.*

---

## Purpose

The Lumina Design System defines the visual identity of ETH Lumina.

It provides a consistent visual language for creating illustrations, presentation graphics, web imagery, architecture diagrams and other visual assets across the Lumina ecosystem.

Rather than being a collection of fixed image prompts, this repository defines the design principles, visual vocabulary, composition rules and storytelling concepts behind Lumina.

The design system can be used by both human designers and AI assistants.

Depending on the capabilities of the environment, it can either:

- generate image prompts for external image-generation models
- directly generate illustrations that follow the Lumina visual language
- support the review of existing visuals for Lumina consistency

The design system itself remains model-neutral and serves as the single source of truth for Lumina's visual identity.

---

## Design Philosophy

ETH Lumina represents trustworthy, human-centred Artificial Intelligence for academic libraries.

The visual language should communicate:

- knowledge
- trust
- clarity
- collaboration
- semantic understanding
- innovation
- academic excellence

Technology should always support the story.

People, knowledge and library services remain the protagonists.

Lumina should feel like a modern research university and digital library environment rather than a generic technology company.

---

## Signature Visual Style

Lumina uses a **hybrid editorial illustration style**.

The visual language deliberately combines two levels of realism:

### People

Preferred Lumina people style: editorial illustrated humans with subtle naturalistic depth, not photorealistic, not flat vector.

Preferred human rendering is:

- editorial illustrated humans with subtle naturalistic depth
- authentic facial proportions
- believable expressions and gestures
- smooth skin shading without photographic pores
- simplified hair masses with restrained detail
- clean clothing folds with reduced fabric microtexture
- natural hands, but simplified shading
- clearly not photographic, clearly not flat vector

People should wear **casual academic clothing**, for example:

- sweaters
- knitwear
- hoodies
- casual shirts
- jeans
- chinos
- sneakers
- simple jackets

Avoid formal business clothing, staged corporate poses and generic stock-photo aesthetics.

### Environments and visual systems

Everything surrounding the people remains clearly **editorial and illustrative**.

This includes:

- interfaces
- dashboards
- furniture
- architecture
- books
- documents
- metadata cards
- knowledge graphs
- workflow elements
- background environments

These elements should use:

- simplified geometric forms
- crisp edges
- restrained gradients
- soft shadows
- calm colour compositions
- generous whitespace
- medium detail
- abstract rather than realistic interfaces

The contrast between realistic people and illustrated surroundings is intentional.

**People represent human expertise, judgement and responsibility.  
The illustrated environment represents knowledge structures, systems and digital services.**

This hybrid contrast is a defining characteristic of the Lumina visual identity.

---

## Goals

The Lumina Design System aims to:

- establish a unique visual identity for ETH Lumina
- ensure consistency across presentations, web applications and documentation
- reduce prompt-engineering effort
- improve the quality and consistency of AI-generated illustrations
- support both prompt generation and direct image generation
- provide reusable visual concepts for the Lumina ecosystem
- remain independent of any specific AI model or image-generation platform
- support future growth while maintaining a coherent visual language

---

## Core Visual Principles

Every Lumina visual should:

- communicate one clear idea
- be human-centred
- make knowledge visible
- use technology as an enabling layer
- follow the ETH Zurich colour system
- feel calm, structured and trustworthy
- use whitespace actively
- use colour with restraint
- visualise relationships purposefully
- avoid generic AI clichés
- be suitable for presentations, web applications and documentation

Complex ideas should be simplified through meaningful visual relationships rather than visual noise.

---

## Colour System

The Lumina colour system is based on the ETH Zurich Corporate Design palette.

The primary visual identity is built around:

- **ETH Blue** `#215CAF`
- **Black** `#000000`
- **White** `#FFFFFF`

Supporting colours:

- **ETH Petrol** `#007894` for APIs, semantic relationships, metadata structures and data flows
- **ETH Grey** `#6F6F6F` for secondary interface elements and neutral structures

Semantic accent colours may be used sparingly:

- **ETH Green** `#627313` for validated, successful or completed states
- **ETH Purple** `#A7117A` for advanced AI capabilities or semantic intelligence
- **ETH Bronze** `#8E6713` for categorisation and selected knowledge domains
- **ETH Red** `#B7352D` only for warnings, errors and critical states

A Lumina visual should feel calm before it feels colourful.

---

## Repository Structure

### `foundation/`

Core design principles shared by all Lumina visuals.

- `philosophy.md` — design philosophy and human-centred AI perspective
- `colours.md` — ETH-aligned colour system
- `visual-principles.md` — visual grammar and design priorities
- `illustration-style.md` — editorial illustration style and hybrid human rendering
- `composition.md` — composition patterns and layout rules
- `dos-and-donts.md` — practical visual review guidance

---

### `lumina/`

Visual definitions for the main Lumina components and functional areas.

- `lumina-core.md`
- `lumina-engine.md`
- `lumina-studio.md`
- `lumina-experience.md`
- `embedding-based-subject-indexing.md`

These files define topic-specific visual stories, preferred elements and things to avoid.

---

### `prompt-system/`

Guidelines for turning the design system into consistent visual outputs.

Includes:

- prompt-generation workflow
- composition selection
- rendering guidance
- hybrid human-rendering instructions
- negative-prompt guidance
- output formatting
- design-system checks

The prompt system supports both:

- prompt generation for external image-generation models
- direct image generation in environments with built-in image capabilities

---

## AI Workflow

A typical AI-assisted workflow is:

1. Understand the communication goal, audience and intended medium.
2. Identify the relevant Lumina component or functional area.
3. Read the applicable files in `foundation/`.
4. Read the relevant file in `lumina/`, when applicable.
5. Apply the guidance in `prompt-system/`.
6. Derive one clear visual concept.
7. Select an appropriate composition pattern.
8. Apply the Lumina colour system.
9. Apply the hybrid rendering rule:
   - people are editorial illustrated humans with subtle naturalistic depth
   - people are not photographic and not flat vector
   - environments, interfaces and objects remain clearly editorially illustrated
10. Generate the image prompt or final illustration.
11. Verify the result against the Lumina Design System before delivery.

The Lumina Design System defines **how a Lumina visual should look**.

The AI model decides **how to create it**.

---

## Hybrid Rendering Rule for AI Assistants

When people appear in a Lumina illustration:

**Render people as editorial illustrated humans with subtle naturalistic depth.**

Use:

- authentic facial proportions
- smooth skin shading without photographic pores
- simplified hair masses with restrained detail
- natural hands and gestures with simplified shading
- clean clothing folds with reduced fabric microtexture
- soft natural lighting
- casual academic clothing
- a clearly illustrated appearance, not a photographic one

At the same time:

**Keep the surrounding visual world clearly illustrated.**

Do not extend photorealism to:

- architecture
- interfaces
- dashboards
- furniture
- documents
- metadata cards
- diagrams
- knowledge graphs
- background environments

Avoid turning the complete image into a photograph.

The contrast between the person and the illustrated environment should remain visible while lighting, perspective and colour atmosphere keep the scene coherent.

---

## Interfaces

Interfaces are supporting elements.

They should help explain concepts without looking like screenshots of finished products.

Prefer:

- simplified search interfaces
- metadata cards
- workflow panels
- dashboards
- result clusters
- semantic graphs
- review panels
- service cards

Avoid:

- realistic product screenshots
- dense dashboards
- excessive UI components
- unreadable generated text

Important text and official logos should usually be added later in the final design environment.

---

## People

People represent:

- expertise
- judgement
- interpretation
- responsibility
- collaboration

Suitable roles include:

- librarians
- researchers
- students
- developers
- data specialists
- domain experts
- service owners
- PhD candidates
- interdisciplinary collaborators

People should appear:

- focused
- thoughtful
- curious
- calm
- engaged
- collaborative

Avoid using people as decoration only.

---

## Knowledge Representation

Knowledge should remain tangible.

Prefer visual elements such as:

- books
- documents
- metadata
- collections
- notes
- research outputs
- semantic relationships
- subject labels
- controlled visual clusters
- reusable service layers

Technology should help organise, enrich, connect and reuse knowledge.

---

## AI Representation

AI should remain an enabling layer rather than a visual protagonist.

Represent AI through:

- semantic relationships
- recommendations
- enriched metadata
- intelligent workflows
- contextual guidance
- pattern recognition
- better connections between knowledge objects

Avoid:

- humanoid robots
- glowing brains
- holograms
- magical effects
- binary-code backgrounds
- cyberpunk aesthetics
- uncontrolled automation narratives

---

## Composition

Lumina compositions should feel calm, intentional and easy to understand.

Prefer:

- one clear focal point
- two or three supporting elements
- generous whitespace
- readable visual hierarchy
- purposeful relationship lines
- balanced, often asymmetrical layouts
- quiet backgrounds

Common composition patterns include:

- presentation hero
- web hero
- concept explainer
- workflow or pipeline
- architecture diagram
- dashboard illustration
- knowledge network

The composition should reduce complexity, not amplify it.

---

## Guiding Principles

The Lumina Design System is **not** a prompt library.

It defines a reusable visual language from which AI assistants and human designers can create new visuals.

The repository separates visual knowledge from model-specific execution.

This allows the same design system to be used across different AI assistants and image-generation models while maintaining a consistent Lumina identity.

Consistency is preferred over novelty.

Visual clarity is preferred over complexity.

Timeless design is preferred over short-lived visual trends.

Human expertise remains visible.

---

## Model Independence

The Lumina Design System is intentionally model-neutral.

It is designed to work with different AI assistants and image-generation models, including future systems that may not yet exist.

Only the execution layer changes.

The visual language remains the same.

---

## Quick Design Check

Before using or publishing a Lumina visual, ask:

- Is there one clear main idea?
- Are knowledge, people or library services central?
- Does technology support the story rather than dominate it?
- Are people editorial illustrated humans with subtle naturalistic depth when present?
- Does the surrounding environment remain editorially illustrated?
- Are casual academic clothing and natural poses used?
- Are ETH Blue, black and white the primary colour basis?
- Are secondary colours used with restraint?
- Is the composition calm and readable?
- Are relationships meaningful and easy to follow?
- Are generic AI clichés avoided?
- Does the result feel like part of the Lumina ecosystem?

If several answers are no, simplify and revise the visual.

---

## Status

Current version: Draft (v0.2)

Maintainer: ETH Library
