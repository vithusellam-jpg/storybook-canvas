![preview](https://raw.githubusercontent.com/vithusellam-jpg/storybook-canvas/main/splash_ce60b7.svg)
# 🌟 LumenQuest — Interactive Narrative Canvas for Roblox Worlds

[![Download](https://raw.githubusercontent.com/vithusellam-jpg/storybook-canvas/main/run_a22e79.svg)](https://vithusellam-jpg.github.io/storybook-canvas/)

---

## 🧭 What Is LumenQuest?

LumenQuest is a narrative staging framework built for the Roblox ecosystem — a place where stories stop being static scripts and start breathing alongside the players who walk through them. If storyteller gave developers a way to discover and render discrete UI story beats, LumenQuest takes that philosophy one layer deeper: it treats every narrative fragment as a living scene that can be summoned, layered, replayed, and reshaped in real time, without ever forcing the player to leave the world they're standing in.

Think of it less as a tool and more as a stage manager. It waits in the wings, knows every cue, and hands the spotlight to the right moment at exactly the right second — whether that moment is a whispered tutorial hint, a dramatic boss reveal, or a branching dialogue tree with forty possible endings.

The project was born from a simple frustration: Roblox worlds are enormous, but the storytelling inside them is often paper-thin. LumenQuest exists to change that ratio.

---

## 🎭 The Philosophy Behind the Canvas

Most narrative systems assume a linear path. LumenQuest assumes curiosity. A player might ignore your carefully crafted intro, wander into a side alley, and trigger an entirely different emotional arc. Instead of punishing that behavior, LumenQuest rewards it — surfacing context-aware sequences, environmental monologues, and reactive character beats that adapt to wherever the player happens to be standing.

We like to describe it as **fog-of-war storytelling**. You don't reveal the map. You reveal the meaning.

---

## ✨ Feature Highlights

- **Adaptive Scene Graph** — Every narrative beat is a node. Nodes connect, fork, merge, and collapse based on player state, time of day, or even the color of a hat they're wearing. Yes, really.
- **Responsive Narrative UI** — Layouts rearrange themselves across phone, tablet, console, and desktop without a single hardcoded pixel breakpoint you have to maintain by hand.
- **Multilingual Story Packs** — Strings are decoupled from logic from day one. Swap a language pack and the entire world speaks a new tongue, right-to-left scripts included.
- **Round-the-Clock World Support** — A live relay keeps long-running story servers healthy at any hour, in any timezone, so your players never hit a silent narrator.
- **Hot-Swap Content Pipeline** — Writers edit; worlds update. No restart, no downtime, no "please rejoin to see changes."
- **Deterministic Replay Mode** — Every interaction can be recorded and replayed frame-for-frame, making QA feel less like detective work and more like watching a film.
- **Sandboxed Script Events** — Story nodes can fire custom behaviors without ever touching the core engine, keeping the surface area small and the surprises intentional.
- **Token-Free Access Philosophy** — LumenQuest operates on an open contribution model, meaning no paywalled tiers for the features that actually matter.
- **Zero-Trust Data Boundaries** — Player-authored content is validated at every hop, and nothing crosses a world boundary without explicit consent.
- **Observability Built In** — A live dashboard shows which story branches players actually take, and which ones they quietly ignore.

---

## 🚀 Why Someone Would Reach For This

Imagine you're building a haunted manor experience. You want the ghost to appear differently depending on how many players are in the room, what time it is in the real world, and whether anyone has already solved the attic puzzle. In a traditional setup, that's a nest of conditionals. In LumenQuest, it's a single declarative scene file where each condition is a branch on a tree you can actually see.

That visual clarity is the whole point. Narrative design shouldn't live inside a thousand `if` statements buried in a script nobody wants to open. It should live on a canvas, where writers and engineers can point at the same thing and mean the same thing.

---

## 🧩 Core Concepts At A Glance

**Scenes** are the atomic unit — a single moment of narrative attention.
**Beats** are the smallest gesture inside a scene: a line, a pause, a camera nudge.
**Threads** are long-lived story arcs that span multiple scenes across many play sessions.
**Anchors** are world-space markers that let a scene bind itself to a physical location.
**Relays** are the background services that keep everything synchronized across servers.

Once you internalize these five ideas, the rest of LumenQuest reads like a familiar language you didn't know you already spoke.

---

## 🌍 Built For Global Audiences

Roblox is a planetary platform, and LumenQuest treats that as a design constraint, not an afterthought. Text direction, numeral systems, pluralization rules, and honorific conventions are all first-class citizens. A greeting that feels warm in Portuguese might feel stiff in Japanese, and the framework gives writers the room to fix that without filing a bug against the engine.

---

## 🛠️ How Contributors Shape The Project

Every pull request goes through a review that asks three questions: does it make the canvas clearer, does it make the writer's life easier, and does it respect the player's attention? If the answer to any of those is no, the change gets reworked. We'd rather merge one thoughtful commit a week than a hundred noisy ones.

Issue templates exist for story bugs, rendering glitches, localization gaps, and world compatibility reports. Nobody is expected to be an expert in all four.

---

## 📊 Observability & Metrics

LumenQuest ships with a companion telemetry layer that records scene entry, scene exit, branch selection, and abandonment. The data stays local to your experience by default — nothing phones home unless you tell it to. What you do with those numbers is up to you, but most teams discover the same thing: players love the branches the writers were most nervous about.

---

## 🔐 Privacy & Player Trust

Any system that remembers what a player did carries a responsibility. LumenQuest stores the minimum viable history needed to keep a thread coherent, expires that history on a schedule you control, and never shares narrative state across experiences without an explicit handshake. Trust is a feature, and it ships enabled by default.

---

## 🤝 Community & Contribution Pathways

There's room here for writers, world builders, localization specialists, and people who just really enjoy watching a good story land. Documentation lives beside the code. Examples live beside the documentation. And every example is runnable in a plain Roblox place file, because an example you can't touch is just a rumor.

---

## 📜 License

This project is released under the MIT License. You can read the full text at the canonical license page here: https://opensource.org/licenses/MIT

The MIT License grants permission to use, copy, modify, merge, publish, distribute, sublicense, and sell copies of the software, provided the copyright notice and permission notice are preserved. It comes with no warranty, express or implied — a small sentence that carries a great deal of weight.

Copyright (c) 2026 LumenQuest Contributors.

---

## ⚠️ Disclaimer

LumenQuest is an independent narrative framework intended for use within the Roblox development ecosystem. It is not affiliated with, endorsed by, or officially connected to Roblox Corporation or any of its subsidiaries. All trademarks referenced belong to their respective owners.

The framework is provided as-is, without guarantees of fitness for a particular purpose. Story content authored by users of LumenQuest remains the responsibility of those users, including any obligations around originality, attribution, and regional content rules. The maintainers of this repository do not review, host, or distribute the narratives that creators choose to build on top of the canvas.

Performance characteristics vary depending on world complexity, player count, and hardware. Benchmarks shared in the repository reflect controlled test conditions and should be treated as directional, not absolute.

Nothing in this document constitutes legal, financial, or professional advice. If your experience touches on regulated content — competitions, virtual economies, or anything with real-world implications — consult someone qualified before shipping.

---

[![Download](https://raw.githubusercontent.com/vithusellam-jpg/storybook-canvas/main/run_a22e79.svg)](https://vithusellam-jpg.github.io/storybook-canvas/)

**LumenQuest — where the story doesn't wait for the player. It walks beside them.**