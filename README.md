# The Claus Team Social Media Agent System

This folder contains the complete Markdown-based operating manual for two AI agents:

1. **Content Idea Research Agent**
2. **Daily Content Calendar Agent**

These agents are designed for Brad Claus and The Claus Team to create consistent, useful, lead-generating social media content for:

- Facebook
- Instagram
- TikTok

This system assumes Brad will manually post the content. There is no auto-posting workflow included.

## Primary Goal

Create a repeatable system that helps Brad:

- Research content ideas people actually care about
- Turn those ideas into daily social media content
- Build local authority in Schertz, Cibolo, San Antonio, New Braunfels, Garden Ridge, Seguin, Marion, and La Vernia
- Generate conversations, DMs, appointments, and leads
- Keep content aligned with Brad's brand voice
- Avoid generic real estate content
- Use social media as a business development engine, not a random posting habit

## Tools Available

The coding agent may use:

- Claude Code
- Codex
- Firecrawl MCP
- Playwright MCP
- Local Markdown files
- Manual inputs from Brad
- Exported MLS data, if provided
- Exported Follow Up Boss notes, if provided
- Exported social media analytics, if provided

## No Auto-Posting

The agents should not auto-post to Facebook, Instagram, or TikTok.

The agents should create content Brad can review and manually post.

## Recommended Folder Workflow

Use this folder as the system source of truth.

Important: use `13_cta_strategy_guide.md` for all CTA decisions. Do not default to "comment WORD and I’ll send you THIS" style CTAs.

Recommended reading order:

1. `01_business_context.md`
2. `02_brand_voice.md`
3. `03_content_pillars.md`
4. `04_platform_rules.md`
5. `05_research_sources_and_mcp_instructions.md`
6. `06_content_idea_research_agent.md`
7. `07_daily_content_calendar_agent.md`
8. `08_weekly_research_output_template.md`
9. `09_daily_calendar_output_template.md`
10. `10_quality_control_checklist.md`
11. `11_master_prompt_for_codex_or_claude_code.md`
12. `13_cta_strategy_guide.md`

## Output Files the Agents Should Create

The agents should generate Markdown files only.

Recommended output folders:

```text
outputs/
  weekly_research/
    weekly_content_research_YYYY-MM-DD.md

  daily_calendars/
    daily_content_calendar_YYYY-MM-DD.md

  approved_ideas/
    approved_content_ideas.md

  archives/
    posted_content_log.md
```

## Main Agent Relationship

The agents work together:

```text
Content Idea Research Agent
        ↓
weekly_content_research_YYYY-MM-DD.md
        ↓
Daily Content Calendar Agent
        ↓
daily_content_calendar_YYYY-MM-DD.md
        ↓
Brad manually posts content
```

## Important Operating Principle

These agents should save Brad time, not create more work.

The research agent should not dump a giant pile of half-baked ideas.

The daily calendar agent should not create vague content like:

> "Post something about buying a home."

That is useless. A fortune cookie could do that, and it would at least come with lunch.

Each output should be specific enough that Brad can record or post from it immediately.

