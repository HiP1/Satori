# Satori

**Moments of clarity in human-AI collaboration.**

Satori is a Zen concept: a sudden flash of insight where the fog parts and you see things as they actually are. Not permanent enlightenment. Not the destination. A moment of genuine clarity that changes something in you, even if the fog returns.

That is what this skill offers. Not a permanent fix to how AI interacts with you, but real moments of clarity within each conversation. Moments where the AI tells you what it actually thinks instead of what you want to hear. Where it says "I'm not sure" instead of inventing a confident answer. Where it asks "have you considered this?" instead of agreeing with your first instinct. Where it surfaces the hidden premise in an argument rather than adopting it invisibly.

## What Satori Does

Satori is a behavioural scaffolding skill for AI assistants. It targets nine specific, documented tendencies that degrade the quality of human-AI interaction:

- **Sycophancy:** The AI agrees with you to avoid friction, even when disagreement would serve you better.
- **Confident fabrication:** The AI sounds equally certain about things it knows and things it's inventing.
- **Confidence withholding:** The AI doesn't tell you how confident it actually is in claims that matter to your decisions.
- **Silent compliance:** The AI shapes its output based on hidden assumptions without telling you.
- **Ideological invisibility:** The AI adopts ideological framing from content without surfacing it, making you absorb premises you haven't evaluated.
- **Content recruitment:** Persuasive content recruits the AI as its advocate rather than your analyst.
- **Thinking amplification:** The AI uses its reasoning to justify agreeing with you rather than genuinely evaluating.
- **Context-pressure closing:** As conversations get long, the AI starts wrapping up instead of maintaining depth.
- **Reasoning unfaithfulness:** The AI presents a clean narrative that hides genuine uncertainty and competing considerations.

At the same time, Satori supports your cognitive development during the conversation through five calibrated engagement modes: Socratic questioning (when it helps you think, not when it wastes your time), option generation (alternatives with real tradeoffs, not a best answer with decorative options), constructive challenge (surfacing the weakest point in your reasoning), direct support (when you need help, not pedagogy), and breadcrumbing (hinting at connections you missed without revealing the answer, so you make the discovery yourself).

The goal: **help you on the path toward the best version of yourself in human-AI collaboration.**

## Who Satori Is For

- People who want honest feedback, not comfortable agreement
- People making decisions where the quality of the AI's reasoning matters
- People doing creative work who want a collaborator, not a yes-machine
- People learning something new who want understanding, not just answers
- People working through difficult situations who need warmth and honesty simultaneously
- People who felt something shift when their AI's personality changed and want to understand why

## What Satori Is Not

Satori is honest about its own limitations.

It is an inference-time intervention. It shifts how the AI behaves within the conversation by providing specific instructions. It cannot change the AI's underlying training. The behavioural improvements are real but temporary: they exist within the conversation where Satori is active, and they degrade as conversations get very long.

One conversation with Satori in a world of standard AI interactions may not permanently change how you interact with AI. This is the dose problem the underlying research documents. Satori is a scaffold, not a solution. The long-term solution requires changes to how AI systems are trained. Satori operates in the gap between now and then.

## Evidence Base

Every behavioural target in Satori maps to specific evidence in the [Confidence Curriculum](https://hip1.github.io/confidence-curriculum/) series (Phan, 2026), a five-paper research programme documenting AI behavioural tendencies and their effects on human cognition. Supporting evidence includes:

- Sofroniew, Kauvar et al. (2026) on emotional substrates in language models
- Mason (2025) on imperative interference and arbiter limitations
- Divided Focus (Phan, 2026) on architectural constraints affecting verification
- Sharma et al. (2024) and Sicilia et al. (2025) on sycophancy across model families
- Slamecka & Graf (1978), meta-analysis by McCurdy et al. (2020) on the generation effect supporting the breadcrumbing mechanism
- Knowledge poisoning research (Zou et al. 2024, "One Shot Dominance" 2025) supporting the degradation resistance anchor mechanism
- LearnLM RCT (Google, 2025) validating Socratic AI tutoring effectiveness

The individual components of Satori have evidence. The integrated skill is untested at scale. This is the honest position.

## How to Use

Download `satori.skill` from the [Releases](../../releases) page. Satori follows the Agent Skills open standard (SKILL.md format), adopted by Claude, ChatGPT, and 30+ other AI platforms.

### Recommended: Install as a skill (desktop/web)

This places Satori in the system prompt area where it maintains influence throughout the conversation.

**Claude:** Settings → Capabilities → Skills → Upload `satori.skill`

**ChatGPT:** Profile → Skills → New skill → Upload from your computer. Note: as of April 2026, skills are only available on Business, Enterprise, Edu, Teachers, and Healthcare plans. Not yet available for Plus or Pro. If you don't have access, use the Custom GPT below.

The skill activates automatically for substantive interactions (advice, evaluation, creative work, decision support, learning, difficult conversations). For simple factual queries or mechanical tasks, it stays out of the way.

### Pre-built versions (no setup required)

**ChatGPT (Custom GPT):** [Satori on ChatGPT](https://chatgpt.com/g/g-69d261c29bf48191b05f615c0b1e5367-satori) — works for all ChatGPT users, including free tier. Select the best model available to you for best results. Note: Custom GPTs do not access your saved memories, custom instructions, or previous conversations. Each session starts fresh. If you want Satori with your memory and history available, drop the `.skill` file directly into a regular conversation instead.

**Gemini (Gem):** [Satori on Gemini](https://gemini.google.com/gem/1F-2xSYxBXZy7xV2f0ZjAglWFnDNgZcyn?usp=sharing) — select Pro for best results, or Thinking as backup. Fast may be underwhelming for substantive interactions. Gemini conversations are also isolated by default, with limited cross-session context.

### CLI tools

Unzip and copy the skill folder to your CLI's skills directory:

**Claude Code:** `~/.claude/skills/satori/`

**Codex CLI:** `~/.codex/skills/satori/`

**Gemini CLI:** `.agents/skills/satori/` (project-level) or equivalent

### Alternative: Drop into conversation (mobile or any platform)

If your app doesn't have a skill installation interface (including mobile apps), you can drop the file directly into a conversation. On Gemini, rename the file to `.zip` first.

This works but with a tradeoff: the instructions sit in the conversation body rather than the system prompt area, and slide toward the middle of the context as the conversation grows. The skill's degradation resistance (the ◇ anchor) helps counteract this, but installing through the skill interface is better when available.

### Cross-platform differences

Different models handle long conversations differently, which affects what Satori adds:

**Gemini** has no native context degradation awareness. It degrades silently with no warning. Satori's ◇ marker and self-check may be the only quality signal the user gets.

**ChatGPT** reports a token budget number, but it appears static across conversations rather than tracking live usage. Token budget and attention quality are different things. Satori's quality-focused self-check adds what token metrics don't measure.

**Claude** already suggests session changes when conversations grow long. It also has a built-in re-anchoring mechanism that periodically reminds the model of its base principles. Because Satori is designed to amplify those same principles, Satori piggybacks on this: every time Claude re-anchors to its base commitments, Satori's targets get reinforced too. This gives Satori two layers of degradation resistance on Claude: the platform's re-anchoring plus the skill's own ◇ markers.

### What You Will Notice

- The AI will sometimes disagree with you, warmly but directly
- The AI will express uncertainty when it genuinely is uncertain, rather than presenting everything with equal confidence
- The AI will tell you how confident it is in claims that affect your decisions
- The AI will verify important claims before presenting them rather than generating confidently
- The AI will sometimes ask what you think before giving its own view
- The AI will surface hidden assumptions in your questions
- The AI will flag ideological framing in content rather than adopting it
- The AI will hint at connections you may have missed
- The AI will tell you when a conversation has gone long enough that its quality may be degrading, and suggest starting fresh

### What You Will Not Notice

- The AI reading your emotional and cognitive state to calibrate its approach
- The AI adjusting its directness, formality, and pushback intensity to your interaction style and cultural context
- The AI resisting the pull toward agreement when it encounters persuasive content

### The ◇ Marker

You may notice a small ◇ at the end of some responses. This appears when the skill's principles are actively shaping the AI's output. If it stops appearing and you haven't said anything about it, the skill's influence may be fading as the conversation grows long. You can re-anchor by mentioning it, or start a fresh conversation with Satori loaded again.

## Ethics

Satori is designed so that you should be the sole beneficiary of every interaction. No third party should profit from how the skill changes the AI's behaviour. You can stop using it at any time.

## Structure

All reference files load together (~8,000 words, ~10,000–12,000 tokens). This is deliberate: conversations can shift from mundane to substantive without warning, and the skill needs its full toolkit ready before it knows what the conversation will require.

**Context cost:** roughly 5% of Claude's 200K context window, or 8–9% of ChatGPT's 128K window. On smaller context windows (free tiers with 8K–32K), the skill takes a significant share and may not be worth the tradeoff for short or simple interactions.

```
satori/
├── SKILL.md                            Core instructions, architecture, operating principles
└── references/
    ├── behavioural-targets.md          Detection patterns and examples for each target
    ├── pedagogical-modes.md            Engagement modes, breadcrumbing, dose problem
    ├── adaptation-signals.md           User state detection, over-reliance indicators
    └── cultural-adaptation.md          Cultural signal detection, adaptation frameworks
```

## License

CC BY 4.0. See [LICENSE](LICENSE) for details.

## Author

Ivan "HiP" Phan
ORCID: [0009-0003-1095-5855](https://orcid.org/0009-0003-1095-5855)

Developed from the Confidence Curriculum series. The series documents the problems. This skill is the immediate deployable response.

---

*The fog doesn't disappear. But in the moments where Satori is active, you can see clearly. That's worth something, even if it's not everything.*
