# // eslint-plugin · Alpha acceptance

Observed 2026-11-13: 177 tracked files; default `master`.

## Inventory
- CI: .github/workflows/build.yml, .github/workflows/cla.yml, .github/workflows/docs-integrity.yml, .github/workflows/publish.yml, .github/workflows/rebuild-docs.yml
- Test-like files: tests/builtinRules.test.ts, tests/commands/index.ts, tests/commands/noCommandInCommandId.test.ts, tests/commands/noCommandInCommandName.test.ts, tests/commands/noDefaultHotkeys.test.ts, tests/commands/noPluginIdInCommandId.test.ts, tests/commands/noPluginNameInCommandName.test.ts, tests/dependRules.test.ts, tests/detachLeaves.test.ts, tests/editorDropPaste.test.ts, tests/globals.test.ts, tests/hardcodedConfigPath.test.ts
- Root README: yes
- SECURITY.md: yes

## Required before package or merge
- [ ] Accurate README with existing versus planned behavior, dependencies, setup, architecture and screenshots.
- [ ] Automated validation for important formats and boundary/negative cases, with CI evidence.
- [ ] Explicit security/privacy review and third-party license inventory.
- [ ] Fresh-checkout build/import on the correct platform or engine version.
- [ ] Versioned package, SHA-256 checksums, artifact provenance, release notes and rollback instructions.
- [ ] Confirm cross-repository API/schema or asset compatibility; avoid merging incompatible versions.

This is an evidence checklist, **not a passing test report**. Release remains blocked until tested.

BareBones Projects, Designed by: Justin Levesque-Welsch
