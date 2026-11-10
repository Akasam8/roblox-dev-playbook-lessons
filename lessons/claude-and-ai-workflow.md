# Claude And Ai Workflow

<!-- Lessons are added by the daily routine. Format: see ROUTINE.md -->

## Prompting

- **Reverse-engineer prompts from references.** When you don't know how to ask AI for something (thumbnail, animation, UI), give it an example that already works (screenshot or clip) and ask it to write the prompt that recreates that style for your game. (x2) — @dsrstudiorblx, [video](https://www.tiktok.com/@dsrstudiorblx/video/7704135454823681311), 2026-11-04; @dsrstudiorblx, [video](https://www.tiktok.com/@dsrstudiorblx/video/7704135345041853727), 2026-11-04
- **Give context and references, and make the AI ask questions first.** Assign a role, give full context and reference examples, then ask what questions it has before it builds (e.g. a /global message system); answer and repeat. Push back on weak first answers and ask it to explain its reasoning. Broad prompts give wrong results. (x3) — @momentumcash, [video](https://www.tiktok.com/@momentumcash/video/7675547651525381407), 2026-08-19; @momentumcash, [video](https://www.tiktok.com/@momentumcash/video/7675858358712241438), 2026-08-19; @dsrstudiorblx, [video](https://www.tiktok.com/@dsrstudiorblx/video/7688912204967529758), 2026-09-24
- **Build the game in phases; never one-shot it with AI.** Prompt one system at a time (core gameplay, UI, monetisation, map, funnels, movement) and test each before moving on, using short follow-up prompts to iterate on a feature. One giant prompt produces a fragile, shallow game. (x12) — @adamdoesroblox, [video](https://www.tiktok.com/@adamdoesroblox/video/7689503728868658463), 2026-09-25; @adamdoesroblox, [video](https://www.tiktok.com/@adamdoesroblox/video/7689924526343245087), 2026-09-26; @adamdoesroblox, [video](https://www.tiktok.com/@adamdoesroblox/video/7692183185672654110), 2026-10-02; @adamdoesroblox, [video](https://www.tiktok.com/@adamdoesroblox/video/7692220099280784671), 2026-10-02; @adamdoesroblox, [video](https://www.tiktok.com/@adamdoesroblox/video/7692578391853108510), 2026-10-03; @adamdoesroblox, [video](https://www.tiktok.com/@adamdoesroblox/video/7692594425054170398), 2026-10-03; @adamdoesroblox, [video](https://www.tiktok.com/@adamdoesroblox/video/7692838177345719583), 2026-10-04; @adamdoesroblox, [video](https://www.tiktok.com/@adamdoesroblox/video/7693319594039119134), 2026-10-05; @adamdoesroblox, [video](https://www.tiktok.com/@adamdoesroblox/video/7693324834452950302), 2026-10-05; @adamdoesroblox, [video](https://www.tiktok.com/@adamdoesroblox/video/7693694079263198494), 2026-10-06; @adamdoesroblox, [video](https://www.tiktok.com/@adamdoesroblox/video/7694446250896248094), 2026-10-08; @adamdoesroblox, [video](https://www.tiktok.com/@adamdoesroblox/video/7701063760420687135), 2026-10-26

## Playtesting with AI

- **Have Claude playtest as a specific new player, then iterate.** Tell the agent to role-play a first-time player of your target age (most Roblox players are young, roughly 6–12), try the main actions, and list everything confusing, boring or broken; fix the biggest friction and re-run. Vary the persona (impatient kid, non-techy adult) and treat it as a supplement to real playtests, not a replacement. (x6) — @momentumcash, [video](https://www.tiktok.com/@momentumcash/video/7690419663771110686), 2026-09-28; @momentumcash, [video](https://www.tiktok.com/@momentumcash/video/7693076345286331678), 2026-10-05; @momentumcash, [video](https://www.tiktok.com/@momentumcash/video/7702808498140237086), 2026-10-31; @momentumcash, [video](https://www.tiktok.com/@momentumcash/video/7702834109256699167), 2026-10-31; @momentumcash, [video](https://www.tiktok.com/@momentumcash/video/7702870530046758174), 2026-10-31; @momentumcash, [video](https://www.tiktok.com/@momentumcash/video/7705143276524915999), 2026-11-06

## Agent setup

- **Split work into researcher, builder and reviewer agents.** Have them check each other's work before showing you anything, and keep a running mistakes file (what broke, the fix, the lesson) so the next build starts smarter. — @momentumcash, [video](https://www.tiktok.com/@momentumcash/video/7705673187983428894), 2026-11-08
- **Turn research into reusable skills.** Have the agent study public game-design knowledge repos, top Roblox dev/design videos and transcripts from creators you trust, then save the techniques as a skill it applies to your game (this playbook is one). Respect licences. (x4) — @momentumcash, [video](https://www.tiktok.com/@momentumcash/video/7702485206216805662), 2026-10-30; @momentumcash, [video](https://www.tiktok.com/@momentumcash/video/7704371804441201951), 2026-11-04; @momentumcash, [video](https://www.tiktok.com/@momentumcash/video/7705619523206106399), 2026-11-08; @momentumcash, [video](https://www.tiktok.com/@momentumcash/video/7705624189381774623), 2026-11-08

## Context

- **AI is now normal in Roblox dev.** Roblox reported that 80%+ of its top games use AI in some form, and a beginner with Claude/Codex shipped a decent game in two weeks. Using AI isn't the edge; using it for original ideas is. AI makes ambitious, script-heavy original mechanics far easier to build, so don't just use it to clone existing games faster. (x3) — @dsrstudiorblx, [video](https://www.tiktok.com/@dsrstudiorblx/video/7702283173010459934), 2026-10-30; @dsrstudiorblx, [video](https://www.tiktok.com/@dsrstudiorblx/video/7701910844749253918), 2026-10-29; @momentumcash, [video](https://www.tiktok.com/@momentumcash/video/7705691118519733535), 2026-11-08
- **Keep a game knowledge vault so AI remembers every system.** Maintain an Obsidian vault documenting every mechanic, map and system (plus reference notes on UI, animation and map-building) for Claude to read, so it doesn't lose details between sessions. (x2) — @adamdoesroblox, [video](https://www.tiktok.com/@adamdoesroblox/video/7702943456968150302), 2026-10-31; @adamdoesroblox, [video](https://www.tiktok.com/@adamdoesroblox/video/7705555408844229918), 2026-11-07

## Art direction

- **Use named design styles when prompting for visuals.** AI image tools respond poorly to vague words like clean or grunge; learn and use actual style names from a visual-vocabulary guide so thumbnails, icons and promo art stop looking generic. — @momentumcash, [video](https://www.tiktok.com/@momentumcash/video/7678065239442591007), 2026-08-25
- **Pair Claude Code with an image-generation tool.** Claude Code cannot generate images itself, so connect it to an image model (e.g. via Higgsfield) to produce custom, on-brand icons and art while it builds the UI. — @momentumcash, [video](https://www.tiktok.com/@momentumcash/video/7675846114733460766), 2026-08-19

## Automation

- **Log repetitive tasks for a week, then automate them.** For one week write down every repetitive task you do, then ask AI which can be fully or partly automated and what tools you would need, to find hours of work an agent could take over. — @momentumcash, [video](https://www.tiktok.com/@momentumcash/video/7693058774273215775), 2026-10-05

## Fundamentals

- **Learn Luau and modelling basics before leaning on AI.** Understand how Luau, Blender and game systems work (AI can teach you) so you can direct and debug it. You don't need a $200+/month plan; on a small budget, pick one AI tool and learn it deeply. (x3) — @dsrstudiorblx, [video](https://www.tiktok.com/@dsrstudiorblx/video/7692564354356514079), 2026-10-03; @isaacrocreate, [video](https://www.tiktok.com/@isaacrocreate/video/7702960048233909510), 2026-10-31; @isaacrocreate, [video](https://www.tiktok.com/@isaacrocreate/video/7702625015786654977), 2026-10-31

## AI games

- **AI-built games still need deliberate design and polish.** AI implements your ideas but doesn't supply a storyboard, core loop or polish; study successful games' core systems, sound and retention hooks, and take time instead of shipping a week-old build. Obvious AI slop scares players away. (x4) — @dsrstudiorblx, [video](https://www.tiktok.com/@dsrstudiorblx/video/7691557200476556575), 2026-10-01; @dsrstudiorblx, [video](https://www.tiktok.com/@dsrstudiorblx/video/7691880841060076830), 2026-10-02; @dsrstudiorblx, [video](https://www.tiktok.com/@dsrstudiorblx/video/7692566112361286943), 2026-10-03; @isaacrocreate, [video](https://www.tiktok.com/@isaacrocreate/video/7698438977153436948), 2026-10-19

## Tool choice

- **Creator found Claude Opus 5.5 strongest for Roblox assets.** After spending about $400 in a month on Claude and Codex, one dev found both strong at code but preferred Claude Opus 5.5 with Claude Design for models and visual effects. *(Time-sensitive: check Roblox's current rules.)* — @dsrstudiorblx, [video](https://www.tiktok.com/@dsrstudiorblx/video/7695214687801183518), 2026-10-11
- **Fable 5.2 is pricier than Opus 5.5; use it selectively.** Fable 5.2 became available on all paid Claude plans and tops benchmarks, but burns usage much faster than Opus 5.5. Stay on Opus 5.5 for most tasks and switch to Fable for hard problems or to review finished work. *(Time-sensitive: model pricing and plans change.)* — @momentumcash, [video](https://www.tiktok.com/@momentumcash/video/7706280685874515231), 2026-11-09

## Skill gaps

- **List your skill gaps and plan who or what covers them.** Before starting, note what you're good at (e.g. scripting, modelling, building) and what you're not (UI, SFX, VFX), then line up collaborators or a tested AI workflow for the gaps. — @dsrstudiorblx, [video](https://www.tiktok.com/@dsrstudiorblx/video/7687812237339282718), 2026-09-21

## Setup

- **Connect Claude to Studio via Studio's built-in MCP server.** In Studio open the AI Assistant panel's three-dot menu, Settings, MCP Servers, Setup Instructions and copy the JSON config; paste it into Claude Desktop's Settings > Developer > Edit Config file, save, fully quit and reopen Claude. Studio should show one client connected; confirm by asking Claude to check the Studio connection. (x4) — @adamdoesroblox, [video](https://www.tiktok.com/@adamdoesroblox/video/7691747109111942431), 2026-10-01; @adamdoesroblox, [video](https://www.tiktok.com/@adamdoesroblox/video/7691747282479287583), 2026-10-01; @adamdoesroblox, [video](https://www.tiktok.com/@adamdoesroblox/video/7695496071425821982), 2026-10-11; @adamdoesroblox, [video](https://www.tiktok.com/@adamdoesroblox/video/7702943456968150302), 2026-10-31

## Debugging

- **Make the AI add print logs and playtest for you.** Ask Claude to add print logging to its scripts and run playtests itself, so it can read the output and fix bugs without you relaying errors. — @adamdoesroblox, [video](https://www.tiktok.com/@adamdoesroblox/video/7689503728868658463), 2026-09-25

## Art and models

- **Use Blender MCP for AI-made models and animations.** Connect Blender to Claude Code or Codex through a Blender MCP so the AI can generate 3D models and animations, then import them into Studio. (x2) — @adamdoesroblox, [video](https://www.tiktok.com/@adamdoesroblox/video/7695496071425821982), 2026-10-11; @adamdoesroblox, [video](https://www.tiktok.com/@adamdoesroblox/video/7702943456968150302), 2026-10-31

## Studio tools

- **Install Easy Textures, Brush Tool and Archimedes plugins.** Easy Textures applies textures with one click, Brush Tool scatters many parts/objects instead of placing them one by one, and Archimedes builds smooth curved part arcs. — @adamdoesroblox, [video](https://www.tiktok.com/@adamdoesroblox/video/7697288194215267614), 2026-10-16
