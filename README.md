# Suno AI Starter Kit

A structured template and workflow for creating AI-generated music with [Suno AI](https://suno.ai), designed to work seamlessly with LLM agents like Claude Code, Cursor, OpenAI Codex, and similar tools.

## What is this?

This starter kit provides a framework for producing high-quality AI-generated music by giving your LLM agent complete context about:

- How to write effective Suno AI prompts
- Structured song creation workflows
- Best practices for lyrics formatting
- Sound design and production direction
- Vocal effects, genre transitions, and mood changes

Instead of repeatedly explaining Suno's quirks and formatting requirements, simply point your AI agent at this repository and it will understand how to help you create music that matches your vision.

## Why use this?

Working with Suno AI involves many subtle techniques - from bracket notation for section tags to punctuation cues for vocal delivery. This starter kit:

- Provides a proven workflow for consistent results
- Includes prompt engineered documentation
- Structures your projects for iteration and refinement
- Enables your AI agent to be an effective music production partner
- Helps you maintain organization across multiple songs

## Project Structure

```
suno-starter-kit/
├── README.md              # This file
├── CLAUDE.md              # Project instructions for AI agents
├── AGENTS.md              # Guidance for AI assistants (same as CLAUDE.md)
├── reference/
│   └── suno-guide.md     # Comprehensive Suno AI prompting guide
└── [song-name]/          # Individual song directories (created per song)
    ├── CONCEPT.md        # High-level theme and emotional core
    ├── STRUCTURE.md      # Song structure and narrative arc
    ├── LYRICS.txt        # Formatted lyrics for Suno
    └── SOUND.md          # Production direction and style tags
```

## The Workflow

When creating a new song, follow this structured five-step process:

### 1. Create Song Directory
Create a descriptive directory name that captures the song concept:
```bash
mkdir glitchcore-lovesong/
cd glitchcore-lovesong/
```

### 2. Write CONCEPT.md
Document the overarching idea:
- Central theme or story
- Target emotions and mood
- Musical inspiration or reference points
- Key imagery or metaphors

### 3. Define STRUCTURE.md
Plan the song's architecture:
- Section order (intro, verse, chorus, bridge, outro)
- Narrative progression and story beats
- Emotional arc and mood transitions
- Key moments and climaxes

### 4. Format LYRICS.txt
Write lyrics using proper Suno formatting:
- Section annotations: `[Verse]`, `[Chorus]`, `[Bridge]`
- Mood/effect annotations: `[softly]`, `[building]`, `[distorted]`
- Backing vocals in parentheses: `(echo me)`
- CAPS for emphasis or shouting
- Instrumental sections: `[Instrumental Break]`

### 5. Describe SOUND.md
Capture production direction without artist names:
- Style summary: vibe, genre blend, energy
- Tempo/groove: BPM range and rhythmic feel
- Instrumentation: drums, bass, keys, synths, effects
- Vocal approach: delivery, doubles, harmonies, effects
- Mix notes: punch, width, dynamics, section transitions
- Compact summary: one-sentence for Suno's style field
- Tag line: comma-separated descriptors

## Quick Start

### For Users
1. Clone this repository
2. Configure your AI agent (Claude Code, Cursor, etc.) to access this directory
3. Tell your agent: "Let's create a new song about [your concept]"
4. Your agent will guide you through the workflow and format everything correctly for Suno

### For AI Agents
This repository includes `CLAUDE.md` and `AGENTS.md` files that provide complete context for assisting with song creation. Key resources:

- **Song Writing Workflow**: Structured five-step process in `CLAUDE.md`
- **Suno Prompting Guide**: Comprehensive techniques in `reference/suno-guide.md`
- **Formatting Rules**: Section tags, vocal effects, punctuation cues
- **Production Tips**: Genre blending, mood transitions, sound effects

When working with users:
1. Follow the workflow in `CLAUDE.md` for new songs
2. Reference `reference/suno-guide.md` for Suno-specific formatting
3. Help iterate on prompts based on generation results
4. Keep all song files organized in dedicated directories

## Key Features of the Suno Guide

The `reference/suno-guide.md` includes detailed techniques for:

- **Style Optimization**: Concise descriptions, weighted tags, scenario references
- **Section Structure**: Bracket notation for verses, choruses, bridges
- **Vocal Effects**: Whispers, screams, layered vocals, backing vocals
- **Punctuation Cues**: Strategic use of commas, ellipses, caps for delivery
- **Sound Effects**: Asterisks for non-vocal sounds, instrumental breaks
- **Mood Transitions**: Mid-song shifts, genre blending, dynamic builds
- **Iteration Strategies**: Testing variations, precise instructions, external polish

## Example Song Structure

```
cyberpunk-ballad/
├── CONCEPT.md
│   Theme: Lost connection in a digital age
│   Mood: Melancholic yet hopeful
│   Reference: Blade Runner aesthetic meets emotional vulnerability
│
├── STRUCTURE.md
│   [Intro] - Ambient synth pad (8 bars)
│   [Verse 1] - Intimate, confessional
│   [Chorus] - Soaring, emotional release
│   [Verse 2] - Building tension
│   [Bridge] - Breakdown, shift to spoken word
│   [Final Chorus] - Full production, layered vocals
│   [Outro] - Return to ambient, fading
│
├── LYRICS.txt
│   [Intro]
│   [Ambient synth wash]
│
│   [Verse 1][softly]
│   Neon reflections on empty streets...
│   ...
│
└── SOUND.md
    Style: Melancholic synthwave with ethereal vocals
    Tempo: 85 BPM, half-time feel
    Instrumentation: Warm analog synths, subtle 808s...
```

## Tips for Best Results

1. **Be Specific**: Clear, concise tags work better than long descriptions
2. **Iterate**: Generate multiple variations and refine your prompts
3. **Use Structure**: Section tags help Suno maintain coherent song flow
4. **Keep It Simple**: Often less is more with style descriptions
5. **Experiment**: Try different combinations of tags and formatting
6. **Polish Externally**: Consider editing in a DAW for final touches

## Contributing

This is a living template. If you discover new Suno techniques or workflow improvements:

1. Test them thoroughly with multiple generations
2. Document the approach clearly
3. Share your findings (GitHub issues/PRs welcome)

## License

ISC License - see [LICENSE.md](LICENSE.md)

## Resources

- [Suno AI Platform](https://suno.ai)
- [Suno Community Wiki](https://sunoai.wiki)
- [r/SunoAI Reddit](https://reddit.com/r/SunoAI)

## Acknowledgments

Built from community knowledge and experimentation. Special thanks to the Suno AI community and a bunch of cool folks on Discord for sharing techniques and discoveries!

---

🎶 **Have fun!** 🎶
