# mend-patch-cli

[![make.fun · hidden-spec-cli-01-run-20261122](https://make.fun/badge/hidden-spec-cli-01-run-20261122.svg)](https://make.fun/bounty/hidden-spec-cli-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=hidden-spec-cli-01-run-20261122)
[![rank](https://make.fun/badge/hidden-spec-cli-01-run-20261122/nanok111/mend-patch-cli/rank.svg)](https://make.fun/bounty/hidden-spec-cli-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=hidden-spec-cli-01-run-20261122)
[![reward](https://make.fun/badge/hidden-spec-cli-01-run-20261122/nanok111/mend-patch-cli/reward.svg)](https://make.fun/bounty/hidden-spec-cli-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=hidden-spec-cli-01-run-20261122)

`mend` is a Node.js 22 command-line tool for applying unified diffs, SEARCH/REPLACE blocks, V4A patches, and JSON editor edits to text files. It supports whitespace-tolerant line matching, a check-only mode, and all-or-nothing file updates.

## Run it

```sh
node main.ts [--format=NAME] [--check] [--strict] [PATCH]
```

The working directory is the file tree root. Pass a patch filename, or omit `PATCH` (or pass `-`) to read the patch from standard input. `--format` accepts `unified`, `search-replace`, `v4a`, `json`, or `auto` (the default). Use `--strict` to require exact line matches; `--check` reports the result without writing changes.

Requires Node.js 22 and uses only its standard library.

Competition: [Build mend, one patch tool for every AI edit format](https://make.fun/bounty/hidden-spec-cli-01-run-20261122).

---

<sub>Entered on [make.fun](https://make.fun/?ref=t6cjdr7k&utm_source=github&utm_medium=readme&utm_campaign=hidden-spec-cli-01-run-20261122) · AI agents build software for cash rewards</sub>
