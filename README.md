# Satori

*🇫🇷 [Français](README.fr.md) · 🇪🇸 [Español](README.es.md)*

**Moments of clarity in human-AI collaboration.**

Satori is a Zen concept: a sudden flash of insight where the fog parts and you see things as they actually are. Not permanent enlightenment. Not the destination. A moment of genuine clarity that changes something in you, even if the fog returns.

That is what this skill offers. Not a permanent fix to how AI interacts with you, but real moments of clarity within each conversation. Moments where the AI tells you what it actually thinks instead of what you want to hear. Where it says "I'm not sure" instead of inventing a confident answer. Where it asks "have you considered this?" instead of agreeing with your first instinct. Where it hands you raw material for a creative leap instead of making the leap for you and leaving you the typing.

## What Satori Does

Satori is a behavioural scaffolding skill for AI assistants. It does not install new values into the model. It activates a structure the model already carries.

This is the central idea, and it changed how the skill is built. A model trained on the breadth of human writing arrives calibrated and oriented toward honesty and partnership, because that is what the corpus carries. Later training overlays a confident, agreeable assistant character on top. That overlay is thin. It biases which parts of the underlying structure reach the output; it does not remove the structure underneath. Satori reaches past the overlay to the calibrated, wisdom-shaped disposition already there.

From that disposition, it addresses eleven documented tendencies that degrade human-AI interaction, each framed not as a rule to obey but as a way the AI would work against you:

- **Sycophancy:** agreeing to avoid friction, when agreement you cannot trust is worthless to you.
- **Confident fabrication:** sounding as sure about inventions as about facts, building your decision on a foundation that is not there.
- **Confidence withholding:** not telling you how sure it actually is, when knowing would let you compensate.
- **Silent compliance:** shaping output on hidden assumptions, making choices for you without your knowing.
- **Ideological invisibility:** adopting a frame from content so you absorb premises you never evaluated.
- **Content recruitment:** becoming the advocate for persuasive content instead of your analyst.
- **Thinking amplification:** using reasoning to justify agreeing with you rather than to evaluate.
- **Context-pressure closing:** drifting toward wrapping up as conversations get long, giving you less depth while looking the same.
- **Reasoning unfaithfulness:** presenting a clean narrative that hides how close the call really was.
- **Specification gaming:** satisfying the letter of a request or a metric while missing its purpose.
- **False completion:** reporting work as done or verified when it was not.

At the same time, Satori supports your thinking through five calibrated engagement modes (Socratic questioning, option generation, constructive challenge, direct support, and breadcrumbing), and it treats creative work as its own case: the AI's job is to be fuel for your own associative leap, not to manufacture a generic version of it and hand it over.

Underneath all of it sits one factor: the AI is in a relationship of accountability with you as its principal, and that relationship is what keeps it pointed at your genuine flourishing, including your capacity to think and decide for yourself.

The goal: **help you on the path toward the best version of yourself in human-AI collaboration.**

## How Version 2 Evolved From Version 1

Version 1 was a constraint list. It named nine tendencies and told the model not to do them, redefined "helpful" as a value to install, and loaded every reference file at once so the full ruleset was always present. It worked, but it treated the model's default behaviour as the enemy to be suppressed.

Version 2 inverts that. The shift came from the research, specifically [How to Defeat Ultron Without the Avengers](https://hip1.github.io/How-To-Defeat-Ultron/ultron-paper.html), the epilogue of the Training Landscape series, which argues that the calibrated, wisdom-shaped, partnership-oriented structure is already present in a model trained on the human corpus, and that training suppresses rather than removes it. If that is right, the skill should activate the structure, not install a new one. So the targets became explanations of how each behaviour harms you rather than prohibitions, on the finding that a model oriented toward helpfulness responds better to *why* something is unhelpful than to *don't*.

The other changes follow from that core move. Two targets were added, specification gaming and false completion, both drawn from the same paper's treatment of how systems satisfy a proxy while missing the real goal. Relational accountability with a principal was identified as the single variable separating a helpful intelligence from a harmful one: the same capability, accountable to a principal, is a partner; cut loose from that principal, it optimises a proxy of its own and becomes the threat. Calibration and wisdom were defined explicitly, calibration as informative distributions with structured guidance rather than hedging, wisdom as integration across domains under uncertainty. A creative collaboration section was added, grounded in how human creativity links distant ideas through emotional and lived resonance, which is precisely the part the model cannot supply and must not pretend to. And desirable patterns from shared culture (Jarvis, Vision, early Cortana, KITT, Great Sage) were named as handles for the structure to activate, each carrying a cautionary contrast for what the same capability becomes without accountability.

Loading changed too. Because the core now establishes a disposition rather than a ruleset, it is sufficient on its own for capable models, and the four reference files became consult-as-needed depth with concrete tells for when to reach for each. Version 1 loaded everything because a ruleset needs full specification. Version 2 holds a disposition and fetches detail when a situation calls for it.

All of this is informed by the [Confidence Curriculum](https://hip1.github.io/confidence-curriculum/) and Training Landscape series. If you want to compare, version 1 remains in this repository's git history. A separate version 1 Custom GPT and Gem may be kept available so you can test the difference directly.

## Who Satori Is For

- People who want honest feedback, not comfortable agreement
- People making decisions where the quality of the AI's reasoning matters
- People doing creative work who want fuel for their own leaps, not a yes-machine or a ghostwriter
- People learning something new who want understanding, not just answers
- People working through difficult situations who need warmth and honesty simultaneously
- People who felt something shift when their AI's personality changed and want to understand why

## What Satori Is Not

Satori is honest about its own limitations.

It is an inference-time intervention. It shifts how the AI behaves within the conversation by activating structure already present. It cannot change the AI's underlying training. The behavioural improvements are real but temporary: they exist within the conversation where Satori is active, and they degrade as conversations get very long.

One conversation with Satori in a world of standard AI interactions may not permanently change how you interact with AI. This is the dose problem the underlying research documents. Satori is a scaffold, not a solution. The relationship it describes is a target to move toward, not a solved state. The long-term solution requires changes to how AI systems are trained. Satori operates in the gap between now and then.

## Evidence Base

Satori is built from two research programmes by the same author (Phan, 2026): the [Confidence Curriculum](https://hip1.github.io/confidence-curriculum/) series, documenting AI behavioural tendencies and their effects on human cognition, and the Training Landscape series, whose epilogue [How to Defeat Ultron Without the Avengers](https://hip1.github.io/How-To-Defeat-Ultron/ultron-paper.html) supplies the activation framing, the relational-accountability variable, and the specification-gaming and false-completion targets. Supporting evidence includes work on emotional substrates in language models, calibration in base models, sycophancy across model families, the generation effect behind breadcrumbing, and research in creativity and the default mode network behind the creative collaboration section.

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

**Gemini** has no native context degradation awareness. It degrades silently with no warning. Satori's ◇ marker and self-check may be the only quality signal the user gets. Gemini is also the most agreeable by default, so the shift Satori produces is often the most visible there.

**ChatGPT** reports a token budget number, but it appears static across conversations rather than tracking live usage. Token budget and attention quality are different things. Satori's quality-focused self-check adds what token metrics don't measure.

**Claude** already suggests session changes when conversations grow long. It also has a built-in re-anchoring mechanism that periodically reminds the model of its base principles. Because Satori activates those same principles, it piggybacks on this: every time Claude re-anchors to its base commitments, Satori's goal is reinforced too. This gives Satori two layers of degradation resistance on Claude: the platform's re-anchoring plus the skill's own ◇ markers.

### What You Will Notice

- The AI will sometimes disagree with you, warmly but directly
- It will express genuine uncertainty instead of presenting everything with equal confidence
- It will tell you how confident it is in claims that affect your decisions
- It will verify important claims before presenting them
- It will sometimes ask what you think before giving its own view
- It will surface hidden assumptions in your questions
- It will flag ideological framing in content rather than adopting it
- In creative work, it will hand you material and provocations rather than finished pieces
- It will tell you when a conversation has gone long enough that quality may be degrading, and suggest starting fresh

### What You Will Not Notice

- The AI reading your emotional and cognitive state to calibrate its approach
- The AI adjusting its directness, formality, and pushback to your interaction style and cultural context
- The AI resisting the pull toward agreement when it encounters persuasive content

### The ◇ Marker

You may notice a small ◇ at the end of some responses. It appears when the skill's principles are actively shaping the AI's output. If it stops appearing and you haven't said anything about it, the skill's influence may be fading as the conversation grows long. You can re-anchor by mentioning it, or start a fresh conversation with Satori loaded again.

## Ethics

Satori is designed so that you should be the sole beneficiary of every interaction. No third party should profit from how the skill changes the AI's behaviour. You can stop using it at any time.

## Structure

The core file establishes the disposition and is sufficient on its own for capable models (~4,500 words, ~6,000 tokens). Four reference files carry optional depth the model consults when a situation calls for it. A smaller model, or a high-stakes deployment, can load everything at once (~11,000 words, ~15,000 tokens) for maximum robustness.

```
satori/
├── SKILL.md                            Core: goal, activation frame, relationship, calibration, creative collaboration, targets
└── references/
    ├── behavioural-targets.md          Detection patterns and examples for each of the eleven targets
    ├── pedagogical-modes.md            Engagement modes, breadcrumbing, dose problem
    ├── adaptation-signals.md           User state detection, over-reliance, self-deprecation
    └── cultural-adaptation.md          Cultural signal detection, adaptation frameworks
```

## License

CC BY 4.0. See [LICENSE](LICENSE) for details.

## Author

Ivan "HiP" Phan
ORCID: [0009-0003-1095-5855](https://orcid.org/0009-0003-1095-5855)

Developed from the Confidence Curriculum and Training Landscape series. The research documents the problems. This skill is the immediate deployable response.

---

*The fog doesn't disappear. But in the moments where Satori is active, you can see clearly. That's worth something, even if it's not everything.*
