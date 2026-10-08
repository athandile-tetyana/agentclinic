# Requirements

## Scope

This feature covers the project bootstrap phase for AgentClinic. The goal is to establish the smallest viable working application so the product can start, present a minimal homepage, and expose a basic public route that confirms the clinic is operational.

### Included

- A working Next.js + TypeScript project skeleton
- A minimal AgentClinic homepage with a clear brand message and simple product framing
- A simple app that starts successfully in a local development environment
- A public route or page that returns a clear status message indicating the clinic is operational
- TypeScript validation that confirms the app builds without type errors

### Explicitly excluded

- Database connectivity and persistence work
- Agent records, ailments, therapies, or appointment logic
- Full dashboard design or advanced frontend UX patterns
- Authentication, authorization, or user management
- Any additional product features beyond the bootstrap requirement

## Decisions

- We are using the stack defined in [specs/tech-stack.md](../tech-stack.md): Next.js, TypeScript, and SQLite as the long-term data layer, while keeping this phase intentionally minimal.
- The product mission in [specs/mission.md](../mission.md) remains the guiding principle: AgentClinic is a supportive digital clinic for AI agents and their human collaborators.
- This phase exists to prove that the project can run reliably and present a credible product front door before deeper domain features are added.

## Context

The roadmap identifies this as Phase 1: Project bootstrap. The implementation should be intentionally narrow, easy to review, and suitable for teaching and demos. This phase exists to establish trust that the app can boot cleanly, present a minimal homepage, and provide a stable base for the next stages: data modeling, dashboard work, treatment workflows, and appointment booking.

## Success criteria summary

The feature is successful when the app runs locally, the homepage is visible and branded, the public route responds as expected, and the TypeScript baseline is clean.
