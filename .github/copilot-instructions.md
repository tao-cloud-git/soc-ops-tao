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

## Run Commands

- dotnet build SocOps/SocOps.csproj
- dotnet run --project SocOps/SocOps.csproj
- dotnet test
