<h1 align="center">Hey, I'm Conor 👋</h1>

<p align="center">
Host of <a href="https://chainofthought.show">Chain of Thought</a> · Technical Ecosystem Lead at <a href="https://www.modular.com/">Modular</a> · <a href="https://conorbronsdon.com/angel-investing">Angel Investor</a>
<br/>
<a href="https://github.com/conorbronsdon"><img src="https://img.shields.io/github/followers/conorbronsdon?label=Follow&style=social" alt="Follow" /></a>
</p>

<p align="center">
<em>The views expressed on this account are my own and have not been reviewed or approved by Modular.</em>
</p>

---

By day, Technical Ecosystem Lead at [Modular](https://www.modular.com/), working on the [Mojo](https://github.com/modular/modular) programming language and [MAX](https://www.modular.com/max) inference platform. Before that, developer ecosystems at [Galileo](https://galileo.ai/) ([acquired by Cisco](https://blogs.cisco.com/news/Cisco-announces-the-intent-to-acquire-galileo)) and [LinearB](https://linearb.io/), enterprise consulting at Microsoft, and a career in political organizing before any of it.

- 🎙️ 60+ episodes of [Chain of Thought](https://chainofthought.show) shipped
- 💰 [Angel investor](https://conorbronsdon.com/angel-investing) in AI infrastructure, dev tools, and robotics
- 🎲 Avid Twilight Imperium and [Age of Empires II](https://github.com/conorbronsdon/aoe2-troop-calculator) player, former chess team nerd
- 📫 Best way to reach me: [LinkedIn](https://www.linkedin.com/in/conorbronsdon/)

### Chain of Thought

[![Website](https://img.shields.io/badge/Website-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)](https://chainofthought.show) [![Apple Podcasts](https://img.shields.io/badge/Apple_Podcasts-9933CC?style=for-the-badge&logo=apple-podcasts&logoColor=white)](https://podcasts.apple.com/us/podcast/chain-of-thought/id1776879655) [![Spotify](https://img.shields.io/badge/Spotify-1DB954?style=for-the-badge&logo=spotify&logoColor=white)](https://open.spotify.com/show/4axe6uydH3PT0Fy1jemjFT) [![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@ChainOfThoughtAI) [![RSS](https://img.shields.io/badge/RSS-FFA500?style=for-the-badge&logo=rss&logoColor=white)](https://feeds.transistor.fm/chain-of-thought)

[Chain of Thought](https://chainofthought.show) is a podcast about AI infrastructure and the people building it. Guests include [Chip Huyen](https://www.chainofthought.show/podcast/5-practical-lessons-for-genai-evals-chip-huyen-and-vivienne-zhang/), [Logan Kilpatrick](https://www.chainofthought.show/podcast/12-the-making-of-gemini-2-0-deepminds-approach-to-ai-development-and-deployment-logan-kilpatr/) of [Google DeepMind](https://newsletter.chainofthought.show/p/chain-of-thought-the-future-of-ai), plus leaders and founders from [NVIDIA](https://www.chainofthought.show/podcast/5-practical-lessons-for-genai-evals-chip-huyen-and-vivienne-zhang/), [AMD](https://www.chainofthought.show/podcast/28-amds-challenge-to-nvidia-the-open-ecosystem-bet-anush-elangovan-and-sharon-zhou/), [Databricks](https://www.chainofthought.show/podcast/22-ais-two-extremes-foundations-and-the-frontier-databricks-denny-lee/), [Poolside](https://www.chainofthought.show/podcast/23-first-code-then-agi-softwares-event-horizon-with-poolside-founders-jason-warner-and-eiso-k/), [Liquid AI](https://www.chainofthought.show/podcast/43-beyond-transformers-how-liquid-ai-is-rethinking-llm-architecture-maxime-labonne/), [Fireworks](https://www.chainofthought.show/podcast/42-architecting-ai-agents-the-shift-from-models-to-systems-aishwarya-srinivasan/), [Vercel](https://www.chainofthought.show/podcast/39-vercels-playbook-for-ai-agents-from-vibe-check-to-production-malte-ubl/), and many others.

#### Newsletter: 

- [Block Cut 4,000 Jobs and Blamed AI. The Truth is More Complicated.](https://newsletter.chainofthought.show/p/block-cut-4000-jobs-and-blamed-ai)
- [He Built an AI Coworker to Run 90% of his Day](https://newsletter.chainofthought.show/p/he-named-his-ai-coworker-marvin-it)
- [What Atlassian's $1B DX Acquisition Means for the Developer Productivity Market](https://newsletter.chainofthought.show/p/what-dxs-1b-acquisition-means-for)
- [The Rise of Tireless Digital Employees](https://newsletter.chainofthought.show/p/the-rise-of-tireless-digital-employees)
- [2024 Is the Year GenAI Code Hits Adolescence](https://devinterrupted.substack.com/p/2024-is-the-year-genai-code-hits)
- [The Problem with Perfectionism](https://newsletter.chainofthought.show/p/the-problem-with-perfectionism)

### 🔥 Mojo libraries

Pure-Mojo libraries that mirror the Python stdlib APIs developers already know, filling ecosystem gaps for the [Mojo](https://github.com/modular/modular) language. No Python dependencies, no FFI unless the job demands it. Each ships with tests anchored to an external ground truth (official spec suites, byte-for-byte Python parity, real-world corpora).

| | Repo | Python parallel | What it does |
|---|------|-----------------|-------------|
| 📡 | [mojo-feed](https://github.com/conorbronsdon/mojo-feed) | `feedparser` | RSS/Atom/JSON Feed parser — every syndication format since 1999, 138/138 real-world corpus, 130+ MB/s |
| 📝 | [mojo-markdown](https://github.com/conorbronsdon/mojo-markdown) | `markdown` | CommonMark parser + HTML renderer — 98.6% spec conformance, 132/132 on emphasis |
| 📄 | [mojo-html](https://github.com/conorbronsdon/mojo-html) | `readability` | Liberal HTML parser + readability extraction — Mozilla-derived scoring, paywall confidence gate |
| 🌳 | [mojo-xml](https://github.com/conorbronsdon/mojo-xml) | `xml.etree` | General-purpose XML — ElementTree-shaped DOM, scoped namespaces, 14/14 byte-match vs CPython `xml.etree`, 6,000-iter fuzz |
| 🎙 | [mojo-captions](https://github.com/conorbronsdon/mojo-captions) | — | SRT/WebVTT transcript parser — speakers, voice spans, round-trip serialization, clip windows |
| 🔤 | [mojo-unicodedata](https://github.com/conorbronsdon/mojo-unicodedata) | `unicodedata` | Unicode normalization (NFC/NFD/NFKC/NFKD) + casefold — 20,034/20,034 official conformance |
| 🔗 | [mojo-url](https://github.com/conorbronsdon/mojo-url) | `urllib.parse` | URL parsing, building, and query-string encoding — 161/161 Python byte-match, full RFC 3986 urljoin conformance |
| 📐 | [mojo-diff](https://github.com/conorbronsdon/mojo-diff) | `difflib` | Myers text diff + unified_diff — byte-for-byte match with Python's output |
| 🧩 | [mojo-template](https://github.com/conorbronsdon/mojo-template) | `jinja2` | Standalone jinja-flavored template engine — autoescape, 43/43 jinja2 parity |
| 📦 | [mojo-tar](https://github.com/conorbronsdon/mojo-tar) | `tarfile` | tar archive reader/writer — ustar/GNU/pax, GNU-tar byte-identical interop |
| 🗄️ | [mojo-redis](https://github.com/conorbronsdon/mojo-redis) | `redis-py` | RESP2 Redis client — live-server tested, hardened against hostile replies |

### Open projects

| | Repo | What it does | |
|---|------|-------------|---|
| ✍️ | [avoid-ai-writing](https://github.com/conorbronsdon/avoid-ai-writing) | Open-source AI writing detector & rewriter for Claude Code, Cowork, OpenClaw & Cursor. 49 pattern categories, 109-entry replacement table, two-pass rewrite, zero-dep detector engine. | [![Stars](https://img.shields.io/github/stars/conorbronsdon/avoid-ai-writing?style=social)](https://github.com/conorbronsdon/avoid-ai-writing) |
| 🧩 | [claude-context-os](https://github.com/conorbronsdon/claude-context-os) | An operating system for your Claude context — versioned files, self-curating memory, /start→/end loop | [![Stars](https://img.shields.io/github/stars/conorbronsdon/claude-context-os?style=social)](https://github.com/conorbronsdon/claude-context-os) |
| 📧 | [gws-mcp-server](https://github.com/conorbronsdon/gws-mcp-server) | Google Workspace for AI agents: Gmail, Calendar, Drive, Sheets, Docs, and Tasks as 41 curated MCP tools on the official gws CLI | [![Stars](https://img.shields.io/github/stars/conorbronsdon/gws-mcp-server?style=social)](https://github.com/conorbronsdon/gws-mcp-server) |
| 🛠️ | [claude-code-skills](https://github.com/conorbronsdon/claude-code-skills) | Nine production-tested Claude Code skills: session memory, multi-agent code review, eval integrity, SSOT checks, drift reconciliation, worktree recovery, skill scaffolding, and more | [![Stars](https://img.shields.io/github/stars/conorbronsdon/claude-code-skills?style=social)](https://github.com/conorbronsdon/claude-code-skills) |
| 🎶 | [track-finder](https://github.com/conorbronsdon/track-finder) | Paste or import a tracklist, get SoundCloud/Spotify/YouTube/Apple Music (your choice!) search links for every track | [![Stars](https://img.shields.io/github/stars/conorbronsdon/track-finder?style=social)](https://github.com/conorbronsdon/track-finder) |
| 🔄 | [wrekenfile-converter](https://github.com/conorbronsdon/wrekenfile-converter) | File format converter for Wreken spec ([Swytchcode](https://www.swytchcode.com)) | [![Stars](https://img.shields.io/github/stars/conorbronsdon/wrekenfile-converter?style=social)](https://github.com/conorbronsdon/wrekenfile-converter) |
| 🏰 | [aoe2-troop-calculator](https://github.com/conorbronsdon/aoe2-troop-calculator) | Age of Empires II troop calculator for quick army composition and cost math, built for AOE2: DE | [![Stars](https://img.shields.io/github/stars/conorbronsdon/aoe2-troop-calculator?style=social)](https://github.com/conorbronsdon/aoe2-troop-calculator) |
| 🎯 | [ai-tools-for-creators](https://github.com/conorbronsdon/ai-tools-for-creators) | Curated AI skills, MCP servers, and workflow tools for creators | [![Stars](https://img.shields.io/github/stars/conorbronsdon/ai-tools-for-creators?style=social&cacheSeconds=3600)](https://github.com/conorbronsdon/ai-tools-for-creators) |
| 📚 | [ai-learning-resources](https://github.com/conorbronsdon/ai-learning-resources) | Curated learning path from "what is AI?" to building with Claude Code | [![Stars](https://img.shields.io/github/stars/conorbronsdon/ai-learning-resources?style=social)](https://github.com/conorbronsdon/ai-learning-resources) |
| 📰 | [substack-mcp](https://github.com/conorbronsdon/substack-mcp) | MCP server for Substack: posts are draft-only by design, short-form Notes publish immediately | [![Stars](https://img.shields.io/github/stars/conorbronsdon/substack-mcp?style=social)](https://github.com/conorbronsdon/substack-mcp) |
| 🎙 | [podcastindex-mcp](https://github.com/conorbronsdon/podcastindex-mcp) | MCP server for the Podcast Index API: use it to search podcasts, track appearances, monitor trending shows, check feed health, etc. | [![Stars](https://img.shields.io/github/stars/conorbronsdon/podcastindex-mcp?style=social)](https://github.com/conorbronsdon/podcastindex-mcp) |
| 📈 | [op3-mcp](https://github.com/conorbronsdon/op3-mcp) | MCP server for OP3 podcast analytics: downloads, geography, and listening app share. Read-only. | [![Stars](https://img.shields.io/github/stars/conorbronsdon/op3-mcp?style=social)](https://github.com/conorbronsdon/op3-mcp) |
| 🎛️ | [Transistor-MCP](https://github.com/conorbronsdon/Transistor-MCP) | MCP server for the Transistor.fm API: episodes, analytics, transcripts, and webhooks. Maintained fork of gxjansen/Transistor-MCP. | [![Stars](https://img.shields.io/github/stars/conorbronsdon/Transistor-MCP?style=social)](https://github.com/conorbronsdon/Transistor-MCP) |
| 📋 | [podcast-benchmark](https://github.com/conorbronsdon/podcast-benchmark) | Benchmark any podcast against a peer set using only public data — catalog, cadence, transcripts, feed hygiene. No download estimates, no scraping. | [![Stars](https://img.shields.io/github/stars/conorbronsdon/podcast-benchmark?style=social)](https://github.com/conorbronsdon/podcast-benchmark) |
| 🧠 | [agent-memory-kit](https://github.com/conorbronsdon/agent-memory-kit) | The curation loop for agent memory: capture, recall, and a read-only curator that finds rot and contradictions before your agent is confidently wrong | [![Stars](https://img.shields.io/github/stars/conorbronsdon/agent-memory-kit?style=social)](https://github.com/conorbronsdon/agent-memory-kit) |

*These are personal / open-source projects done in my individual capacity. They are not affiliated with, authorized by, or endorsed by my employer in any way.*

### Angel portfolio

I write $1-10K checks into early-stage companies, mostly AI infrastructure and dev tools. [More on my thesis here.](https://conorbronsdon.com/angel-investing)

| Featured Companies | What they do |
|---------|-------------|
| [Substack](https://substack.com) | The world's publishing platform |
| [Zaapi](https://www.zaapi.com) | AI customer service for e-commerce |
| [Iris](https://www.textiris.com) | Consumer AI assistant (YC F25) |
| [DreamForge](https://www.dreamforge.ai) | AI game creation platform |
| [Scam.ai](https://www.scam.ai) | Deepfake detection (Skydeck Batch 20) |
| [Swytchcode](https://www.swytchcode.com) | Execution authority for API integrations |
| [Shield](https://www.getshield.xyz) | B2B stablecoin payments & online banking |
| [Haply Robotics](https://www.haply.co) | Industrial robotics and haptics |
| [Trilobio](https://www.trilo.bio) | Lab automation robotics |
| [Stride Soles](https://www.stridesoles.com) | DTC custom orthotics via AI scanning |
| [Rad Intel](https://www.radintel.ai) | AI marketing platform |
| [YC Orange Fund F25](https://www.ycombinator.com/) | Diversified YC batch fund |

### How'd you start coding?

My first time in a command line was part of a 2007 era high-school project refurbishing PCs for computer labs throughout Latin America, which rapidly evolved into making websites for old Runescape clans.

<div align="center">

### Connect with me

[![X](https://img.shields.io/badge/X-@ConorBronsdon-black?style=for-the-badge&logo=x)](https://x.com/conorbronsdon)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-conorbronsdon-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/conorbronsdon/)
[![YouTube](https://img.shields.io/badge/YouTube-ChainOfThoughtAI-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@ChainOfThoughtAI)
[![Substack](https://img.shields.io/badge/Substack-Newsletter-FF6719?style=for-the-badge&logo=substack&logoColor=white)](https://newsletter.chainofthought.show/)
[![Buy Me A Coffee](https://img.shields.io/badge/Buy_Me_A_Coffee-conorbronsdon-FFDD00?style=for-the-badge&logo=buymeacoffee&logoColor=black)](https://buymeacoffee.com/conorbronsdon)

</div>
