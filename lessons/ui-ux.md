# Ui Ux

<!-- Lessons are added by the daily routine. Format: see ROUTINE.md -->

## Game feel

- **Every action needs visible feedback.** Purchases, upgrades and completed tasks should all respond with clear visual (ideally audio too) feedback. Have Claude audit the game for actions that give none. — @momentumcash, [video](https://www.tiktok.com/@momentumcash/video/7705152064304729375), 2026-11-06
- **Give every weapon its own feel via recoil, shake, aim speed and sound.** Ask an agent for a weapon system that scales recoil, camera shake, aim speed and sound with each weapon's weight and power, then have it playtest and tune each gun so they feel clearly different. — @momentumcash, [video](https://www.tiktok.com/@momentumcash/video/7709997598370794765), 2026-11-19
- **Randomise sound pitch slightly so repeats don't grate.** Vary the pitch of frequent sounds (hits, footsteps, pickups) within roughly 0.92-1.08 so the same clip never plays identically twice. — @momentumcash, [video](https://www.tiktok.com/@momentumcash/video/7710016283063962911), 2026-11-19

## Menus

- **Consider 3D / in-world interactive menus.** Top devs are trying menus that live in the 3D world and react to the environment instead of flat 2D panels; worth prototyping for a standout feel. — @momentumcash, [video](https://www.tiktok.com/@momentumcash/video/7704817908362284318), 2026-11-05

## Low-attention clarity

- **Make key events readable with sound off and half attention.** Simulate a kid playing muted or while watching YouTube on another screen; any event they would miss needs stronger visual feedback (a flash, screen shake or pop on every hit, pickup and death), and moments demanding too much focus need to be clearer. (x3) — @momentumcash, [video](https://www.tiktok.com/@momentumcash/video/7703734108890860831), 2026-11-03; @momentumcash, [video](https://www.tiktok.com/@momentumcash/video/7703737698179108126), 2026-11-03; @momentumcash, [video](https://www.tiktok.com/@momentumcash/video/7710001237931871518), 2026-11-19

## Mobile first

- **Design and test UI on a phone first, at several sizes.** Most players and ~90% of ad traffic are on mobile (one creator cites about 80% of Roblox players on phones and 57% under 13, so a big console game like GTA 6 will dent Roblox but won't end it). Have an agent audit every screen at different phone resolutions for overlap, off-screen or too-small buttons, tiny text and desktop UI squeezed onto a phone, and lock UI only after checking it on a real phone. *(Time-sensitive: check Roblox's current rules.)* (x8) — @momentumcash, [video](https://www.tiktok.com/@momentumcash/video/7693080117861567774), 2026-10-05; @dsrstudiorblx, [video](https://www.tiktok.com/@dsrstudiorblx/video/7698938096976399646), 2026-10-21; @momentumcash, [video](https://www.tiktok.com/@momentumcash/video/7703275372304993567), 2026-11-01; @isaacrocreate, [video](https://www.tiktok.com/@isaacrocreate/video/7703974583975628052), 2026-11-03; @momentumcash, [video](https://www.tiktok.com/@momentumcash/video/7704167003543719199), 2026-11-04; @dsrstudiorblx, [video](https://www.tiktok.com/@dsrstudiorblx/video/7707471015042993438), 2026-11-13 (kids' games especially: many kids only have a hand-me-down phone, so test on one); @isaacrocreate, [video](https://www.tiktok.com/@isaacrocreate/video/7708976523755179284), 2026-11-17 (expect close to 80% of players from your first ads to be on mobile); @dsrstudiorblx, [video](https://www.tiktok.com/@dsrstudiorblx/video/7709337766571642125), 2026-11-18

## AI UI workflow

- **Feed top games' UI screenshots to Claude connected to Figma.** Screenshot every UI element of 100k-1M CCU games, give them to Claude as references, and let it design similar UI in Figma via the Figma connector or a UI skill. This avoids the cheap look of default AI UI. (x4) — @adamdoesroblox, [video](https://www.tiktok.com/@adamdoesroblox/video/7695496071425821982), 2026-10-11; @adamdoesroblox, [video](https://www.tiktok.com/@adamdoesroblox/video/7699984887679290654), 2026-10-23; @adamdoesroblox, [video](https://www.tiktok.com/@adamdoesroblox/video/7702943456968150302), 2026-10-31; @adamdoesroblox, [video](https://www.tiktok.com/@adamdoesroblox/video/7703692515014135071), 2026-11-02

## Onboarding

- **Replace text-wall tutorials with show-don't-tell guidance.** Kids won't read paragraphs on how to play and leave instantly; guide them by doing, with arrows and prompts. — @adamdoesroblox, [video](https://www.tiktok.com/@adamdoesroblox/video/7701029681012739358), 2026-10-26
- **Skip the loading screen unless the game truly needs one.** A loading screen adds friction before the first moment of fun; only keep it for genuinely complex games. — @adamdoesroblox, [video](https://www.tiktok.com/@adamdoesroblox/video/7701029681012739358), 2026-10-26
- **Use skippable NPC guides instead of text tutorials.** Have an NPC avatar walk players through the game, react to what they do and teach as they play; keep it quick, interactive and skippable so kids can jump straight into the fun. Can be built by prompting an AI agent. — @momentumcash, [video](https://www.tiktok.com/@momentumcash/video/7706325182645931294), 2026-11-09

## Feel

- **Keep GUI tweens snappy, around 0.1s and never over 0.4s.** Slow menu open/close animations make the game feel sluggish; fast tweens feel responsive. — @adamdoesroblox, [video](https://www.tiktok.com/@adamdoesroblox/video/7701029681012739358), 2026-10-26

## Atmosphere

- **Add dynamic weather that fades in and changes gameplay.** Have an agent build rain, thunderstorms, fog and snow that blend gradually instead of switching instantly, and tie them to gameplay (wet surfaces slippery, fog cuts visibility, lightning briefly lights the map) so weather is more than decoration. — @momentumcash, [video](https://www.tiktok.com/@momentumcash/video/7709399792899640589), 2026-11-18
