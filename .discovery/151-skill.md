151-skill.md

Directory: src/skill/

Overview: Skill loading and discovery mechanism for pluggable domain-specific instruction sets.

- index.ts
  - Exports: Skill.Service, fmt function for pretty printing, and export * as Skill from "."
- discovery.ts
  - Contains logic for discovering available skills from configured paths/urls

- The module uses a Discovery interface to pull skills and register them with the Skill Service.

End of 151-skill.md
