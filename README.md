# claude-code-skills

A growing collection of Claude Code skills — meta utilities for building with Claude, GTM outreach drafters, and polish tools.

## Install

```bash
git clone https://github.com/omarrns/claude-code-skills
```

Then symlink any skill you want into `~/.claude/skills/`:

```bash
ln -s $(pwd)/claude-code-skills/skills/create-prompt ~/.claude/skills/create-prompt
ln -s $(pwd)/claude-code-skills/skills/create-skill ~/.claude/skills/create-skill
# etc.
```

Or run **`/welcome`** to get an interactive setup for the GTM email skills specifically.

## Skills

### Claude Developer Tools

- `create-prompt` — interactive interview that generates a production-quality prompt for the Claude API, Agent SDK, or any LLM system, following Anthropic's prompting best practices
- `create-skill` — interactive interview that generates a polished `SKILL.md` for Claude Code, covering role, tools, instructions, output format, and examples

### GTM Cold Email

**Setup**

- `welcome` — interviews you, drafts `config/sender-profile.md`, and installs the email skills

**Drafters** (pick one based on recipient)

- `email-founder` — cold emails to founders/CEOs (product-user or ecosystem-peer frame)
- `email-growth-leader` — cold emails to VPs/Heads of Growth (stage-matched builder frame)
- `email-hiring-manager` — JD-anchored fit emails for role-specific outreach
- `pick-frame` — router that selects the right drafter given recipient + sender profile

**Polish**

- `humanize` — strips AI-tells and rewrites in your voice
- `story-consistency` — fact-checks drafts against your sender profile

## License

MIT
