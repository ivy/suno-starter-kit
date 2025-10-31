# Agents

This file provides guidance to AI agents when working in this repository.

## Project Overview

This is a music project repository focused on AI-generated music using Suno AI. The project contains documentation and guides for creating effective music prompts and working with AI music generation.

## Repository Structure

- `doc/` - Documentation directory containing guides and references
  - `suno-guide.md` - Comprehensive guide for creating effective Suno AI music prompts, including tips for style descriptions, vocal effects, genre transitions, and prompt optimization

## Key Documentation

The main resource in this repository is the Suno AI guide (`doc/suno-guide.md`) which provides detailed instructions for:
- Optimizing sound descriptions and style prompts
- Using structured section tags in lyrics
- Leveraging punctuation and formatting for vocal effects
- Incorporating special vocal effects and background sounds
- Guiding mood changes and genre transitions
- Iterating and refining music generation prompts

This guide is the primary reference for understanding how to work with Suno AI for music generation in this project.

## Song Writing Workflow

When creating new songs, follow this structured approach:

### 1. Create Song Directory
Start with a descriptive title that summarizes the concept (e.g., `glitchcore-lovesong/`, `cyberpunk-ballad/`, `synthwave-heartbreak/`). Create a new directory with this name.

### 2. High-Level Concept (CONCEPT.md)
Write the overarching concept, theme, and emotional core of the song. Include:
- Central theme or story
- Target emotions and mood
- Musical inspiration or reference points
- Key imagery or metaphors

### 3. Song Structure (STRUCTURE.md)
Break down the lyrical and musical structure:
- Section order (intro, verse, hook, chorus, bridge, outro, etc.)
- Narrative progression and story beats
- Emotional arc and mood transitions
- Key moments and climaxes
- Overall flow and pacing

### 4. Lyrics (LYRICS.txt)
Write the final lyrics using proper Suno formatting:
- Use section annotations: `[Verse]`, `[Chorus]`, `[Bridge]`, etc.
- Add mood/effect annotations: `[softly]`, `[building]`, `[distorted]`
- Use parentheses for backing vocals: `(echo me)`
- Use CAPS for shouting or emphasis
- Use plain text formatting (no Markdown or emphasis)
- Include instrumental sections: `[Instrumental Break]`
- Add vocal effects and transitions between sections

### 5. Sound Description (SOUND.md)
Capture the final production direction without naming specific artists:
- Style summary: concise description of vibe/genre blend and energy (e.g., “classy hard‑bounce hip‑hop with sleek, assertive edge”).
- Tempo/groove: BPM range and rhythmic feel (swing/straight, bounce, double‑time bridge).
- Instrumentation: drums/bass palette, keys/guitar/synth roles, ear‑candy/SFX (keep tasteful and low).
- Vocal approach: delivery tone, doubles/ad‑libs, harmony usage, effects (dry verses, light plate on hooks, call‑and‑response).
- Mix/arrangement notes: punch/width, sidechain, parallel comp, section dynamics (drops, clap break, lift in final hook).
- Compact version: one‑sentence summary for Suno’s style field.
- Tag line: comma‑separated tags capturing the above (no artist references).

This workflow ensures each song has a solid conceptual foundation, clear structure, properly formatted lyrics, and a producer‑ready sound description optimized for Suno AI generation.
