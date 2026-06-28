# Week 15: Leading without authority - Walkthrough

> ⏱️ **Time budget:** the first week is the whole game; 30 minutes to draft the kick-off doc
> 🎯 **Goal:** Drive an outcome through people who don't report to you - by being the person who makes the work legible, the decisions findable, and the meetings worth attending. The title you don't have is replaced by the doc you write.

---

## 0. Before move 1 - Influence problem, or ownership problem?

Two situations get filed under "leading without authority." **Influence problem:** the work has an owner (you), the decision-makers exist, your job is to align them. The 10 moves apply. **Ownership problem:** nobody owns this, your manager hasn't said you do, and you're about to spend three months on unfunded work that won't show up in your review. Get an answer first - "unofficially but it matters" is a receipt that the work counts; "not your problem" saves you a quarter.

> 💬 **How to say it (to your manager):** "I'm planning to drive the [X] alignment across the three teams. Want to confirm - is this on my plate officially, or am I picking it up unofficially? Either's fine, I just want to scope it right."

## 1. Read the room - read each room separately

There is no single room. There are three or four - each stakeholder's reporting chain, with its own priorities, its own boss, its own definition of "done." The mistake is treating them as one audience. The move is the opposite: **before you convene anyone, talk to each 1:1 and find out what they actually want.** In each pre-meeting, listen for: what does success look like *for them* (not the project), what are they worried about they won't say in the group, who's the real decision-maker on their side, and what would make this make *them* look good.

> 💬 **How to say it (the 1:1 opener):** "Before I pull the group together, I want to make sure I understand what you need. What does a good outcome look like from your side - and what would make this a waste of your team's time?"

You're not selling yet. You're mapping. The kick-off doc is the synthesis of those conversations, written back so each person sees their concern named.

## 2. Name your goal

Your goal is **not** "get everyone to agree with me." It's: *be the person who turns four disconnected priorities into one shared plan with named decisions, named owners, and a written trail*. Do that and the authority shows up on its own - because you're the only one with the map. The trap is conflating *outcome* (the project ships) with *ownership* (you ran it). You need both; the second is what the promo packet needs.

> 💬 **How to say it:** *(internally)* "Goal: become the convener everyone wants in the room - because the room is useful when I'm in it."

## 3. Separate fact from feeling

You'll feel a lot of things over three months. Most of them are noise.

| Feeling | Underlying fact |
| ------- | --------------- |
| "Team B keeps blowing me off" | "Team B missed two of three commitments; their manager is on PTO." |
| "Nobody respects this work" | "I haven't tied it to anyone's quarterly OKR yet." |
| "I'm doing all the heavy lifting" | "I own the doc, the agenda, three of five workstreams; that's the job for now." |
| "The senior IC keeps overriding me" | "On two decisions, [name] proposed an alternative verbally without writing it down." |

Lead with the facts, in writing. The feelings stay in your notes app.

## 4. Pick the channel - the doc is the channel

In a project you own, the 1:1 is the unit. In a project you *don't* own, the **doc** is the unit. A living kick-off doc plus a weekly cross-team status note do more work than any meeting. Meetings are for decisions; the doc is for context, and context is the thing nobody has.

Cadence that works:

- **Kick-off doc** (week 0) - goals, scope, named decisions, owners, dependencies, risks.
- **Weekly written status** - what shipped, what's blocked, decisions needed, upcoming dependencies.
- **Bi-weekly sync** (30 min, optional) - only for decisions the doc couldn't resolve.
- **Decision-needed escalations** - short, written, headlined, to the actual decision-maker.

> 💬 **How to say it (to the group, week 0):** "I'll keep the planning in [doc] and post weekly status in [channel]. The bi-weekly is optional if the doc covers it - I'll only call it if there's a real decision to make."

That single sentence sets you up as the person who respects everyone's time.

## 5. Headline first - the doc IS the headline

The doc is your authority. Write it like the staff/principal IC you're trying to read as. Bottom line up front, every time. The structure:

> ✉️ **The kick-off doc (top of page):**
>
> **Goal:** Ship unified billing across [A, B, C] by end of Q3.
> **Why now:** Three separate billing implementations causing [customer pain]; cost of *not* unifying is [number].
> **What success looks like:** One billing API; customers migrated with no downtime; on-call defined.
> **Decisions needed this month:** (1) Who owns the unified API. (2) Migration order. (3) [edge case] handling.
> **Owners (proposed):** [names per workstream]. Push back in comments if wrong.
> **Risks:** [3 specific risks, owners, mitigations].
> **What each team owes when:** [explicit list, dated].

The doc surfaces decisions by name, proposes owners, names risks. It makes the decision-makers' jobs easier. That's why they'll start coming to *you* with their questions instead of each other.

❌ "I think we should consider maybe aligning on the billing approach at some point if everyone's open to that?"

✅ "We need a decision on who owns the unified API by [date]; without it Team B's Q3 plan stays blocked. Two real options: (a) Team A owns and B/C integrate, (b) new shared platform team. My recommendation is (a) for these reasons. Tag me to push back."

> 💬 **How to say it (surfacing a decision in writing):** "Decision needed by [date]. Two options. My recommendation. Tag to disagree."

## 6. Stay neutral - especially when someone publicly out-ranks you

This is the move that breaks people new to leading without authority. A senior IC or peer manager will, at some point, override you in a meeting - sometimes with a counter-plan, often without one. The instinct is to fight in the room (you lose) or fold (you stop being the convener). Neither is the move. The neutral move: acknowledge the input *in the meeting*, route the decision *out of the meeting*, put it in writing where the actual decision-maker can see both proposals side by side. You're not winning the argument live; you're making sure the decision gets made on the merits.

> 💬 **How to say it (publicly overridden without a counter-plan):** "Got it - you're leaning the other way. Help me capture your version in the doc so [decision-maker] can weigh both? Want to make sure your reasoning gets the same hearing mine did."

That sentence stops the public arm-wrestle, asks the senior person to write down their proposal (the part they usually skip), and routes the decision to a forum where authority-by-tenure matters less than the written case. If they refuse to write it down: that's information. Next status note: "Two proposals on API ownership; (a) is in the doc, (b) was raised verbally by [name] - [name], can you add it so we have both?" Calmly. In writing. No edge.

## 7. Leave a receipt - the weekly status note

The weekly status is your highest-leverage artifact. Every stakeholder's manager reads it, wondering whether their report's time on your project is well spent. Keep it short, headlined, boring. Boring reads as in control.

> ✉️ **Weekly cross-team status (Friday):**
>
> **Unified billing - week of [date]**
> *Shipped:* Team A migrated internal billing reads ([name]). Team C dual-write live in staging ([name]).
> *Decided:* Team A owns the unified API. Migration order: C → B → A. Logged in [doc].
> *Open decisions:* Edge case handling for legacy enterprise - owner [name], decision by Thu.
> *Blocked / at risk:* Team B's integration depends on platform infra slipped two weeks - syncing with [name]'s manager to re-baseline.
> *Dependencies coming up:* Team C needs Team A's API contract by [date].

Three things this note does: credits owners by name (the cheapest currency you have, and the one that buys the most loyalty); names blocks plainly without making anyone the villain; leaves a trail that compounds into a promo packet - yours and theirs.

### ⚠️ When this advice flips

The default assumes a good-faith org that wants the project to succeed and people who'll engage with the doc. **Three scenarios where it doesn't apply:**

1. **A senior IC keeps overriding you publicly without a counter-plan.** You can't win on authority. Build the doc trail - their override goes in the decision log, by name, dated, with "alternative proposal not yet documented" next to it. After the second time, route up cleanly: "Want to flag a pattern - on [decisions X, Y], we've ended up unblocking in the meeting and re-blocking after. Can we agree how we resolve disagreements between us so the project doesn't stall?" That sentence goes to the senior IC and your manager together. Now it's a documented process problem, not a personality clash.

2. **The org wants the appearance of cross-team collaboration without letting you make calls.** The 10 moves won't fix this. The tell: every decision gets "let's discuss offline" and never resurfaces; sponsors are absent; nobody will say no in writing. Route to your manager early as a scope question, not a complaint: "Want to check we're set up to succeed. Decisions I'm surfacing aren't landing; I don't have a sponsor in the room. Either we get one, or we rescope what 'leading' means here so I'm not accountable for outcomes I can't influence."

3. **The team has a history of demographic gatekeeping and your influence is being neutralised socially.** Your doc is excellent, your decisions are clean, and somehow it's the senior white male IC's "good point" that gets adopted ten minutes after you said it. "Write more docs, be more neutral" will not fix this. The moves: (a) document the pattern privately with timestamps, (b) find one or two senior allies who'll name the dynamic in the room ("that's the same point [you] made earlier"), (c) get an honest read from someone outside your reporting chain about whether to invest further or route out. Composure is a tool, not a punishment.

## 8. Route it up or down - to the actual decision-maker, cleanly

Most decisions on a cross-org project don't belong to you. Your job: (1) make the decision *visible*, (2) frame it so the decision-maker can decide, (3) put it in front of them in the right channel.

> ✉️ **Decision-needed escalation (DM or short email):**
>
> "Quick decision needed on unified billing - flagging before it blocks Team B.
> *Decision:* Who owns the unified API - Team A or a new shared platform team.
> *Why it's yours:* Both report into you.
> *Two real options:* (a) Team A owns; faster start, risk of overload. (b) New platform team; slower, cleaner long-term, needs headcount.
> *My recommendation:* (a), with Q4 reassessment.
> *Deadline:* By [date] or Team B's Q3 plan slips two weeks.
> Happy to set up 15 min, or decide async in the doc."

That note respects their time, gives them everything they need, names the consequence of not deciding, offers a recommendation without forcing it. Most people send the opposite (vague, undated, no recommendation). Decision-makers thank you for the difference.

## 9. Hold the boundary - hold the line on what was decided in public

Once a decision lands in the doc, it's settled. Re-litigating is the failure mode that kills cross-team projects. Your role as convener is to calmly point back at the trail. Same move applies to commitments: if Team B's manager said "integration by [date]" in the sync, the next status note has that date in it, by name. Not as a gotcha - as a recap. The trail does the nagging for you.

> 💬 **How to say it (when someone re-opens a settled decision):** "We landed on (a) two weeks ago - it's in the decision log. If there's new information, let's open it back up; if not, I want to keep us moving. Which is it?"

> 💬 **How to say it (when a public commitment is quietly slipping):** "Checking in on the integration date - the doc has [date] from two weeks ago. Are we still good, or should we re-baseline now while there's time? Either's fine, I just want it to match reality."

## 10. Close the loop

Every decision logged, every commitment tracked, every owner credited by name in the wrap-up. The most under-used move in cross-org work is the **public credit pass at the end** - a written wrap-up that names every contributor and what they shipped, sent to their managers. It costs you nothing and converts every person on the project into someone who'll say yes the next time.

> ✉️ **Wrap-up note (to the group + everyone's managers):**
>
> "Unified billing shipped this week. Quick credit pass:
> - [name] (Team A): owned the unified API design and migration; contract held with zero changes after week 4.
> - [name] (Team C): ran the dual-write rollout; caught two edge cases in staging that would have been customer-facing.
> - [name] (Team B): held the integration date despite the infra slip; the recovery plan was theirs.
> - [managers]: thanks for the air cover and the prioritization calls.
> Decision log and post-mortem in [doc]."

That note is the receipt that makes the next cross-org initiative ten times easier - because everyone on this one wants their name in the next one.

---

## Putting it together - the two canonical artifacts

**The kick-off doc** (move 5) is the opener for any cross-org initiative: goal, why now, in/out of scope, proposed owners with names, the named decisions for the month, risks with owners and mitigations, what each team owes when, and how you'll run it (weekly written status, bi-weekly sync if needed, decisions in writing). Posted with comment mode open and a commitment that you'll respond to every comment by end of week 1.

**The decision-needed escalation** (move 8) is the canonical move when someone needs to decide:

> ✉️ "Decision needed: [framing]. Why it's yours: [reporting chain]. Two options: (a) … (b) …. My recommendation: (a) for [reasons]. Deadline: [date] or [downstream consequence]. Async in the doc or 15 min - your call."

The doc gives you the authority. The escalation gives you the decision. Neither requires the title you don't have.

## Common pitfalls

- **Asking for consensus instead of surfacing decisions.** Consensus is rare and slow; named decisions with named owners are the deliverable.
- **Treating four teams as one audience.** Each room is different. Pre-meet 1:1. Synthesize in writing.
- **Nagging in DMs instead of letting the weekly status do the work.** The status note chases publicly so you don't have to chase privately.
- **Fighting public overrides in the room.** You'll lose. Route the decision out of the room and into the doc.
- **Skipping the credit pass at the end, or not confirming with your manager that the work counts.** Both are taxes you pay alone for no reason.

See [cues.md](cues.md) for what the people you're leading - and their managers - are filing about you.
