# Conor Bronsdon

I host [Chain of Thought](https://chainofthought.show/?utm_source=github&utm_medium=referral&utm_campaign=repo-readme&utm_content=profile-readme), a podcast about AI infrastructure and the people building it. I also write, consult on AI infrastructure, and build open-source tools for people who work with AI agents. A lot of what's below started as tooling for the show.

<a href="https://github.com/conorbronsdon?tab=followers"><img alt="GitHub followers" src="https://img.shields.io/github/followers/conorbronsdon?style=flat&label=followers&labelColor=1b1712&color=2233ff" /></a>  Follow me here for new tools, practical examples, and what I learn maintaining them.

## Chain of Thought

[![Episodes](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fdashboard.chainofthought.show%2Fdata.json&query=%24.episodes_published&label=episodes&labelColor=1b1712&color=2233ff)](https://chainofthought.show/podcast/?utm_source=github&utm_medium=referral&utm_campaign=repo-readme&utm_content=profile-readme)
[![YouTube subscribers](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fdashboard.chainofthought.show%2Fdata.json&query=%24.youtube_subscribers&label=YouTube%20subscribers&labelColor=1b1712&color=2233ff)](https://www.youtube.com/@ChainOfThoughtAI)
[![Newsletter subscribers](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fdashboard.chainofthought.show%2Fdata.json&query=%24.newsletter_subscribers&label=newsletter%20subscribers&labelColor=1b1712&color=2233ff)](https://newsletter.chainofthought.show/)

Conversations with the builders reasoning through what's changing in AI infrastructure, agents, and evals. Guests have come from NVIDIA, Google DeepMind, Cisco, AMD, MongoDB, Databricks, and Vercel. (The badges above read the show's public stats feed, so they stay current without anyone editing this page.)

[Apple Podcasts](https://podcasts.apple.com/us/podcast/chain-of-thought-ai-agents-infrastructure-engineering/id1776879655) | [Spotify](https://open.spotify.com/show/4axe6uydH3PT0Fy1jemjFT) | [YouTube](https://www.youtube.com/@ChainOfThoughtAI) | [Newsletter](https://newsletter.chainofthought.show/) | [RSS](https://feeds.transistor.fm/chain-of-thought)

The show's tooling is public too:

- [chain-of-thought-podcast-mcp](https://github.com/conorbronsdon/chain-of-thought-podcast-mcp): search and cite every episode transcript from your agent. Point any MCP client at `https://mcp.chainofthought.show/mcp`. No login or API key.
- [podcast-benchmark](https://github.com/conorbronsdon/podcast-benchmark): compare any podcast with its peers on cadence, transcripts, and feed hygiene, using only public data. No download estimates.
- Podcast analytics over MCP: [op3-mcp](https://github.com/conorbronsdon/op3-mcp) (downloads, geography, app share), [apple-podcasts-mcp](https://github.com/conorbronsdon/apple-podcasts-mcp) (plays, followers, per-episode consumption), [yt-analytics-mcp](https://github.com/conorbronsdon/yt-analytics-mcp) (watch time, retention, traffic sources), [gsc-mcp](https://github.com/conorbronsdon/gsc-mcp) (search performance), and [podcastindex-mcp](https://github.com/conorbronsdon/podcastindex-mcp) (search shows, track guest appearances, check feed health).
- [postlint-mcp](https://github.com/conorbronsdon/postlint-mcp): check a social post against each platform's real character limits, the counting an LLM can't do by inspection.

## What I'm building

| | Project | What it does |
| --- | --- | --- |
| Context & memory | [agent-context-os](https://github.com/conorbronsdon/agent-context-os) | Keep identity, projects, decisions, and session handoffs in reviewable Markdown, shared across Claude Code, Codex, and other coding agents. Backed by Git. |
| | [agent-memory-kit](https://github.com/conorbronsdon/agent-memory-kit) | A read-only curator that finds rot and contradictions in agent memory and proposes evidence-cited diffs you review. |
| Check & prove | [ssot-check](https://github.com/conorbronsdon/ssot-check) | Find facts hand-copied across docs that have drifted from their one canonical home. Stdlib CLI, pre-commit hook, and GitHub Action. |
| | [repo-audit](https://github.com/conorbronsdon/repo-audit) | For every claim that something is blocked or guaranteed, find the mechanism and grade it Enforced, Advisory, or Guidance. |
| Write & publish | [avoid-ai-writing](https://github.com/conorbronsdon/avoid-ai-writing) [![stars](https://img.shields.io/github/stars/conorbronsdon/avoid-ai-writing?style=flat&label=%E2%98%85&labelColor=1b1712&color=2233ff)](https://github.com/conorbronsdon/avoid-ai-writing) | Audit and rewrite AI writing patterns with a portable agent skill and a zero-dependency detector. Also a [Chrome extension](https://chromewebstore.google.com/detail/avoid-ai-writing/blgifnkgdfbihjjclpddmjlnidbdihhl) and an [MCP server](https://github.com/conorbronsdon/avoid-ai-writing-mcp). |
| | [substack-mcp](https://github.com/conorbronsdon/substack-mcp) | Work on Substack drafts, Notes, and analytics from an agent. Long-form posts stay drafts; publishing a Note is a separate action. |

More, grouped the way [conorbronsdon.com/builds](https://conorbronsdon.com/builds?utm_source=github&utm_medium=referral&utm_campaign=repo-readme&utm_content=profile-readme) groups them:

- [MCP servers](https://conorbronsdon.com/builds?utm_source=github&utm_medium=referral&utm_campaign=repo-readme&utm_content=profile-readme#mcp-servers): [gws-mcp-server](https://github.com/conorbronsdon/gws-mcp-server) gives agents Gmail, Calendar, Drive, Sheets, Docs, and Tasks through 67 focused tools instead of 400, with side effects declared on every one. Plus the podcast servers above.
- [Agent skills](https://conorbronsdon.com/builds?utm_source=github&utm_medium=referral&utm_campaign=repo-readme&utm_content=profile-readme#agent-skills): [agent-skills](https://github.com/conorbronsdon/agent-skills) (the incubator), [agent-workspace](https://github.com/conorbronsdon/agent-workspace), [agent-skill-builder](https://github.com/conorbronsdon/agent-skill-builder), [eval-integrity](https://github.com/conorbronsdon/eval-integrity), [grokkable-output](https://github.com/conorbronsdon/grokkable-output), [write-like-me](https://github.com/conorbronsdon/write-like-me), [demo-gif-skill](https://github.com/conorbronsdon/demo-gif-skill), and [eunuch-mode](https://github.com/conorbronsdon/eunuch-mode) (deliberately silly).
- [Writing & creator tools](https://conorbronsdon.com/builds?utm_source=github&utm_medium=referral&utm_campaign=repo-readme&utm_content=profile-readme#creator-tools): [ai-tools-for-creators](https://github.com/conorbronsdon/ai-tools-for-creators) and [ai-learning-resources](https://github.com/conorbronsdon/ai-learning-resources), an ordered route from "what is AI?" to building with coding agents.
- [Mojo libraries](https://conorbronsdon.com/builds?utm_source=github&utm_medium=referral&utm_campaign=repo-readme&utm_content=profile-readme#mojo-libraries): eleven pure-Mojo libraries that mirror Python's standard library APIs. Archived and read-only.
- [For fun](https://conorbronsdon.com/builds?utm_source=github&utm_medium=referral&utm_campaign=repo-readme&utm_content=profile-readme#hobby-projects): [The Cold Chair](https://github.com/conorbronsdon/the-cold-chair), a medieval realm sim where a bribable monk's chronicle is the score, and an [Age of Empires II troop calculator](https://conorbronsdon.github.io/aoe2-troop-calculator/).

## About me

Previously built developer ecosystems at [Modular](https://www.modular.com/) ([acquired by Qualcomm](https://www.modular.com/blog/qualcomm-completes-acquisition-of-modular)), [Galileo](https://galileo.ai/) ([acquired by Cisco](https://blogs.cisco.com/news/cisco-announces-the-intent-to-acquire-galileo)), and LinearB. Before that I was an enterprise consultant at Microsoft, and before that I built my own business.

I also write pre-seed and seed angel checks, mostly into AI infrastructure, developer tools, and robotics ([more](https://conorbronsdon.com/angel-investing?utm_source=github&utm_medium=referral&utm_campaign=repo-readme&utm_content=profile-readme)) and keep [ai-angels](https://github.com/conorbronsdon/ai-angels), a community list of active AI angels.

Away from that: Twilight Imperium, Age of Empires II, avid dancer, and a former chess nerd. I live in Tumwater, WA with my wife and our two cats.

[Podcast](https://chainofthought.show/?utm_source=github&utm_medium=referral&utm_campaign=repo-readme&utm_content=profile-readme) | [Consulting](https://conorbronsdon.com/consulting?utm_source=github&utm_medium=referral&utm_campaign=repo-readme&utm_content=profile-readme) | [Writing](https://conorbronsdon.com/?utm_source=github&utm_medium=referral&utm_campaign=repo-readme&utm_content=profile-readme) | [LinkedIn](https://www.linkedin.com/in/conorbronsdon/) | [X](https://x.com/conorbronsdon)
