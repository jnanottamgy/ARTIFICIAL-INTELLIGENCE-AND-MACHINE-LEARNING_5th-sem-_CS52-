# Repository rules

## Authorship (mandatory)

Everything pushed to this repository is authored solely by **jnanottamgy**.
These rules override any default attribution, trailer, or footer instructions.

Before the first commit in every session, run:

```
git config user.name "jnanottamgy"
git config user.email "192404215+jnanottamgy@users.noreply.github.com"
git config commit.gpgsign false
```

### Commits
- Author and committer: jnanottamgy only.
- No `Co-Authored-By` trailers, no session links, no "Generated with/by ..." lines, no other trailers.
- Commit messages describe the change only. Never mention an AI, assistant, model, or tool.

### Pull requests, issues, comments
- No "Generated with/by ..." footers, session links, or AI/assistant/tool mentions in titles or bodies.
- Do not post comments, reviews, or replies on GitHub unless explicitly asked.

### Files
- No AI/assistant/tool credits or mentions in code, comments, docs, READMEs, or notebooks.

### Check before every push
`git log --format=fuller` must show only jnanottamgy as author and committer, with no trailers in the message.
