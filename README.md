# repo-slim

![repo-slim](docs/cover.webp)

Agent skill: keep git repos small. Stop committing build output and safely purge old bulky files from history.

An agent skill from [VIOLINET Tech](https://github.com/Violinet-tech). It is a folder with a `SKILL.md`, written from a real job and the mistakes made on the way. It works in Claude Code and any harness that reads the `SKILL.md` format, and the markdown is readable as plain docs without an agent.

Page: https://violinet-tech.github.io/repo-slim/

## Use it when

a push warns about large files, `.git` is huge, or build output was committed.

## Install

Clone it into your skills folder. The folder name must match the `name:` in `SKILL.md`, which is why it is cloned under that name:

```bash
git clone https://github.com/Violinet-tech/repo-slim ~/.claude/skills/repo-slim
```

For one project only, clone into `.claude/skills/repo-slim` instead.

## What's inside

- `SKILL.md`: the skill

## More skills

See [all VIOLINET Tech skills](https://github.com/orgs/Violinet-tech/repositories?q=topic%3Aagent-skills).

## Contributing

Issues and PRs welcome. Keep it generic: no personal paths, keys or machine addresses.

## License

MIT, see [LICENSE](LICENSE).
