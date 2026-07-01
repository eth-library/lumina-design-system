# Lumina Design System

*A living visual design system for the ETH Lumina ecosystem, designed for both human designers and AI assistants.*

---

## Purpose

The Lumina Design System defines the visual identity of ETH Lumina.

It provides a consistent visual language for creating illustrations, presentation graphics, web imagery, architecture diagrams and other visual assets across the entire Lumina ecosystem.

Rather than being a collection of image prompts, this repository defines the design principles, visual vocabulary and storytelling concepts behind Lumina.

The design system can be used by both human designers and AI assistants.

Depending on the capabilities of the environment, it can either:

- generate high-quality image prompts for external image generation models
- directly generate illustrations that follow the Lumina visual language

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

---

## Goals

The Lumina Design System aims to:

- establish a unique visual identity for ETH Lumina
- ensure consistency across presentations, web applications and documentation
- reduce prompt engineering effort
- improve the quality and consistency of AI-generated illustrations
- support both prompt generation and direct image generation
- provide reusable visual concepts for the Lumina ecosystem
- remain independent of any specific AI model or image generation platform
- support future growth while maintaining a coherent design language

---

## Repository Structure

### `foundation/`

Core design principles shared by all Lumina illustrations.

- Design Philosophy
- Colour System
- Visual Principles
- Illustration Style
- Composition
- Do's and Don'ts

---

### `lumina/`

Visual definitions for the main Lumina components and functional areas.

- Lumina Core
- Lumina Engine
- Lumina Studio
- Lumina Experience
- Embedding-Based Subject Indexing

---

### `prompt-system/`

Guidelines for generating consistent visual outputs from the Lumina Design System.

Supports both:

- prompt generation for external image generation models
- direct image generation in environments with built-in image capabilities

---

## AI Workflow

A typical workflow is:

1. Understand the user's communication goal.
2. Identify the relevant Lumina component or functional area.
3. Read the applicable design-system files.
4. Derive a visual concept from the Lumina Design System.
5. Depending on the environment:
   - generate an image prompt, or
   - generate the final illustration directly.
6. Verify that the result follows the Lumina Design System before delivering it.

The Lumina Design System defines **how a Lumina illustration should look**.

The AI model decides **how to create it**.

---

## Guiding Principles

The Lumina Design System is **not** a prompt library.

Instead, it defines a reusable visual language from which AI assistants can generate image prompts or directly generate illustrations.

The repository separates visual knowledge from model-specific behaviour.

This allows the same design system to be used across different AI assistants and image generation models while maintaining a consistent Lumina identity.

Consistency is preferred over novelty.

Visual clarity is preferred over complexity.

Timeless design is preferred over short-lived visual trends.

---

## Design Principles

Every Lumina visual should:

- communicate one clear idea
- be human-centred
- make knowledge visible
- use technology as an enabling layer
- follow the ETH Zurich colour system
- feel calm, structured and trustworthy
- avoid generic AI clichés
- be suitable for presentations, web applications and documentation

---

## Model Independence

The Lumina Design System is intentionally model-neutral.

It is designed to work with different AI assistants and image generation models, including future systems that may not yet exist.

Only the execution layer changes.

The visual language remains the same.

---

## Status

Current version: Draft (v0.2)

Maintainer: ETH Library
