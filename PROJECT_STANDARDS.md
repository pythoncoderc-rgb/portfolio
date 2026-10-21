# Project Standards

This checklist keeps portfolio projects consistent, well-documented, testable, and appropriately scoped.

## Repository

- Clear project name and one-sentence description
- README with purpose, features, build/run steps, and limitations
- Explicit license
- Useful GitHub topics
- No credentials, tokens, local paths, build outputs, or generated clutter committed

## Code

- Core logic separated from user-interface code where practical
- Functions/classes kept small and purpose-specific
- Error paths handled explicitly
- Safe defaults for commands that can change files
- No unnecessary third-party dependencies

## Verification

- Automated tests for the core behavior
- CI for Python tests or CMake/CTest builds
- Reproducible local commands documented in the README

## Communication

- Claims in the README match the actual implementation
- Small utilities are presented at their real scope, without inflated production claims
- Changelogs/releases are added when a project begins shipping versions
