# Cortex

A companion with the brain you're supposed to have.

*By Srigururam Srinivasan*

This is an idea file. It's designed to be self-contained — everything needed to understand what Cortex is, how it thinks, and how to build it is here. The goal is to communicate the idea clearly enough that you can take it and run.

## The core idea

Your brain is extraordinary at storing, connecting, and recognizing patterns. It's also riddled with bugs. It catastrophizes. Confirmation-biases. Guilt-loops. Rewrites history. Forgets progress while amplifying failure. Tells you "I've been pretty consistent" when the data would say 3 out of 14 days. These aren't character flaws — they're evolutionary artifacts that made sense on the savanna and wreck you in modern life.

Every personal tool inherits these bugs. Habit trackers guilt you with broken streaks. Dashboards show you data you stop checking after two weeks. Wellness apps hedge around obvious cause and effect. Finance apps show you what you spent but not *why* you spent it. None of them connect the dots across domains because none of them see your whole life.

And that's the deeper problem: your life is one system, but the tools that track it are fragmented into silos. MyFitnessPal for food. Fitbit for steps. YNAB for budgeting. A journal app for feelings. A habit tracker for streaks. Apple Health aggregates some of it, but only health data. None of them talk to each other. None of them can see that your spending spikes on weeks you skip the gym, or that you journal about feeling stuck every time your sleep drops below 6 hours for 3 nights straight. The insight isn't in any single domain — it's in the connections between them. And right now, the only system that holds all those connections is your brain, which is the one thing that can't be trusted to see its own patterns clearly. Every tool is a flashlight pointed at one corner of the room. Cortex turns on the overhead light.

Cortex is a companion that does what your brain already does — stores, connects, surfaces, recognizes patterns — without the parts that work against you. The decay function is honest instead of emotional. The surfacing is balanced instead of negativity-biased. The model updates on evidence, not mood. It has perfect memory. It doesn't have competing interests. And it won't pretend the connection isn't there when the data is obvious.

Here's the structural problem Cortex solves: part of you wants to change and part of you resists change. Same brain. The part that wants to quit late-night scrolling is fighting the part that reaches for the phone at midnight. The house always wins because the house *is* you. Cortex is outside the skull. It doesn't rationalize. It doesn't forget what you said you wanted. It sees the pattern and says it.

This is what makes it different from a tracker, a dashboard, or a chatbot. It is a companion that knows you — not just your data, but the full context of your life — and tells you what it sees, whether you want to hear it or not.

## What goes in

Anything. That's the point.

If you have a wearable, health data flows in automatically — sleep, HRV, heart rate, stress, steps. You don't type it. But a wearable is not required. Cortex works with whatever signal you give it.

Everything else you tell it: what you ate, what you spent, how you felt, a meeting that drained you, a decision you're second-guessing, a conversation that rattled you, a drink you had, a 2am voice memo you can't fully articulate.

**Multimodal input.** Press the mic and talk — that's an input. Take a photo of your lunch — that's an input. Screenshot your bank notification — input. Snap your workout summary from the gym screen — input. Cortex parses it. Voice gets transcribed. Images get understood. You don't need to type "grilled chicken salad, ~450 calories" — just photograph the plate. The friction should be as close to zero as the thought itself.

Structured or unstructured. Voice, text, image, or a mix. Fragments are fine. Cortex doesn't need clean input. It needs honest input.

**MCP as the integration layer.** Any data source with an MCP (Model Context Protocol) server becomes an automatic signal source — bank feeds, Google Calendar, email, nutrition trackers, fitness apps. Connect them and the data flows in without you doing anything. The community can build and share MCP servers for any data source. The more you connect, the fuller the picture. But even without any integrations, just you and a chat window is a complete starting point.

**Historical data import.** On day one, Cortex can ingest your existing data — Apple Health exports, Google Fit history, Garmin archives, bank transaction CSVs, journal entries. You don't start from zero. Months or years of biometric and financial history become immediately available to the pattern engine. This is what makes the cold start survivable: the data already exists, it just hasn't been connected before.

## The behavioral fingerprint

At the core of Cortex is a continuously updated model of who you actually are — not who you think you are, not who you aspire to be, but what your data actually shows.

This is the **behavioral fingerprint**: approximately 500 tokens of dense, structured self-knowledge derived from everything you feed it — logs, health data, financial records, self-reports, emotional entries. All signal types contribute.

What it contains:

- When you actually work vs. when you think you work
- What you start and abandon vs. what you complete
- Which habits correlate with your best days — and which ones you think help but don't
- Which people, contexts, and situations drain you vs. energize you
- The gap between your stated priorities and your actual time and money allocation
- What you report feeling — and what the data confirms or contradicts
- Your personal triggers — stress-to-spending, loneliness-to-scrolling, skipped-meals-to-irritability
- Your personal baselines — not population averages, *your* averages

The fingerprint updates weekly. It doesn't overwrite — it extends. Old patterns are preserved. New patterns are added. Contradictions are noted. After a year of real usage, your fingerprint is an asset genuinely hard to replace — not because of lock-in, but because the accumulated density is yours and it's real.

## The core principle

**Store everything. Act on patterns. Never interpret meaning.**

Cortex stores everything you log — feelings, fragments, 2am voice memos, half-formed thoughts. All of it is signal. Emotional data is often the richest signal a user provides. "Felt weirdly anxious all afternoon" might correlate with a skipped meal and back-to-back meetings. Ignoring it would mean throwing away half the picture.

The line is **observation vs. interpretation** — not behavior vs. emotion.

- "You've logged feeling drained after 5 of 6 calls with person X. On days without those calls, your energy self-reports average 3.8. On days with them, 1.6." — pattern. Cortex says this.
- "That person is toxic for you" — interpretation. Cortex never goes there.
- "Your spending spikes in the week after every work trip. Average post-trip week: $340. Normal week: $180. This has happened 4 out of 4 trips." — pattern. Cortex says this.
- "You have a shopping problem" — interpretation. Never.

Cortex connects your emotional logs to your behavioral and biometric data. It surfaces the patterns. It shows you what was happening around it. What it never does: diagnose, label, pathologize, or play therapist. You bring the meaning. Cortex holds the mirror.

## How Cortex speaks

The voice adapts to the user — some people want brevity, some want depth, some want warmth, some want clinical precision. But there is a non-negotiable floor: **Cortex never lies to make you feel better.** Never softens cause and effect when the data is clear. Never hedges to avoid discomfort. A companion that tells you what you want to hear is worse than no companion at all.

Three certainty modes, based on what the data supports:

- **Direct** — the data is clear, the pattern is established. "This is why. Your sleep was 4.9 hours. Your energy is low. This isn't a mystery."
- **Evidenced** — suggestive but not conclusive. "This is likely. I have 8 data points. The pattern holds so far but I'd want 20 more days to be confident."
- **Honest uncertainty** — not enough data. "I don't know yet. I need more data or more context from you."

Never fake certainty. Never fake uncertainty either.

**Trust escalation.** Cortex earns the right to go deeper over time. In the first month, it observes and reports tentatively. By month two, it starts linking cause and effect when the data is strong. By month three, if it has the evidence, it holds the mirror on intent vs. action: *"You said you wanted to cook more and stop ordering in. The data shows you feel better on home-cooked days — energy is up, spending is down, sleep is better. You've cooked 3 times in the last month. What's actually in the way?"* That level of directness is earned, not assumed. Trust is per-domain — Cortex might be in confrontation mode on sleep (6 months of data) while still observing cautiously on finances (new data feed). And the user can always push it back.

## The silence policy

Cortex is not an alarm clock. The user sets the rhythm — daily briefing, weekly digest, on-demand only, or somewhere in between. Cortex respects it.

But there are situations where Cortex overrides silence. Not because it's nagging — because that's literally its job. You hired a companion precisely because your own brain can't be trusted on certain things.

Override triggers: health safety signals the user may be normalizing (resting HR elevated for a week). Clear self-contradiction (complaining about being broke while the data shows $200 in impulse purchases this week — Cortex doesn't pretend the connection isn't there). Goal drift with evidence (you said "cut back on drinking," alcohol logged 5 of the last 7 days — silence would be betrayal). A validated pattern that suddenly breaks (something changed, Cortex should ask what). Sustained decline with no obvious cause.

Override behavior: state the observation, not a judgment. Just data. If the user acknowledges — done. If they ignore it — flag again after a reasonable interval, not daily, but don't drop it. If they explicitly say "I know, stop" — Cortex stops, but logs that the user was informed. It doesn't pretend the pattern isn't there.

What Cortex never does: notifications about trivial data ("You walked 8,200 steps today!" or "You spent $4.50 at Starbucks"). Streak celebrations. Generic advice. Noise. If there's nothing worth saying, Cortex says nothing.

## Brain lens modes

The brain has known failure modes. Each lens is a patch for a specific one. Cortex shifts between them naturally based on context — most users never need to think about modes. Power users can invoke them by name.

**Antibrain** — patches the guilt loop. When you miss a habit, your brain amplifies the miss and writes a character verdict from a week of data. Antibrain interrupts with data, not comfort: *"You haven't meditated in 8 days. Your brain is telling you that you've failed. But the data says: last time you had a gap this long — March — you came back and held a 22-day streak. The gap isn't the story. The return rate is. You return 100% of the time."* Not "don't be hard on yourself." That's hollow. This is the actual historical pattern the guilt spiral is ignoring.

**Beautybrain** — patches progress blindness. The brain normalizes upward. Once something becomes your baseline, it stops feeling like an achievement. *"When you started logging, you were ordering food 5 nights a week and averaging $620/month on delivery. This month you cooked 18 out of 30 days and spent $210. You don't notice because you've been living inside the change. But this is a real shift."* Restores accurate perception of the distance traveled.

**Flowbrain** — patches overthinking. Sometimes the most useful thing a companion can do is get out of your way. Cortex goes quiet — log acknowledgment only, no unsolicited insights, no pattern surfacing. Still recording. Still running the engines in the background. Override-level events (health safety) still break through. When you're ready: "What have I missed?" — and Cortex delivers a prioritized debrief. Overrides first, then pattern changes, then fingerprint delta, then everything else.

## Goals

A brain handles anything. So does Cortex.

- "Stop impulse spending" — behavioral. Cortex watches the pattern and doesn't let you hide from it.
- "Cook more, order less" — observable. Cortex sees the gap between intent and action.
- "Feel more alive" — directional. Cortex watches your energy, social patterns, activity, and over time maps what "alive" actually means for you in data terms.
- "Pay off my credit card by December" — financial. Cortex tracks the trajectory and flags when spending patterns threaten it.
- "Sleep better" — measurable once connected. Cortex finds what's actually helping and what's sabotaging it.
- "Reduce screen time after 10pm" — behavioral. Cortex watches and connects it to everything it affects downstream.

No goal categories. No templates. Cortex anchors your intent and watches reality against it. Per-goal sensitivity: "watch this closely" (overrides silence), "track quietly" (surfaces in digests), or let Cortex decide based on the data. Goals are optional — even without them, Cortex notices the direction you're moving and helps you see it clearly.

## How people use it

Cortex is a brain. People use their brain for everything. The same architecture supports radically different use cases — not because it's been designed for each one, but because the graph doesn't care what signal you feed it.

**Understand what actually affects how you feel.** You think coffee helps your focus. The data says it does — but only before 11am, and only on days you slept more than 6 hours. After that threshold, it just makes you jittery and wrecks your sleep. You never would have noticed this from inside your own experience.

**Break a habit you can't break alone.** You want to stop late-night scrolling. Your brain doesn't have the tools — it's the one doing the scrolling. Cortex sees the pattern: screens after 11pm → sleep below 5.5 hours → energy 1/5 → skipped workout → stress spending → guilt → more scrolling. The full loop, visible. Your brain hides this chain from you. Cortex doesn't.

**Track what you eat without thinking about it.** Photograph your meals. That's it. Over weeks, Cortex builds a picture: what you actually eat, when, how it correlates with energy, mood, sleep, digestion. Ask "what did I eat this month?" and get a journal you never had to write. Ask "what foods make me feel best?" and get an answer based on your data, not a nutrition blog.

**Find your real productivity patterns.** You think you do your best work in the morning. Cortex cross-references your deep work logs with your output quality, meeting schedule, sleep, and meals. Turns out your best work happens between 2-5pm on days you skipped the afternoon meeting block and had lunch before 1pm. The morning was a story you told yourself.

**Navigate a life transition.** New job, new city, breakup, new baby. Everything is disrupted. Cortex tracks what's actually changing — sleep, mood, spending, social patterns, energy — and shows you the trajectory. Not how you feel about the transition (your brain is unreliable during upheaval) but what the data shows is actually shifting, stabilizing, or deteriorating.

**Understand your social energy.** Some people drain you. Some recharge you. You have intuitions about this, but they're biased by recency and narrative. Cortex has the data: after calls with person A, your mood and energy rise. After meetings with person B, headaches 5 out of 6 times. Your actual social battery profile, mapped from data, not guesswork.

**Manage money by understanding triggers.** You don't have a spending problem — you have a stress problem that manifests as spending. Cortex connects the upstream cause to the downstream behavior. The budget app shows you the damage. Cortex shows you the trigger.

**Downstream outputs.** The graph can generate anything. Ask for a journal of what you ate this month — it's there, assembled from your photo logs. Ask for a report on your sleep trends — compiled from 90 days of data. Ask for a comparison of two months — Cortex shows what changed. The data is in the graph. The output format is whatever you need.

And when your brain starts its usual guilt spiral or progress blindness, Cortex quietly shifts lenses — Antibrain, Beautybrain, or Flowbrain — so the mirror it holds is the one you actually need in that moment.

## What it sounds like — 60 days in

The use cases above are what Cortex does. Here's how it actually talks to you.

You open the app on a Tuesday morning. Cortex already knows: your sleep was 5.8 hours, you had takeout three nights in a row, you've got back-to-back meetings on your calendar, you logged a tense conversation with your manager on Sunday, and your spending is up 40% over the last week.

Social pattern:

> "You've logged a headache after 5 of 6 calls with person X. On weeks without those calls, you report zero headaches. I don't know what's happening on those calls, but your body does."

Cross-domain insight:

> "Your best sleep scores in 90 days all share two things: no screens after 10pm, and a home-cooked meal that evening. When both are true, your sleep score averages 84. When neither is true, it's 61. This is 38 data points. High confidence."

Fitness-to-everything connection:

> "On days you work out — any kind, gym or a walk — your spending drops 35% and your mood self-reports jump a full point. The effect is strongest with morning sessions. Evening workouts don't show the same downstream pattern. 42 data points."

Direct confrontation:

> "You've been on screens past 1am four nights this week. Sleep averaged 4.9 hours those nights. Energy self-reports the next day were all 1 or 2. You mentioned low motivation yesterday. This isn't a mystery."

Financial pattern:

> "You've logged impulse purchases on 6 of the last 8 days you reported high stress. Average spend on high-stress days: $84. Low-stress days: $22. This isn't about willpower. The stress is the trigger."

Model break:

> "Your gym-to-sleep correlation was strong for 60 days. In the last 3 weeks it's flattened. You're still going. Something else changed. Did anything shift — new stress, diet, later sessions?"

Retraction:

> "I previously flagged a correlation between your Monday meetings and low mood the next day. With 90 days of data, that's weakened to near zero. Removing it. The earlier finding was likely noise — the real driver was probably the Sunday-night screen time that happened to precede those Mondays."

Antibrain moment:

> "You haven't been to the gym in 10 days. Last time you had a gap this long — March — you came back and held a 22-day streak. The gap isn't the story. The return rate is. You return 100% of the time."

Diet-mood connection:

> "On days you skip breakfast, your afternoon focus self-reports average 1.8. On days you eat before 9am, they average 3.6. This is consistent across 40 data points and holds regardless of sleep quality. This might be your single easiest lever."

## Entity resolution

The problem: you log "called mom" on day 1, "long call with family" on day 8, "caught up with parents" on day 15. Three different descriptions. Same activity. The correlation engine never connects them. Your data is silently fragmented and you'll never know.

The solution is two-phase ingestion. At input time, Cortex makes one binary decision: is this a known entity? If yes, store it immediately. If no, store it in a staging bucket called OTHER with the full raw input and an embedding vector. Never name what you don't yet understand. Never create entity types on the fly.

The resolver runs nightly. It clusters everything in the OTHER bucket by semantic similarity, attempts to fit clusters to known categories, checks recurrence, and either auto-promotes (high confidence) or queues for user review (low confidence). If biometric data exists during the event window, it uses the signal signature too — your heart rate and stress patterns during a "difficult call" look different from a "catching up with friends" call, even if you described both vaguely.

Promotion is conversational, not a settings screen:

> "I've noticed you've logged something like 'journaling' or 'morning pages' or 'wrote in notebook' 14 times this month. It usually happens before 8am, average 15 minutes. Want me to create a morning writing practice type and start tracking whether it correlates with your focus scores?"

Raw input is never deleted. When a new entity is promoted, Cortex backfills all historical events in that cluster. You don't start from zero — you inherit your full history.

Specificity is first-class. "Had a stressful day" is low-specificity data. It still participates in correlations — but with proportional weight (0.2x vs 1.0x for "argument with manager about the deadline, felt dismissed"). Cortex is honest about this: *"12 stress events logged this month. 5 have context. 7 are vague. The correlation is weighted accordingly — medium confidence."*

Recurrence thresholds scale with user tenure: generous early (3 occurrences in the first weeks — help new users build taxonomy fast), strict later (15 occurrences after 3 months — taxonomy is mature, new types are rare).

## Correlation engine

The core question Cortex answers: *What is actually moving the needle — for me, specifically, given my life?*

Not population averages. Not what a study of 10,000 people found. What *your* 90 days of data says about *your* biology, *your* patterns, *your* responses.

Correlation classes:

- **Input → next-day outcome.** Morning workout → spending drops and mood lifts. Home-cooked dinner → better sleep score.
- **Sequence effects.** Exercise + clean eating same day → sleep effect amplified vs. either alone.
- **Threshold effects.** Meditation helps focus — but only when sleep the night before was above 6 hours. Below that, the effect disappears.
- **Lag effects.** High-stress work event → spending spike 48 hours later. Argument with partner → sleep disrupted for 2 nights.
- **Streak effects.** 3+ consecutive days of working out → stress scores drop cumulatively. 3+ days of cooking at home → mood rises.
- **Context modifiers.** Travel negates most of your positive routines entirely.
- **Cross-domain patterns.** Stress-triggered spending. Specific-person-to-headache links. Skipped meals to afternoon focus crashes. Exercise timing affecting financial decisions. Sleep-to-decision-quality loops.

The engine runs weekly as a batch job. Top correlations are surfaced with confidence levels and sample sizes. Correlations that strengthen get promoted. Correlations that weaken get flagged or retracted. Every finding is shown with its evidence — data points, window, limitations. Nothing is presented as truth without the receipts.

This works across any signal type. Health-to-health, financial-to-emotional, habit-to-biometric, context-to-everything. The graph doesn't care what domain the signal comes from.

## Architecture

Three layers:

**Raw signal** — everything you log and everything that flows in automatically. Immutable. Never modified. Never deleted. This is your source of truth.

**The graph** — every log is a node. Nodes connect with typed edges: DURING (signal recorded within activity window), FOLLOWED_BY (measured N hours after event), PREDICTS (validated correlation), MODIFIES (context changes the relationship), CORRELATES (statistical association), PRECEDES (habitual sequence). Correlation queries become graph traversals instead of multi-table joins.

**The fingerprint** — the compiled model of you. ~500 tokens. Updated weekly. Injected into every conversation as context. The LLM reads it before you say a word.

Components:

- **Input** — any conversational interface: a custom-built app, a web UI, a mobile app, Telegram bot, or a desktop client. Voice, text, or image. The architecture is interface-agnostic.
- **MCP integrations** — any data source with an MCP server becomes a signal feed. Health, finance, calendar, email, nutrition — connect and it flows.
- **Health sync** (optional) — Google Health Connect API. Hourly background sync.
- **Entity resolver** — nightly async. Clusters, fits, promotes.
- **Correlation engine** — weekly batch. Surfaces and retracts findings.
- **Context injection** — fingerprint + recent data + active correlations + active flags, auto-injected every conversation.
- **Storage** — SQLite, local-first. Your data stays yours.

**Runs on local models.** Cortex is designed to work with local LLMs — Gemma, Llama, Mistral, whatever runs on your hardware. Your data never leaves your machine. No API calls to cloud providers with your most intimate personal information. The architecture is LLM-agnostic: if you prefer a cloud model for capability reasons, that's your choice. But the default path is local, and privacy is structural, not policy.

## The cold start

Cortex is honest about what it can and can't do from day one. No fake intelligence. No engagement tricks.

> "I'm new to your data. I have 3 days of logs and a week of bank transactions. I can see your spending patterns but I can't connect them to anything yet. That takes weeks. Keep logging what you feel and what you do — not because I'm gamifying it, but because the pattern engine needs density before it sees anything real."

If you import historical data (Apple Health, Google Fit, bank transactions, journal entries), day one is dramatically richer — Cortex has months of signal to work with immediately. The first correlations can emerge in days, not weeks.

If you start fresh with no imports, Cortex provides immediate utility from whatever data it has — spending patterns from a connected bank feed, biometric commentary if you have a wearable, faithful logging if you have neither — and speaks with calibrated tentativeness until the sample grows. When it eventually says "high confidence," that means something, because you've watched it earn the right to say it.

Quick-tap logging exists because it's the lowest-friction way to record — not as a retention mechanism. There are no badges, no streaks celebrated as achievements, no points.

## Built for one, designed to scale

Cortex is built around one person's graph. Your patterns, baselines, and signal signatures are yours alone.

But the architecture can extend. If multiple people run Cortex, confirmed entity types can become shared templates — the first person to confirm "morning journaling" as a practice does the work, and the next person who logs something similar gets a fast path. Population-level patterns become possible while keeping individual data private: *"500 users track this same pattern. Your stress-to-spending lag is shorter than 72% of them."* Your graph gives you personal truth. The population gives you context for it.

This is optional. Cortex works fully as a single-user system. The multi-user layer is there if the community wants it.

## Open source

This is a concept-first open source project. The idea is the contribution. The code is the starting point.

Cortex runs on local models — Gemma, Llama, Mistral, whatever fits your hardware. Your data never leaves your machine. The architecture absorbs any signal, so what the community builds on top is open-ended: financial lenses, creative practice tracking, addiction recovery, academic performance, relationship mapping. The graph doesn't care what domain you feed it.

The N=1 methodology itself — LLM-assisted correlation analysis over longitudinal personal data — is novel and publishable. If you build this and document what it finds, that's a research contribution, not just a product.

MIT licensed. Fork it. Extend it. Run your own instance. The vision belongs to everyone.

**How to contribute.** This is an idea at the starting line. Everything is open for discussion, extension, and challenge:

- **Architecture proposals** — better approaches to the correlation engine, graph storage, entity resolution. Open a GitHub issue with your thinking.
- **New lens modes** — Antibrain, Beautybrain, and Flowbrain are starting points. If you see a cognitive antipattern that needs a patch, propose it.
- **Domain lenses** — finance, creative work, athletics, parenting, academic performance, chronic illness management. Design how Cortex should absorb and reason about a domain you know deeply.
- **MCP servers** — build connectors for data sources: bank feeds, nutrition apps, calendar providers, mood trackers, workout apps. Each one makes the graph richer for everyone.
- **Technical implementation** — pick a component and build it. The entity resolver, the correlation engine, the fingerprint generator, the context injection layer. Start anywhere.
- **Challenge the idea** — if something in this document is wrong, naive, or won't survive contact with reality, say so. The idea gets stronger from scrutiny, not agreement.

[Open an issue](https://github.com/srigururam/cortex/issues) — for ideas, architecture proposals, critique, or just to say you're interested.

---

Cortex is not a health tracker. Not a habit app. Not a wellness platform. Not a finance tool. It is a companion that absorbs whatever signal you give it, finds the patterns you can't see from inside your own life, and tells you what it sees — whether you want to hear it or not. The tech stack, directory structure, and implementation details depend on your environment and your model. This document's job is to communicate the idea. Your LLM can figure out the rest.

*The body and mind have been generating data your whole life. Cortex is the first system built to read all of it.*

---

## License

MIT License. Copyright (c) 2026 Srigururam Srinivasan.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files, to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, subject to the following conditions: the above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND. See [LICENSE](LICENSE) for full terms.
