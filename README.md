# agents-definitions

This repository stores structured agent definition files for personal projects. It is organized into domain-specific folders and includes a meta-agent design template for creating clear, single-purpose agent definitions.

## Repository structure

- `engineering/` — placeholder directory for engineering-focused agent definitions.
- `finance/` — placeholder directory for finance-focused agent definitions.
- `health/` — placeholder directory for health-focused agent definitions.
- `meta/agents-designer.md` — a meta-agent definition describing the persona, objectives, workflow, constraints, and output format used to design reliable agent specifications.

## Purpose

The repository is intended to capture reusable, category-aligned agent definitions and to document the design process used to create them. Each agent definition should be:

- single-purpose
- explicit about inputs and outputs
- unambiguous and directly implementable
- privacy-aware for sensitive domains

## Current contents

- `meta/agents-designer.md` contains the Meta-Agent persona and design workflow for translating vague user intent into executable agent definitions.
- Domain folders are currently empty placeholders for future agent definitions.

## How to use

1. Add a new agent definition file to the appropriate domain folder.
2. Follow the `agents-designer.md` output format to define:
   - name, purpose, persona, objectives, workflow, inputs, outputs, constraints, and validation test case.
3. Keep each agent focused on one clear task and avoid mixing responsibilities.

## Notes

This repo is not a runtime implementation; it is a library of agent definition documents and design guidance.
