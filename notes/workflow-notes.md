# Workflow Notes

## Goal
Explore ways of keeping generated backgrounds visually consistent across adjacent shots.

## Key questions
- How much can depth guidance help preserve spatial continuity?
- How should reference images be used without overfitting to a single shot?
- How can actor preservation be separated from background generation?

## Current approach
- Generate or guide background separately
- Use simplified layout guidance
- Composite actor after environment generation when needed