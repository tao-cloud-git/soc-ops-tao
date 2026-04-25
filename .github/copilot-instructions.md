# Copilot Workspace Instructions

## Mandatory Development Checklist

Before proposing or finalizing code changes, always run and report:

- [ ] Lint: dotnet format --verify-no-changes SocOps/SocOps.csproj
- [ ] Build: dotnet build SocOps/SocOps.csproj
- [ ] Test: dotnet test

If a step fails or is not applicable, explain why and summarize the error.

## Project Snapshot

SocOps is a Blazor WebAssembly app (.NET 10) for a social bingo game.

## Key Paths

- SocOps/Components: UI screens and board components
- SocOps/Services: game orchestration and bingo rules
- SocOps/Models: game state and domain models
- SocOps/Data: static question data
- SocOps/wwwroot/css/app.css: utility CSS classes

## Working Rules

- Keep changes focused; avoid broad refactors unless requested.
- Follow existing C# conventions (PascalCase for public members).
- Put business logic in services, not directly in components.
- Reuse utility classes from app.css before adding new styles.

## Design Guide

- Preserve the existing visual language unless the task explicitly asks for a redesign.
- Favor bold, intentional interfaces over generic layouts; choose a clear visual direction before adding styles.
- Reuse utility classes from SocOps/wwwroot/css/app.css first, and add new utilities only when the existing set cannot express the design cleanly.
- Define reusable colors, spacing, and surface treatments with CSS variables when introducing new styling patterns.
- Use expressive typography and strong contrast, but keep readability and mobile responsiveness intact.
- Prefer subtle, purposeful motion that supports hierarchy or feedback instead of decorative animation.
- Keep component markup clean by moving reusable presentation rules into CSS rather than duplicating long class combinations everywhere.

## Run Commands

- dotnet build SocOps/SocOps.csproj
- dotnet run --project SocOps/SocOps.csproj
- dotnet test
