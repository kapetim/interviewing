# interviewing

Interview preparation monorepo — behavioral, architecture, and algorithms.

## Focus

Three pillars:

- **Behavioral** — STAR prep, competency domains, rehearsal.
- **Architecture** — system design examples, patterns, AWS drills, runbooks.
- **Algorithms** — C++17 templates, reference, and accepted contest solutions.

## Sections

| Path | Content |
| --- | --- |
| [`src/behavioral/`](src/behavioral/README.md) | Behavioral prep — STAR, competency domains, rehearsal |
| [`src/architecture/`](src/architecture/README.md) | Architecture examples, patterns, AWS drills, 60-minute runbooks |
| [`src/algorithms/`](src/algorithms/README.md) | C++17 templates, handbook reference, and contest solutions |

## Quick start

```bash
# Lint all markdown (CI)
docker build --target lint -t interviewing-lint -f docker/Dockerfile .
docker run interviewing-lint

# Compile every C++ template / solution
./.github/scripts/compile-algorithms.sh
```
