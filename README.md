🌐 [Português (BR)](README.pt_BR.md) | [Español](README.es.md)

# Soc Ops

Build better in-person conversations with a game people actually want to play.

**Soc Ops** is a Social Bingo experience powered by **Blazor WebAssembly (.NET 10)**. Players move around the room, find people who match each prompt, and race to complete 5 in a row.

🎮 **[Play the Game](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/)**
• 📚 **[Open the Lab Guide](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/)**
• 🧭 **[Start Workshop Locally](workshop/GUIDE.md)**

---

## Why This Project

- Turns awkward mixers into structured, fun interaction
- Demonstrates real-world Blazor component architecture
- Works as a hands-on lab for GitHub Copilot agent workflows

## What You Can Explore

- Component-driven UI in [SocOps/Components](SocOps/Components)
- Game state and orchestration in [SocOps/Services](SocOps/Services)
- Domain models in [SocOps/Models](SocOps/Models)
- Question dataset in [SocOps/Data/Questions.cs](SocOps/Data/Questions.cs)
- Utility-first styling in [SocOps/wwwroot/css/app.css](SocOps/wwwroot/css/app.css)

---

## Quick Start

### Prerequisites

- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0) or newer

### Run Locally

```bash
cd SocOps
dotnet run
```

App URL: http://localhost:5166

### Build

```bash
cd SocOps
dotnet build
```

### Test

```bash
dotnet test
```

---

## Workshop Path

Follow the guided lab from setup to multi-agent development:

| Part | Focus |
|------|-------|
| [00](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=00-overview) | Overview and checklist |
| [01](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=01-setup) | Setup and context engineering |
| [02](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=02-design) | Design-first frontend |
| [03](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=03-quiz-master) | Custom quiz master |
| [04](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=04-multi-agent) | Multi-agent development |

Offline versions are available in [workshop](workshop).

---

## Codespaces (Optional)

1. Create a repository from this template
2. Open GitHub: Code → Codespaces → Create codespace on main
3. Wait for devcontainer initialization
4. Run:

```bash
cd SocOps
dotnet run
```

---

Deploys automatically to GitHub Pages on push to `main`.
