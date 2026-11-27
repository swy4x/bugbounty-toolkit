# swy4x Bug Bounty Toolkit

A work-in-progress collection of web security research utilities and command templates by **swy4x**.

## Project files

- `index.html` — Advanced Bug Bounty Toolkit command hub.
- `tools-hub.html` — Original multi-tool hub, rebranded from P1R4T3RX to swy4x.

## Status

This repository is an early development baseline. Some command examples still need validation, dependency checks, safer input handling, and clearer output management. The toolkit currently displays/copies shell command templates; the HTML pages do not execute scans themselves.

## Safe use

Use only on domains and applications you own or have explicit written permission to test. Confirm the program's scope and rules before running any active testing commands. Do not run templates unchanged: review each command, replace placeholders, and understand its impact first.

## Roadmap

- Move target input and **Generate Commands** to the top of the workflow.
- Audit every command for correctness, usefulness, dependencies, and safe defaults.
- Remove fake or unsupported tools and misleading functionality.
- Generate commands from validated target and configuration inputs.
- Improve reporting, error handling, accessibility, and responsive UI.

## License

See [LICENSE](LICENSE).
