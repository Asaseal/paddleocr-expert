# paddleocr-expert

`paddleocr-expert` is a Codex skill for PaddleOCR and PaddleX support. It helps with OCR, PDF parsing, table extraction, deployment, troubleshooting, customer replies, and follow-up records.

This repository is laid out so that the repository root is the skill directory. The required `SKILL.md` is at the top level.

## Install

### Install with Codex skill installer

If the installer supports GitHub repo + path arguments, use:

```bash
python <path-to-install-skill-from-github.py> --repo Asaseal/paddleocr-expert --path . --name paddleocr-expert
```

For agents, the important part is:

- repo: `Asaseal/paddleocr-expert`
- path: `.`
- name: `paddleocr-expert`

### Manual install

1. Clone or download this repository.
2. Copy the repository contents into:

```text
~/.codex/skills/paddleocr-expert/
```

3. Restart Codex so the new skill is discovered.

After install, the destination should contain:

- `SKILL.md`
- `agents/openai.yaml`
- `references/`

## What This Skill Does

- Choose between `PP-OCRv5`, `PP-StructureV3`, `PP-ChatOCRv4`, `table_recognition_v2`, and `PaddleOCR-VL`
- Explain PaddleOCR/PaddleX deployment and serving
- Troubleshoot version mismatch, OOM, Windows/WSL, and backend issues
- Draft ready-to-send WeChat replies for customer support
- Produce structured follow-up records for operations workflows

## Repository

- GitHub: <https://github.com/Asaseal/paddleocr-expert>
- License: `MIT`

## Note For Agents

If a user pastes only the repository URL, treat the repository root as the skill path and install it as `paddleocr-expert`.
