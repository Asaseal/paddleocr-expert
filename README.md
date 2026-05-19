# paddleocr-expert

Open-source Codex skill source for PaddleOCR and PaddleX support.

This repository now uses a more standard skill-repo layout:

```text
paddleocr-expert/
├── LICENSE
├── README.md
└── skills/
    └── paddleocr-expert/
        ├── SKILL.md
        ├── agents/
        └── references/
```

The actual skill lives at:

```text
skills/paddleocr-expert
```

## Quick Install

### For humans

Clone or download this repository, then copy:

```text
skills/paddleocr-expert
```

into:

```text
~/.codex/skills/paddleocr-expert/
```

Restart Codex after copying.

### For Codex skill installer

Use:

```bash
python <path-to-install-skill-from-github.py> --repo Asaseal/paddleocr-expert --path skills/paddleocr-expert
```

## Copy-Paste Agent Install Instruction

If you want to hand this repo to another agent, give it this exact instruction:

```text
Install the Codex skill from GitHub repo Asaseal/paddleocr-expert. The skill path inside the repo is skills/paddleocr-expert. Install it with the skill name paddleocr-expert.
```

Or if the agent works better with a URL:

```text
Install the Codex skill from https://github.com/Asaseal/paddleocr-expert . The skill directory inside the repo is skills/paddleocr-expert. Use paddleocr-expert as the installed skill name.
```

## What This Skill Does

- Choose between `PP-OCRv5`, `PP-StructureV3`, `PP-ChatOCRv4`, `table_recognition_v2`, and `PaddleOCR-VL`
- Explain PaddleOCR/PaddleX deployment and serving
- Troubleshoot version mismatch, OOM, Windows/WSL, and backend issues
- Draft ready-to-send WeChat replies for customer support
- Produce structured follow-up records for operations workflows

## Repository Facts

- GitHub: <https://github.com/Asaseal/paddleocr-expert>
- Skill path: `skills/paddleocr-expert`
- Install name: `paddleocr-expert`
- License: `MIT`
