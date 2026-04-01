# my-mbti

An OpenClaw MBTI style-switching skill with support for single-type mode, mixed personality combinations, scenario-based recommendations, and user-friendly onboarding prompts.

## What It Does

`my-mbti` lets the assistant change its response style based on MBTI-inspired communication modes.

It supports:
- single personality mode (for example: `INTJ`)
- hybrid mode (for example: `ISFJ+ISTJ`)
- conflict handling for mixed combinations
- scenario-based recommendations
- user-facing onboarding prompts
- side-by-side comparison responses

## Repository Structure

```text
SKILL.md
references/
  index.md
  INTJ.md
  INTP.md
  ENTJ.md
  ENTP.md
  INFJ.md
  INFP.md
  ENFJ.md
  ENFP.md
  ISTJ.md
  ISFJ.md
  ESTJ.md
  ESFJ.md
  ISTP.md
  ISFP.md
  ESTP.md
  ESFP.md
scripts/
  extract_mbti_pdfs.py
  switch_style_hint.txt
```

## Main Features

### 1. Single-Type Switching
Examples:
- `INTJ`
- `ENFP`
- `ISFJ`

### 2. Hybrid Personality Combinations
Examples:
- `ISFJ+ISTJ`
- `INTJ+ENFP`
- `INFJ+ENTJ`

### 3. Scenario-Based Recommendation
The skill can recommend personality styles based on the user's preferred experience, communication style, or work context.

### 4. Conflict Handling Rules
When the user mixes multiple personality types, the skill keeps the first type as the main frame and uses later types as supporting modifiers.

## Usage

Place this repository into an OpenClaw skills directory or install it as part of your local skill collection, then use the patterns defined in `SKILL.md`.

## Notes

This skill is designed as a practical communication-style tool, not as a personality diagnosis system.
