# NEMESIS — Multi-Agent AI Study System
### ATLAS TBS Hackathon

> It doesn't just help you study. It studies you. Then it hunts your weaknesses.

---

## Setup (3 steps)

### 1. Install dependencies
```bash
npm install
```

### 2. Add your Anthropic API key
Edit the `.env` file:
```
VITE_ANTHROPIC_API_KEY=sk-ant-...your-key-here...
```
Get your key at: https://console.anthropic.com/settings/keys

### 3. Run
```bash
npm run dev
```
Opens at **http://localhost:5173**

---

## Agents

| Agent | Role |
|-------|------|
| **SHADOW** | Analyzes your courses and maps a vulnerability graph |
| **ORCHESTRATOR** | Reads your natural language messages and routes to the right agent |
| **NEMESIS** | Generates adversarial questions targeting your exact weak spots |
| **SOCRATES** | Guided dialogue — never gives answers, only asks questions |
| **COACH** | Reads your emotional/cognitive state and adapts |
| **REVIEW** | Spaced repetition — light review for topics due for refresh |
| **EXAM** | Full timed exam simulation across all vulnerable topics |

## Features

- **Vulnerability Graph** — live knowledge map with memory retention rings
- **Forgetting Curve Predictor** — warns you before you forget
- **SM-2 Spaced Repetition** — updates after every answer
- **Orchestrator Chat** — just describe your state in plain language
- **Dynamic Score Updates** — performance changes vulnerability scores in real-time
- **Exam Simulator** — timed, adversarial, full-session

---

## Build for production
```bash
npm run build
```
