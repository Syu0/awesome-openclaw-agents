# Contributing to Awesome OpenClaw Agents

We welcome community agents! Submit yours and get it listed on [crewclaw.com/agents](https://crewclaw.com/agents?utm_source=github&utm_medium=contributing&utm_campaign=submit).

---

## Submit Your Agent

### Option 1: Pull Request (recommended)

**Step 1:** Fork & clone

```bash
git clone https://github.com/YOUR-USERNAME/awesome-openclaw-agents.git
cd awesome-openclaw-agents
```

**Step 2:** Create your agent folder

```
agents/[category]/[agent-name]/SOUL.md
agents/[category]/[agent-name]/README.md
```

Categories: `business`, `creative`, `data`, `development`, `devops`, `ecommerce`, `education`, `finance`, `freelance`, `healthcare`, `hr`, `legal`, `marketing`, `personal`, `productivity`, `real-estate`, `saas`, `security`

**Step 3:** Write your SOUL.md

```markdown
# Agent Name

Brief description of the agent.

## Core Identity

- **Role:** What the agent does
- **Personality:** How it behaves
- **Communication:** How it talks

## Responsibilities

1. **Primary Task**
   - Detail 1
   - Detail 2

## Behavioral Guidelines

### Do:
- Good behavior 1

### Don't:
- Bad behavior 1

## Example Interactions

**User:** Example prompt
**Agent:** Example response
```

**Step 4:** Add a README.md for your agent

```markdown
# Agent Name

> One-line description

## Overview

What this agent does and why it's useful.

## Use Cases

| Request | Output |
|---------|--------|
| Example 1 | Result 1 |

## Author

Created by [@your-username](https://github.com/your-username)
```

**Step 5:** Add entry to `agents.json`

```json
{
  "id": "your-agent-name",
  "category": "category",
  "name": "Your Agent Name",
  "role": "One-line role description",
  "path": "agents/category/your-agent-name/SOUL.md",
  "deploy": "https://crewclaw.com/create-agent"
}
```

**Step 6:** Submit PR

```bash
git add .
git commit -m "Add [AgentName] agent template"
git push origin main
```

### Option 2: Issue

Don't want to set up a PR? Use the **[Submit Your Agent](https://github.com/mergisi/awesome-openclaw-agents/issues/new?template=agent-submission.md)** issue template. Paste your SOUL.md and we'll add it for you.

---

## What Happens After Merge

1. Your agent appears in the [registry](https://github.com/mergisi/awesome-openclaw-agents/tree/main/agents)
2. Listed on [crewclaw.com/agents](https://crewclaw.com/agents?utm_source=github&utm_medium=contributing&utm_campaign=listed) with deploy button
3. You get credited as the author
4. Community can deploy your agent with one click

---

## Other Contributions

### Improve Documentation
Fix typos, clarify instructions, add examples.

### Report Issues
Found a broken link or outdated info? [Open an issue](https://github.com/mergisi/awesome-openclaw-agents/issues/new?template=bug-report.md).

---

## Style Guidelines

- **Agent names:** Descriptive. `CodeReviewer` not `CR`
- **SOUL.md:** Clear headers, example interactions, specific behavioral guidelines
- **README:** Start with name + one-liner, include use case table, credit author

---

## PR Checklist

- [ ] SOUL.md follows the template above
- [ ] README.md included
- [ ] Entry added to `agents.json`
- [ ] Agent tested (works with OpenClaw or similar framework)
- [ ] No broken links

---

## Review Process

1. Maintainer reviews within 48 hours
2. Feedback if changes needed
3. Merged and deployed to crewclaw.com/agents

Questions? [Open a discussion](https://github.com/mergisi/awesome-openclaw-agents/discussions).
