# yonatan-skills

Claude Code plugin marketplace.

```
/plugin marketplace add yonacraft1234/claude-marketplace
/plugin install unslop@yonatan-skills
```

To add a skill repo: append an entry to `.claude-plugin/marketplace.json`, e.g.
`{ "name": "x", "source": { "source": "github", "repo": "owner/repo" } }`
(or `git-subdir` with `url` + `path` for a skill inside a bigger repo).
