# awesome-ai-film 🎬

> **Every technological revolution reshapes what's possible in art.**
> Electricity made cinema. Aluminum stopped being a precious metal and became soda cans.
> Intelligence — once the rarest human resource — is becoming cheap.
>
> **What happens to film when intelligence is a commodity?**

A curated exploration of what AI is making possible in filmmaking — and what remains irreducibly human.

[English](README.md) | [简体中文](README.zh-CN.md)

---

## The Premise

| Era | Scarce Resource | When It Became Cheap | What Changed |
|-----|----------------|---------------------|--------------|
| 1880s | Electricity | Power grid | Cities lit up. Cinema was born. |
| 1890s | Aluminum | Hall-Héroult process | From crown jewels to soda cans. Skyscrapers, airplanes. |
| 1990s | Computation | PCs + internet | Anyone with a laptop became a publisher. |
| 2000s | Distribution | YouTube, streaming | Anyone became a broadcaster. |
| 2020s | **Intelligence** | LLMs, generative AI | Anyone becomes a... filmmaker? |

Each time a fundamental constraint dissolves, we don't just get *more* of the old thing. We get *new kinds* of things that were literally unthinkable before.

This repo tracks that metamorphosis for film.

---

## Contents

- [AI Filmmaking Tools](#ai-filmmaking-tools)
- [Text-to-Video Generation](#text-to-video-generation)
- [AI Scriptwriting & Story](#ai-scriptwriting--story)
- [AI Visual Effects & Post-Production](#ai-visual-effects--post-production)
- [AI Voice, Music & Sound Design](#ai-voice-music--sound-design)
- [Digital Humans & AI Actors](#digital-humans--ai-actors)
- [Democratization: Who Gets to Make Films Now?](#democratization-who-gets-to-make-films-now)
- [What Remains Human?](#what-remains-human)
- [Research & Papers](#research--papers)
- [Early Examples & Experiments](#early-examples--experiments)
- [The Economic Shift](#the-economic-shift)
- [Philosophy & Criticism](#philosophy--criticism)
- [Contributing](#contributing)
- [Code of Conduct](#code-of-conduct)

---

## AI Filmmaking Tools

*End-to-end and specialized tools for AI-assisted film production.*

- [Runway](https://runwayml.com) — Gen-3 Alpha. Text/image-to-video, motion brush, camera controls. Used in *Everything Everywhere All at Once* for rotoscoping.
- [Pika](https://pika.art) — Text-to-video with style control. Lip-sync generation.
- [Kling](https://klingai.com) — High-fidelity Chinese video generation model. 2-minute coherent videos.
- [Sora](https://openai.com/sora) — OpenAI's text-to-video. Photorealistic 60s clips with emergent 3D understanding.
- [Hailuo (MiniMax)](https://hailuoai.video) — Text-to-video with strong motion consistency.
- [LTX Studio](https://ltx.studio) — AI-native video editing: script → storyboard → edit.
- [Wonder Studio](https://wonderdynamics.com) — Auto-replace actors with CG characters. Lighting/motion transfer.
- [Descript](https://descript.com) — AI video editing via transcript. Remove filler words as easily as deleting text.
- [Topaz Video AI](https://topazlabs.com) — Upscale, deinterlace, denoise, frame-interpolate footage.
- [EbSynth](https://ebsynth.com) — Keyframe-driven style transfer for video. *Secret of Kells* aesthetic pipeline.

---

## Text-to-Video Generation

*Models and research that generate moving images from text descriptions.*

- **Sora** (OpenAI, 2024) — Diffusion transformer. Emergent world simulation. 1920×1080 @ 60s. [Technical report](https://openai.com/research/video-generation-models-as-world-simulators)
- **Veo 2** (Google DeepMind, 2025) — 4K video generation. Cinematic camera controls. [Announcement](https://deepmind.google/technologies/veo/)
- **Kling 2.0** (Kuaishou, 2025) — 1080p, 2-min clips. 3D face and body reconstruction pipeline.
- **Hailuo** (MiniMax, 2024) — Strong temporal coherence, competitive with Sora on short clips.
- **Stable Video Diffusion** (Stability AI) — Open-source. Image-to-video, 14/25 frames.
- **AnimateDiff** — Open-source. Plugs into Stable Diffusion for animated outputs.
- **ModelScope Text-to-Video** — Open-source. Chinese/English, 16-frame clips.
- **CogVideoX** (Tsinghua/Zhipu) — Open-source bilingual text-to-video. 720×480 @ 6s.

---

## AI Scriptwriting & Story

*LLMs and specialized tools for narrative generation, story structure, and screenplay writing.*

- [Sudowrite](https://sudowrite.com) — AI fiction writing with story bible, beat sheets, prose generation.
- [ScriptBook](https://scriptbook.io) — AI screenplay analysis. Predicts box office, audience demographics, narrative flaws.
- [Dramatron](https://arxiv.org/abs/2209.14958) (DeepMind) — Hierarchical story generation via LLM chaining. Logline → characters → plot → dialogue.
- [PlotGen](https://plotgen.io) — Generative plot outlines with genre-aware structure.
- [Claude](https://anthropic.com/claude) / [GPT-4](https://openai.com/gpt-4) — General-purpose. Increasingly used as screenwriting co-pilots for beat sheets, dialogue passes, coverage.
- **The Writer's Room** (concept) — Multi-agent AI writers' room. Each LLM a different "voice" in the room.

---

## AI Visual Effects & Post-Production

*How AI is changing VFX pipelines, compositing, color grading, and editing.*

- [Wonder Dynamics](https://wonderdynamics.com) — Auto character replacement. No mocap, no tracking markers. (Acquired by Autodesk, 2024)
- [Runway Motion Brush](https://runwayml.com/research/motion-brush) — Selectively animate regions of an image.
- [DAIN](https://github.com/baowenbo/DAIN) — Depth-aware frame interpolation. Turns 12fps into smooth 60fps.
- [Neural Radiance Fields (NeRF)](https://www.matthewtancik.com/nerf) — 3D scene reconstruction from 2D images. Virtual camera placement.
- [Gaussian Splatting](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/) — Real-time radiance field rendering. Game-changer for VFX previs.
- [DeepFaceLab](https://github.com/iperov/DeepFaceLab) — Face-swapping/deepfake tooling. Used in *The Irishman* de-aging explorations.
- [Colourlab AI](https://colourlab.ai) — AI color grading. Auto-match reference looks.
- [Adobe Firefly](https://firefly.adobe.com) — Generative fill, video color, text effects.

---

## AI Voice, Music & Sound Design

*Synthetic voices, AI-composed scores, procedural sound effects.*

- [ElevenLabs](https://elevenlabs.io) — Text-to-speech with voice cloning. 29 languages. Used for dubbing and ADR replacement.
- [Suno](https://suno.ai) — Text-to-music generation. Full songs with vocals and instrumentation.
- [Udio](https://udio.com) — High-quality music generation. Strong on composition structure.
- [AIVA](https://aiva.ai) — AI composer for film scores. 250+ registered works at SACEM.
- [Respeecher](https://respeecher.com) — Voice cloning for film. Recreated young Luke Skywalker's voice in *The Mandalorian*.
- [Murf](https://murf.ai) — AI voiceover studio with emotion control.
- [Descript Overdub](https://descript.com/overdub) — Clone your voice, fix audio mistakes by typing.

---

## Digital Humans & AI Actors

*Synthetic performers, digital doubles, and the question of "who is acting?"*

- [MetaHuman](https://metahuman.unrealengine.com) (Epic Games) — Real-time photorealistic digital humans. Minutes to create.
- [Siren AI / Digital Domain](https://digitaldomain.com) — Digital human pipeline. *Avengers*, *Blade Runner 2049*, de-aged actors.
- **Virtual idols / VTubers** — Entire performance personas run by AI. The "actor" never existed as a single person.
- [Synthesia](https://synthesia.io) — AI video presenters. 140+ AI avatars. Already used in corporate training at scale.
- [HeyGen](https://heygen.com) — Talking photo, AI avatar video generation.
- **De-aging technology** — *The Irishman*, *Indiana Jones 5*, *Gemini Man*. Rapidly improving fidelity.
- **Posthumous performance** — Peter Cushing in *Rogue One*, Carrie Fisher in *Rise of Skywalker*. Legal and ethical frontier.

---

## Democratization: Who Gets to Make Films Now?

*When the cost floor drops, who enters the arena?*

Historically, filmmaking cost structure:
- **Pre-2000s**: $50M+ studio system. Gatekept.
- **2000s**: $10K+ prosumer cameras. YouTube. Independent film boom.
- **2010s**: $1K+ smartphones. "Shot on iPhone" campaigns.
- **2020s**: $0/month AI tools available to anyone with internet.

### The New Filmmakers
- **Solo creators** — One person + AI = a film. No crew, no budget, no gatekeepers.
- **Non-English language cinema** — AI dubbing/localization breaks distribution barriers.
- **Niche genres** — A $0-budget experimental sci-fi short can look like a $100M production.
- **Interactive & generative cinema** — A film that is different every time you watch it.
- **Fan films & remix culture** — Legal grey zone. Creative explosion.

### Counter-forces
- **Distribution still matters**. Making a film ≠ getting it seen.
- **Taste gatekeeping shifts to curation**. The bottleneck moves from production to discovery.
- **Platform dependency**. AI tools are SaaS. You don't own the means of production.

---

## What Remains Human?

*In a world where AI can generate any image, any voice, any scene — what can't it do?*

### The Case for Human Irreplaceability

| Human Capability | Why AI Struggles |
|-----------------|------------------|
| **Lived experience** | AI has no childhood, no heartbreak, no grief. It simulates emotion — it doesn't feel it. |
| **Taste & judgment** | Knowing which shot to cut, which take to use, which line lands. AI can generate 1000 versions but can't pick the one that *matters*. |
| **Cultural intuition** | Understanding why a joke works in Lagos but not in LA. The texture of subcultures. |
| **Moral weight** | Art made by humans carries the weight of intention. "A human chose to say this" is different from "an AI generated this." |
| **The gaze** | Cinema is someone *looking*. What they choose to look at, how long, why — this is the director's consciousness. |
| **Presence** | An actor in a room. The tension of live performance. The thing that happens between takes. |
| **Risk & vulnerability** | Putting something real on screen costs the creator something. AI risks nothing. |

### What Might Actually Survive (Informed Speculation)

- **Live performance** — Theater, concerts, live broadcasts. The irreplaceable "this is happening now."
- **Documentary** — The camera's relationship to reality. Indexical truth.
- **Auteur cinema** — The idiosyncratic vision of a specific human being. Not because AI *can't* be idiosyncratic, but because we won't *care* about AI's idiosyncrasies.
- **Community filmmaking** — Made by and for specific communities. The making *is* the meaning.
- **The hand-made aesthetic** — As AI perfection becomes cheap, imperfection becomes premium. Grain, practical effects, "human error."

### The Hard Question

> When an AI-generated film wins an Oscar — not for best visual effects, but for best picture — what do we do?

---

## Research & Papers

*Academic work on AI and film.*

- [Video Generation Models as World Simulators](https://openai.com/research/video-generation-models-as-world-simulators) — OpenAI Sora technical report, 2024.
- [Dramatron: Hierarchical Story Generation](https://arxiv.org/abs/2209.14958) — DeepMind, 2022. LLM chain for screenwriting.
- [Make-A-Video: Text-to-Video without Text-Video Data](https://arxiv.org/abs/2209.14792) — Meta, 2022. Pioneering T2V.
- [Imagen Video: High Definition Video Generation](https://arxiv.org/abs/2210.02303) — Google, 2022.
- [Align your Latents: High-Resolution Video Synthesis](https://arxiv.org/abs/2304.08818) — Video LDM, 2023.
- [Phenaki: Variable Length Video Generation](https://arxiv.org/abs/2210.02399) — Google, 2022. Long-form video.
- [Tune-A-Video: One-Shot Tuning of Image Diffusion Models](https://arxiv.org/abs/2212.11565) — 2023. Fine-tune T2I models for video.
- [Generative Agents: Interactive Simulacra of Human Behavior](https://arxiv.org/abs/2304.03442) — Stanford/Google, 2023. LLM agents as characters.
- [Neural Radiance Fields (NeRF)](https://arxiv.org/abs/2003.08934) — Mildenhall et al., 2020. Scene representation.
- [3D Gaussian Splatting](https://arxiv.org/abs/2308.04079) — Kerbl et al., 2023. Real-time radiance fields.

---

## Early Examples & Experiments

*Actual AI-generated or AI-assisted films worth watching.*

- **The Frost** (Waymark, 2023) — 12-min AI-generated film using DALL-E 2 + D-ID. Narrative coherence milestone.
- **Thanksgiving** (Fabian Stelzer, 2023) — AI-native short. Audience voted on story branches. [Twitter thread](https://twitter.com/fabianstelzer)
- **Safe Zone** (Runway AI Film Festival winner, 2023) — AI-assisted short about surveillance.
- **The Crowd** (Glenn Marshall, 2022) — Neural style transfer short. Cannes selection.
- **Critterz** (Native Foreign, 2023) — First AI-generated animation on a major platform. DALL-E + professional animation pipeline.
- **AI-generated trailers** — Fan-made trailers using Midjourney + Runway for "what if" concepts (e.g., *The Legend of Zelda*, *Bioshock*).
- [Runway AI Film Festival](https://runwayml.com/ai-film-festival/) — Annual showcase. Growing quality year over year.
- [Curious Refuge](https://curiousrefuge.com) — AI filmmaking community. Home of the viral AI *Star Wars* trailer.

---

## The Economic Shift

*What happens to the film industry's economics when production cost approaches zero?*

### Current Cost Structure (approximate)
| Line Item | Studio Film | Indie Film | AI-Assisted |
|-----------|------------|------------|-------------|
| Script | $500K-$5M | $10K-$100K | $0-$100 (LLM) |
| Cast | $5M-$100M+ | $50K-$1M | $0-$500 (voice TTS) |
| VFX | $10M-$200M | $50K-$1M | $0-$5K (generative) |
| Sound/Music | $500K-$5M | $10K-$50K | $0-$100 (AI music) |
| **Total** | **$50M-$300M+** | **$500K-$10M** | **$0-$10K** |

### Implications
- **Supply explosion**. When anyone can make a film, we drown in content.
- **Curation becomes the new gatekeeper**. Festivals, algorithms, tastemakers.
- **The long tail eats the blockbuster?** Or blockbusters become even more important as cultural anchors?
- **IP becomes everything**. When execution is cheap, the *idea* is all that matters.
- **Live + experiential premium**. Things that can't be generated become more valuable.

---

## Philosophy & Criticism

*Voices thinking deeply about what this means.*

- **Ted Chiang** — "Why AI Isn't Going to Make Art." [The New Yorker, 2024](https://www.newyorker.com/culture/the-weekend-essay/why-ai-isnt-going-to-make-art)
- **Walter Benjamin** — *The Work of Art in the Age of Mechanical Reproduction* (1935). The "aura" of the original. Re-read it in the age of generation.
- **André Bazin** — "The Ontology of the Photographic Image." What is cinema's relationship to reality? When images are generated, not captured.
- **Hito Steyerl** — The "poor image." What happens when images lose resolution but gain velocity? AI inverts this: infinite resolution, questionable provenance.
- **Lev Manovich** — *The Language of New Media*. Database logic vs narrative. AI as the ultimate database cinema.
- **Shane Denson** — *Discorrelated Images*. Post-cinematic affect. How AI images "feel" different.

---

## Contributing

This is a living document. The landscape shifts weekly.

**To contribute:**
1. **New tools** — Must be publicly available (open source, commercial, or beta with waitlist). No vaporware.
2. **Papers** — Must have arXiv/DOI. Preprints welcome.
3. **Films/examples** — Must be viewable online. Link to the work, not a tweet about it.
4. **Philosophy** — Must be substantive. No hot takes.

Open a PR or issue. Link the thing. Explain why it matters *for the impossible → possible transition*.

See [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

---

## Code of Conduct

This project adheres to the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to the maintainer.

---

## License

[CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) — Public domain. This knowledge belongs to everyone.

---

*Maintained by [SpencerRaw](https://github.com/SpencerRaw). Inspired by the conviction that the cost of intelligence falling to zero is the most important story of our time — and film is where we'll see its effects most vividly.*
