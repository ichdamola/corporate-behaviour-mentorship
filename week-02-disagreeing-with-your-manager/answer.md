# Week 02: Disagreeing with your manager - Walkthrough

> ⏱️ **Time budget:** one focused conversation, 10 minutes to plan it
> 🎯 **Goal:** Register a real disagreement, get genuinely heard, and stay someone your manager *wants* dissent from - then commit fully whichever way it goes.

---

## 0. Before move 1 - Is the decision actually still open?

This walkthrough assumes the rewrite is leaning, not locked. **Confirm that first.** A surprising number of "we're considering a rewrite" framings are actually "we're announcing a rewrite, softly." If your manager's already committed to this upward - to their boss, to the team in a Slack post, to a public roadmap - the move is no longer "disagree," it's "understand and commit" (skip to move 9). The 1:1 opener for the check is small and non-confrontational:

> 💬 **How to say it:** "Quick one before the rebuild call locks - want to make sure I'm not missing context. Is this still being weighed or has it been decided already?"

If they say "it's decided," your week-02 ends with move 9 and your follow-up move (a clean recap, helpful commitment to the new direction) is the entire performance. Pushing further once the decision is closed turns this from "thoughtful dissent" into "doesn't accept outcomes" - exactly the file the curriculum is trying to keep you out of.

## 1. Read the room

Your manager is leaning toward a full rewrite and seems invested. "Invested" is the key read. People defend decisions they've emotionally committed to harder than decisions they're still weighing - so *when* you raise this matters as much as *how*. The decision isn't final, which means there's still a window. Walk through it before it closes.

Also read: your manager is the one who will defend this decision *upward*. If the rewrite tanks, they own it to their boss. That means they have every incentive to want good dissent now - they just may not feel it in the moment.

> 💬 **How to say it:** *(internally)* "They're invested but not committed. The window is open. They'll thank me later for pressure-testing this - if I do it cleanly."

## 2. Name your goal

Be honest with yourself about the goal. It is **not** "win" or "be proven right." It's: *make sure the strongest version of the counter-argument is heard before the decision locks.* If you've done that and they still choose the rewrite, you've succeeded at your actual job. The rewrite being a mistake is then their call to own, not your cross to bear.

This reframe is what keeps you out of the "I told you so" trap that destroys the relationship.

> 💬 **How to say it:** *(internally)* "Goal: the best counter-case gets a fair hearing. Not: I get my way."

## 3. Separate fact from feeling

You have a feeling ("this is going to be a disaster, I've seen it before") and you have facts. Lead with facts; the feeling is just what generated them.

| Feeling | Underlying fact |
| ------- | --------------- |
| "This'll take forever" | "Comparable rewrites here took ~2 quarters; the refactor path is ~3 weeks." |
| "The current system is fine" | "Current error rate is 0.2%; the pain is readability, which cleanup addresses." |
| "I've seen this fail" | "Two teams attempted full rewrites of similar systems; both shipped late and buggy." |

The facts are persuasive. The feeling is not. Bring the table, not the dread.

> 💬 **How to say it:** *(internally)* "Strip 'disaster.' What's the number, the precedent, the measurable risk?"

## 4. Pick the channel

This is a **1:1, synchronous, private** conversation - never a public thread, never the group channel, never a reply-all dissent. Disagreeing with your manager in front of others, even gently, puts them in a defend-my-authority posture and guarantees you lose. Ask for a few minutes 1:1.

After the conversation, a short written recap is fine (move 7) - but the disagreement itself happens face to face.

> 💬 **How to say it:** "Quick one before the rebuild call locks - want to make sure I'm not missing context. Got 15?"

That opener leads with the work and your humility, not your dissent. The earlier draft ("I've got some thoughts I'd like to think through with you") pre-announces a challenge and hands an insecure manager 15 minutes to load defensive ammunition before you've even started. The shorter form keeps the door open.

## 5. Headline first - but as a question, not a verdict

Here's the counter-intuitive part. With a *peer* you'd lead with your bottom line. With your *manager*, on a decision they're invested in, you lead by **asking, then asserting**. Open by understanding their reasoning before you push on it - partly because you might be missing context, and partly because people will hear a challenge they helped surface.

> 💬 **How to say it:** "Before I give you my take - what's driving the rebuild for you? I want to make sure I'm reacting to the actual reasons, not what I assume they are."

*Then* you headline your concern, once it's grounded in their answer:

> 💬 **How to say it:** "Okay, that helps. My honest concern is the timeline. Here's the math I keep landing on..."

## 6. Stay neutral

Everything in this conversation is carried by tone. The same sentence - "I think the rewrite is a mistake" - is a career-limiting move if it's delivered with edge and a perfectly normal contribution if it's delivered flat and factual.

Neutral here means: no "obviously," no "everyone knows," no sighing, no "I've been saying this." Just the facts and your reasoning, stated once, calmly. The principle: *being right is worthless if you deliver it in a way that makes you look unhinged.* Clean and factual can't be twisted into "they were being difficult."

> 💬 **How to say it:** "I could be wrong about this, and you've got context I don't. But based on what I'm seeing, the refactor path gets us 80% of the benefit in about a fifth of the time. That tradeoff feels worth naming before we commit."

Note the "I could be wrong." That's not weakness - it's the thing that keeps the door open. It signals you're reasoning, not fighting.

## 7. Leave a receipt - as input, not insurance

After the conversation, a brief written summary is good practice - *if* it's framed as collaborative input, not as a paper trail for blame. The difference is everything:

❌ Insurance (toxic): "Per our conversation, I want it on record that I advised against the rewrite." → reads as positioning for "I told you so."

✅ Input (clean): "Thanks for talking it through. Summarizing where I landed so it's captured: refactor gets ~80% of the value in ~3 weeks vs. ~2 quarters; main risk of the rewrite is timeline + the two prior rewrites that slipped. Whatever we decide, happy to help make it work."

> 💬 **How to say it:** Always end the receipt with a commitment to the outcome, not a hedge against it.

### ⚠️ When this advice flips

The "input, not insurance" rule is the right default. It assumes a good-faith manager who'll own the outcome. **Three scenarios where it doesn't apply:**

1. **Bad-faith manager (looking for a scapegoat).** If you have direct evidence - pattern of pinning slips on the closest IC, history of "rewriting history" in retros, peers warning you privately - keep a **personal timestamped doc** of what you raised and when. *Not* an email "for the record" to them; not a Slack post. A private file in your notes app you'd hand to HR or your skip-level if the situation requires it later. The toxic version goes outward; this version stays inward until it's needed.

2. **Power-imbalanced position.** Junior on the team, on a visa, sole IC of your demographic on the team - the math on a tanked rewrite gets pinned on you regardless of who decided. The "I could be wrong about this" hedge that reads as gracious from a senior IC reads as confirmation of incompetence from someone whose competence is already under-credited. Substitute: *"based on what I'm seeing today"* - same epistemic humility, no self-deprecation handle.

3. **Genuinely abusive manager.** If "stay composed, leave a clean receipt, route through them not over them" maps onto a manager who responds to dissent with retaliation, this curriculum's advice is the wrong frame entirely. The move is to document privately, identify a safe escalation path (skip-level, HR, mentor outside your reporting chain), and recognize that "compose first" can become "absorb harm." Composure is a tool, not an obligation.

Use the default. Note when you're in one of these. Don't pretend the bad-faith case is rare - it isn't.

## 8. Route it up or down

Usually this disagreement stays right here, between you and your manager. But name the case where it routes up: if the decision is genuinely high-stakes *and* you believe your manager hasn't surfaced the risk to *their* boss, you can offer to help them do that - never go around them.

> 💬 **How to say it:** "If it'd help, I'm happy to write up the tradeoff cleanly so you've got it for when [skip-level] asks. Your call entirely."

That offers support upward through your manager, not over them.

## 9. Hold the boundary - disagree and commit

This is the move that defines you. Once the decision is made - *whichever way* - you commit fully, visibly, and without sulking. If they choose the rewrite, you do not relitigate it in standups, you do not slow-walk it, you do not say "well, I warned them" to peers. You row.

> 💬 **How to say it (after they decide on the rewrite):** "Got it - we're doing the rewrite. I'm in. Let me think about how to de-risk the timeline so we give it the best shot."

The people who get trusted with bigger decisions are the ones who can disagree hard *and* commit hard. Either one alone is common. Both together is rare and it's the whole signal.

## 10. Close the loop

If the rewrite proceeds and your timeline concern proves right, the senior move is to **not** collect on it. No "told you so," ever. Instead, help solve the slip when it comes. Conversely, if you were wrong and the rewrite goes great, *say so* - "you were right to push for the rewrite, the clean architecture is paying off" buys you enormous credibility for the next time you disagree.

> 💬 **How to say it (if you were wrong):** "Worth saying - I was skeptical of the rewrite and it's clearly the right call. Good push."

---

## Common pitfalls

- **Leading with the verdict.** "The rewrite is wrong" before understanding their reasoning starts a fight, not a conversation.
- **Disagreeing in public.** Any audience turns your manager defensive. Always 1:1 first.
- **Bringing dread instead of data.** "This feels risky" loses to "here's the timeline math."
- **The insurance-policy recap.** Documenting your dissent as blame-cover poisons the relationship even if you're right.
- **Failing to commit.** Relitigating after the decision is the single fastest way to become someone whose input gets ignored.
- **Collecting on "I told you so."** It feels good once and costs you for years.

See [cues.md](cues.md) for what your manager learns about *you* from how you disagree.
