# README history

## 2026-10-15 — Correct the requirements install example

- User job: a developer copies the dependency-install example into a project that already has a generated requirements.txt file.
- Before: the example split requirements. txt into two tokens. A path check against an owned synthetic project found no requirements. file and observed the extra txt argument.
- Change: use requirements.txt as one argument, add the notes repository purpose, identify the existing Windows activation example, and explain that requirements.txt belongs in the reader project rather than this repository. Link the per-surface history.
- Validation: the identical external command/path checker failed the original spelling and passed the corrected command against a synthetic requirements.txt file. Relative history links were checked against the candidate Git tree.
- Limits: no pip command or package installation was run. Dependency validity, Python versions, actual environments, shell execution and platform support were not certified. Existing command notes, funding configuration and runtime/dependency/CI state were otherwise preserved.
