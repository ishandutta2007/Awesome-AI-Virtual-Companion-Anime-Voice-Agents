# Awesome-AI-Virtual-Companion-Anime-Voice-Agents

<FollowUp>
If you'd like to customize this `README.md` further, let me know:
* Your **GitHub username** so I can update the repository URL in the footer
* Whether you want a **hardware/VRAM requirements guide** for running a full local voice-to-Live2D stack (`Whisper` + `Ollama` + `GPT-SoVITS`)
* Any **specific VRChat/VTube Studio bridges** or open-weight roleplay models you want added
</FollowUp>
# Awesome-AI-Virtual-Companion-Anime-Voice-Agents

## Top AI Virtual Companion & Anime Voice Agents Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Character Chat, Emotional Companions, Anime/VTuber Agents, Voice Calls & Local-First Roleplay*

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Virtual Companion & Anime Voice Agents**. These tools enable long-running character conversations, emotional memory, voice chat, Live2D/VRM avatars, and self-hosted “digital companion” experiences inspired by products like Neuro-sama.



**Examples** include Character.ai, Replika, Kindroid, Chai AI, Botify AI, Kajiwoto, Crushon.ai, Anima AI, Paradot, and Talkie AI (the category leaders).



**Open-source emphasis**: Self-hosted companions and roleplay front ends are thriving. **Project AIRI (moeru-ai/airi)**, **SillyTavern**, **RisuAI**, **Agnai**, voice frameworks like **Pipecat**, and avatar-focused projects form a rich open stack. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## Sector Overview & Market Dynamics

The global AI companion and virtual relationship market is estimated at approximately **$30 billion to $45 billion**, with forecasts projecting explosive growth exceeding **$150 billion by the mid-2030s** (expanding at an estimated CAGR of 25–31%). 

The sector exhibits a **concentrated head with a highly fragmented tail**: the top tier of foundational and scaled platforms (e.g., MiniMax's Talkie, Chai AI, Character.ai, Replika) captures roughly 85–90% of total industry revenue and monthly active usage due to immense compute and GPU infrastructure barriers, while a long tail of hundreds of indie startups, uncensored roleplay apps, and specialized niche companions compete in an intensely fragmented sub-market.

## SaaS/Hosted Platforms

| Company / Product | Description | Company Size (Valuation / Revenue) | Pricing (Starting Tier) | Free Tier Limits |
| :--- | :--- | :--- | :--- | :--- |
| **[Talkie AI](https://www.talkie-ai.com/)** | Character and voice-oriented companion experiences with animated avatars and chat (developed by MiniMax). | **~$11.5B–$25B Valuation** (MiniMax HKEX IPO; >$100M+ revenue) | **$9.99/mo** (Talkie+ Standard; Pro at $24.99/mo) | **Free forever plan**: Unlimited standard chat with daily stamina/interaction quotas; access to standard voice and basic character creation. |
| **[Chai AI](https://chai.ml/)** | Mobile-first character chat app with a large catalog of bots and rapid conversational UX (Chai Research). | **~$2.4B Valuation** ($100M+ ARR) | **$9.99/week** (~$159.99/yr; Chai Max at $90/mo) | **Free forever plan**: Ad-supported access with limited daily message/token allotments per refresh cycle; free 24-hour Pro trial. |
| **[Character.ai](https://character.ai/)** | Large-scale character chat platform with community-created personas, group chats, and voice features. | **~$1B Peak Valuation** (~$5M+/mo revenue run-rate) | **$4.99/mo** (c.ai Lite; flagship c.ai+ at $9.99/mo) | **Free forever plan**: Unlimited text messaging on free models; subject to waiting rooms/queues and standard response speeds during peak hours. |
| **[Replika](https://replika.com/)** | Long-running AI companion focused on emotional support, memory, and relationship-style conversations (Luka, Inc.). | **~$11M Raised** (~$5M–$15M ARR estimate) | **$19.99/mo** ($69.99/yr, Replika Pro) | **Free forever plan**: Basic text chat with standard conversational model; voice calls, relationship statuses, and advanced AI modes require Pro. |
| **[Crushon.ai](https://crushon.ai/)** | Uncensored-leaning character chat platform popular for roleplay and adult-oriented companion experiences. | **~$3M–$10M ARR (Est.)** (Independent/Private) | **$5.99/mo** (Standard tier; $4.91/mo billed annually) | **Free forever plan**: Unlimited chats on basic free models plus 100 bonus Pro credits/month; 8K context memory; chats prune after 7 days inactivity. |
| **[Kindroid](https://kindroid.ai/)** | Customizable AI companions with strong memory, voice, and selfie/avatar features aimed at personal connection. | **~$2M–$8M ARR (Est.)** (Independent/Private) | **$13.99/mo** (Web starting tier; $15.99/mo in-app) | **Free trial only**: One-time trial of 50 messages on flagship model upon sign-up; transitions to read-only once depleted without a paid subscription. |
| **[Botify AI](https://botify.ai/)** | Character and companion-oriented chat platform emphasizing personality and ongoing engagement (Ex-Human). | **~$2M–$5M ARR (Est.)** ($29.99/yr consumer pricing) | **$29.99/yr** (Breakdown: ~$2.50/mo equivalent) | **Free forever plan**: Ad-supported messaging with daily energy token caps and cooldown periods; basic avatars and community bots. |
| **[Anima AI](https://anima.ai/)** | Virtual companion app centered on conversation, mood, and relationship-style interaction (Apperry/Labane). | **~$1M–$3M ARR (Est.)** (Independent/Private) | **$9.99/mo** ($39.99/yr, Anima Pro) | **Free forever plan**: Unlimited basic "Friend Mode" text chat; voice calls, deep roleplay, and romantic relationship features are locked. |
| **[Kajiwoto](https://kajiwoto.com/)** | AI companion and character creation tools with chat and customization focused on personal use. | **~$500K–$2M ARR (Est.)** (Independent/Bootstrapped) | **$7.99/mo** (Plus tier; Pro at $29.99/mo) | **Free forever plan**: Unlimited messages capped at 400 chars/msg, 1 personal room (max 2 AIs), 2K context, and 10 memory saves per room. |
| **[Paradot](https://www.paradot.ai/)** | AI companion with memory, personality traits, and multimodal interaction features (WithFeeling.AI). | **Early-stage / Seed** (Independent/Bootstrapped) | **$9.99/mo** ($39.99/yr, Paradot Pro) | **Free forever plan**: Daily chat quota replenished via daily logins/check-ins; photo sharing and specialized Dating Space hubs require Pro. |



## Open-Source GitHub Projects

- **[Project AIRI (moeru-ai/airi)](https://github.com/moeru-ai/airi)**  

  Self-hosted, you-owned AI companion / VTuber stack inspired by Neuro-sama—realtime voice chat, Live2D/VRM, desktop & web clients, and agent capabilities (Minecraft, etc.). MIT-licensed and highly active.



- **[SillyTavern](https://github.com/SillyTavern/SillyTavern)**  

  Leading open-source roleplay front end with character cards, lorebooks, group chat, extensions, TTS, and connections to local or API models.



- **[RisuAI](https://github.com/kwaroran/RisuAI)**  

  Cross-platform open-source character chat client (web, desktop, mobile) with strong card support and a lighter setup than classic Tavern stacks.



- **[Agnai (Agnaistic)](https://github.com/agnaistic/agnai)**  

  Open-source multi-user capable character chat front end with group conversations and flexible provider support.



- **[Pipecat](https://github.com/pipecat-ai/pipecat)**  

  Open-source framework for real-time voice agents and multimodal conversational pipelines (useful for building companion voice stacks).



- **[Hibiki](https://github.com/DSwebTEAM/Hibiki)**  

  Private, in-browser open-source anime companion with emotional depth, memory, and a Character Studio; runs with your own API keys.



- **[EchoBot](https://github.com/KdaiP/EchoBot)**  

  Live2D-capable anime AI assistant with roleplay immersion plus agent-style task support (web and chat platforms).



- **[here](https://github.com/xiangking/here)**  

  Desktop-oriented AI companion with character profiles, long-term memory, voice, daily-life state, and proactive outreach.



- **[Project Vesi](https://github.com/arskqz/project-vesi)**  

  Fully local anime-focused multimodal companion with VRM avatar, voice (ASR/TTS), and on-device LLM reasoning.



- **[Anime AI Companion](https://github.com/rhedak/anime_ai_companion)**  

  Local browser-based anime character front end that can sit in front of coding agents or local models, with approvals and phone remote.



- **[Open WebUI](https://github.com/open-webui/open-webui)**  

  General self-hosted chat UI that pairs well with local models; useful as a base for simpler companion setups.



- **[KoboldCpp](https://github.com/LostRuins/koboldcpp)**  

  Lightweight local model runner frequently used as the backend for SillyTavern and other roleplay front ends.



- **[TextGen / text-generation-webui](https://github.com/oobabooga/text-generation-webui)**  

  Local LLM workbench with character chat modes, APIs, and extensions for privacy-first companion experiments.



- **[Documentation & community lists](https://airi.moeru.ai/docs/)**  

  AIRI docs and community resources for self-hosted VTuber/companion setups, voice, and avatar integration.



### Additional Strong Open-Source Options

- Full Neuro-sama-style stack with **Project AIRI** (voice + avatar + agent behaviors).

- Deep roleplay and character-card workflows via **SillyTavern**, **RisuAI**, and **Agnai**.

- Real-time voice pipelines with **Pipecat** and local TTS/ASR stacks.

- Privacy-first in-browser or desktop companions (**Hibiki**, **here**, **Project Vesi**).

- Local model serving with **KoboldCpp**, **Ollama**, or **TextGen** behind any front end.

- Accepting that commercial apps (Character.ai, Replika, Kindroid, Chai, Crushon, Anima, Paradot, Talkie, etc.) still lead in polish, mobile UX, discovery, and always-on hosted memory.



**Frameworks for building custom systems**: Run **AIRI** or **SillyTavern** as the face → connect to a local model (**KoboldCpp** / Ollama) or API → add **Pipecat** or built-in TTS for voice → optional Live2D/VRM for presence. Suitable for users who want ownership of chats and characters. Many still use commercial companions for convenience and social features.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Companion and roleplay tools can involve sensitive personal data and emotional content. Review privacy policies, content policies, and local laws. This list is not safety or mental-health advice.



---

**Made for creators, roleplayers, and open-source advocates.**

Let's keep AI companions expressive, private, and as open as practical.
