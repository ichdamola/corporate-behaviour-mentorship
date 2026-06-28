# Week 10: Pushing back on an unrealistic deadline - Walkthrough

> ⏱️ **Time budget:** one 15-minute 1:1 (or a written tradeoff doc), 30 minutes to build the numbers
> 🎯 **Goal:** Surface the tradeoff cleanly so the decision-maker can choose with eyes open - without becoming the person who said it couldn't be done.

---

## 0. Before move 1 - Reframe what you're actually doing

The mistake almost everyone makes here is framing this as *"I need to say no to the deadline."* That framing loses every time. Leadership doesn't have a "no" button to press; they have customers, board commitments, and quarters to hit. "No" reads as obstruction.

The senior reframe: **you're not refusing a deadline; you're presenting the tradeoff space so the right person can pick.** Scope, time, people - pick two. The decision is theirs. Your job is making sure they can choose without being lied to by the plan.

Hold this reframe through every move below. The minute you start arguing *for* a date, you've taken on a fight that isn't yours.

## 1. Read the room

Three things to read before you open your mouth.

**One: how committed is the date?** A date casually floated in a planning meeting is a different animal from a date that's already in a customer contract or a press release. The first is negotiable; the second isn't, and pushing on it the same way is malpractice. (See *When this advice flips* below.)

**Two: who owns the date upward?** Your manager probably committed to this to *their* boss. That means any pushback you raise lands on them having to walk something back. They have every incentive to want the math now, before they're the one explaining the miss later - they just may not feel it yet.

**Three: what's the room's current emotional state?** If leadership is in "rah-rah, we can do this" mode and you walk in with a spreadsheet, you'll get filed as the team's wet blanket regardless of how right you are. Tone-match the headline; let the math do the cutting.

> 💬 **How to say it:** *(internally)* "What did they actually commit to, to whom, and how locked is it? The pushback shape depends on the answer."

## 2. Name your goal

Be honest about what success looks like. It is **not** "they move the date." It's: *the decision-maker sees the real tradeoff space and picks deliberately.* If they see the tradeoff clearly and still choose the original date with full scope, you've succeeded - and the eventual outcome is their call to own, not yours to absorb.

This is the same reframe as week 02. You're not trying to win. You're trying to make sure the strongest version of the constraint gets heard before the plan locks.

> 💬 **How to say it:** *(internally)* "Goal: surface the tradeoff. Not: get my preferred date."

## 3. Separate fact from feeling

This is the load-bearing move for this situation. Vibes-based deadline pushback ("the team is stressed," "this feels aggressive," "I don't think we can do it") loses every argument with a leader who has a board meeting on Thursday. Specific tradeoffs win.

Build the actual numbers before you open your mouth:

| Feeling | Underlying fact |
| ------- | --------------- |
| "This is impossible" | "Full scope is ~14 engineer-weeks; we have 6 engineer-weeks before the date." |
| "We'll burn the team out" | "Hitting the date as-scoped requires the team at ~60h/week for 7 weeks; last time we did that the regression rate doubled." |
| "Something will slip" | "Of the 4 workstreams, 2 have hard dependencies on the auth migration that doesn't land till week 5." |

The feeling is what made you notice. The facts are what get heard. Bring the table, not the dread.

> 💬 **How to say it:** *(internally)* "Strip 'impossible.' What's the engineer-week math, the dependency, the precedent?"

## 4. Pick the channel

Two stages, two channels.

**The conversation is sync, 1:1, with your manager first.** Never push back on a deadline in the planning meeting itself - that's a public challenge to a commitment your manager already nodded to, and it forces them to defend the date in front of the room. You'll be right and you'll lose. Pull them aside after, or grab a 1:1 slot.

**The receipt is async, written, and structured as options.** The written tradeoff doc (move 7) is the artifact that does the actual work. The sync conversation is where you align on the framing; the doc is what gets forwarded upward.

> 💬 **How to say it:** "Got 15 before the plan locks? Want to walk you through the math on the date - I think there's a tradeoff worth naming before we commit."

## 5. Headline first - the tradeoff, not the verdict

This is the second load-bearing move. **The headline is the tradeoff space, not your opinion of the date.** Bury the tradeoff under context and you've buried the whole point.

❌ "I don't think this is realistic. The team is already stretched and we've got the auth dependency, plus there's the holiday in week 4, and honestly the scope has crept since the kickoff, so I'm worried about..." → You sound like you're complaining. The leader stops listening.

✅ "Quick math before we lock it: at current scope, the date needs about 14 engineer-weeks and we have 6. There are three honest versions of done - I want to walk you through them so you can pick."

The second version does three things in one sentence: it concedes the date is the input (not the enemy), it surfaces the constraint as math, and it hands the decision back to the right person.

> 💬 **How to say it:** "There are three versions of done. Want to walk you through what each one costs?"

## 6. Stay neutral

Tone carries this entire conversation. The same sentence - "the date doesn't reconcile with the scope" - is a career-limiting move if delivered with edge or frustration, and a normal piece of senior input if delivered flat.

Neutral here means: no sighs, no "honestly," no "I've been saying this for weeks," no implied "you should have seen this coming." Just the numbers, once, evenly. The principle from week 02 applies: *clean and factual can't be twisted into "they were being difficult."*

It also means: don't apologize for raising it. Pre-apologizing ("I hate to be the one to say this, but...") signals you think you're doing something wrong, which trains the room to treat the pushback as misconduct rather than information.

> 💬 **How to say it:** "I might be missing context on what's driving the date - happy to be wrong. Based on the scope today, here's what the three options look like."

The "I might be missing context" is not weakness. It's the move that keeps the door open and reminds you to actually ask, because sometimes the date *does* have context you don't have, and finding that out cheaply is better than dying on a hill that doesn't exist.

## 7. Leave a receipt - the tradeoff doc

This is the artifact that does the work. The written tradeoff doc is what gets forwarded to *their* boss, dropped into the planning channel, and remembered six weeks later when the reforecast happens. Build it as three options, each with what it costs.

> ✉️ **The written version (Slack DM or short doc to your manager):**
>
> "Recap from our chat - putting this in writing so we've got a shared frame.
>
> **Target:** Ship [feature] by [date].
> **Constraint:** Current scope is ~14 engineer-weeks of work; we have ~6 before the date.
>
> **Three honest options:**
>
> **(A) Full scope, date slips ~5 weeks.** We ship everything as designed, target [date + 5w]. Cost: customer-facing date moves; need to renegotiate with [customer/marketing/etc.].
>
> **(B) Hit the date, cut scope to the core flow.** We ship [specific reduced surface] on [date]; the [specific cut] ships in the next release. Cost: launch is narrower than the original pitch; we'd need a follow-up plan for the cut surface.
>
> **(C) Hit the date, full scope, accept the risk.** Team at sustained overtime, parallel workstreams without the auth dependency landing first. Cost: based on the last comparable push, regression rate roughly doubles for ~2 months post-launch, and we burn ~1 quarter of team capacity recovering.
>
> Whichever you pick, I'm in - just want to make sure we're picking deliberately. Let me know how you'd like to take it forward."

The doc does five things at once: it concedes the target, surfaces the constraint as math, frames the choice as a choice (not a refusal), names what each option *actually* costs (not just "it's harder"), and ends with a commitment to row. That last line is what separates this from blame insurance.

Notice what the doc *doesn't* do: it doesn't recommend an option. The recommendation is leadership's job. You can have a private preference, but the doc stays neutral - because the moment you push a specific option, the conversation becomes about your opinion instead of the math.

### ⚠️ When this advice flips

The three-options frame is the right default. It assumes the date is a planning commitment, not a fact already in the world. **Four scenarios where the move changes:**

1. **The date is a PR / marketing commitment already shipped to customers.** "Option A: slip the date 5 weeks" is no longer an option - the announcement is out, the press release is published, customers are calibrated. The move is no longer "here are three tradeoffs"; it's *"here's what we'd need to cut to actually make the date."* Same neutrality, but the headline collapses to scope-cut options only. Pretending date-slip is on the table when it isn't reads as out of touch.

2. **The date is a board commitment your CEO can't move.** Don't theatre-push at your level. The math is real but the audience is wrong - your manager can't move this and forcing them to say so makes them look weak. The move: hand them the tradeoff doc privately, frame it as *"if you ever need to renegotiate this upward, here's the math,"* and otherwise execute the closest version of (C) you can stomach. Hill, valley, choose.

3. **The deadline is being weaponised to performance-manage the team.** If the date was set as a stretch to "see who can hack it" and the cost of missing is people, this isn't a tradeoff conversation - it's a different conversation, with HR or your skip-level or someone outside the chain. Don't try to math your way out of it. The composure curriculum's advice ("compose, route, leave receipts") still applies; the *target* changes. You're documenting a pattern, not negotiating a scope cut.

4. **You're junior and the room doesn't yet credit your math.** The three-options doc assumes the reader will trust your engineer-week estimates. If you're new, on a visa, or otherwise under-credited, pair the doc with a senior co-signer before it goes upward - "I walked [staff eng] through this and they had the same read." This isn't weakness; it's recognizing that credibility is a precondition for the math to be heard at all.

Use the default. Note when you're in one of these. The number of "unrealistic deadlines" that are actually one of the flips above is higher than people admit.

## 8. Route it up

This is mostly an *up* move. The decision lives one level above where the tradeoff was surfaced - your manager weighs the three options, picks one, and (often) takes it to *their* boss to confirm the new shape. Your job is to make that upward conversation easy for them: clean doc, no editorialising, ready to forward.

> 💬 **How to say it:** "If it'd help, I can tighten this into something you could forward to [skip-level] directly - your call. Happy to be in the room for the math questions, happy to stay out."

Offering to support the upward conversation *through* your manager - not over them - is the move. Going around your manager to their boss with the tradeoff doc is the single fastest way to torch the relationship, even if you're right.

## 9. Hold the boundary - disagree and commit

Once leadership picks an option, **commit to it fully and visibly.** This is the same move as week 02. If they pick (C) - hit the date, full scope, accept the risk - you don't sulk, you don't slow-walk, you don't tell peers "I warned them." You row, and you row hard.

What you *do* hold is the math. If, two weeks in, the numbers shift - a dependency lands late, a teammate leaves - the tradeoff space has changed and the doc needs an update. That's not relitigation; that's reforecasting honestly. The boundary is between "the decision was wrong" (don't relitigate) and "the inputs have changed" (do resurface).

> 💬 **How to say it (after they pick option C):** "Got it - we're going for full scope on [date], accepting the risk profile. I'm in. I'll keep the tradeoff doc live so we're tracking against the same math, and I'll flag early if any of the inputs move."

## 10. Close the loop

Two versions of closing this loop, depending on how it lands.

**If the launch hits:** don't collect. No "we were lucky," no "good thing we pushed." A clean "we hit it" buys you the credibility to be heard the next time you raise a tradeoff. The senior move is to be *more* gracious when you were nervous and it worked out, not less.

**If the launch slips:** *do not* say "I told you so." Ever. Instead, surface the slip early (that's week 04's whole walkthrough), point to the tradeoff doc as the shared frame, and help solve. The doc protects you naturally - the receipt is there, dated, and nobody has to relitigate who knew what when. That's what receipts are for: they let you skip the blame conversation entirely.

> 💬 **How to say it (if the slip happens):** "Tracking against the original tradeoff doc - we're roughly at the (C) risk profile we flagged. New realistic date is [X]. Here's what I'd cut to get closer to the original."

---

## Putting it together - the canonical tradeoff Slack

> ✉️ "Hey - quick recap from our 1:1 on the [feature] date so we're working off the same frame.
>
> **Target:** [date]. **Constraint:** ~14 engineer-weeks of scope, ~6 weeks of capacity.
>
> Three honest versions of done:
> - **(A) Full scope, date slips ~5 weeks.**
> - **(B) Hit the date, ship the core flow only; defer [specific cut] to next release.**
> - **(C) Hit the date, full scope, sustained overtime + parallel risk. Last comparable push cost us ~1 quarter of recovery capacity.**
>
> Happy with whichever you choose - just want us picking deliberately. Want me to tighten this for [skip-level] or take it from here?"

Headlined the tradeoff, brought the math, named what each option *actually* costs, stayed neutral on the recommendation, committed to the outcome, offered to support upward through your manager. Five short paragraphs.

## Common pitfalls

- **Leading with the verdict.** "This date isn't realistic" before the math is a complaint. The math first; the conclusion draws itself.
- **One option, not three.** A single counter-proposal ("we should move it 5 weeks") is the same shape as a refusal. Three options force a *choice*, which is a different conversation.
- **Vibes instead of engineer-weeks.** "The team is stretched" loses to "6 weeks of capacity against 14 weeks of scope." Always.
- **Recommending an option in writing.** Your private preference is fine; the doc stays neutral. The moment you push (A), the conversation becomes about your opinion instead of the constraint.
- **Pre-apologising for raising it.** "Sorry to be the one to say this" trains the room to treat your pushback as misconduct. Skip the throat-clearing.
- **Routing around your manager.** Taking the tradeoff doc to their boss directly torches the relationship even when the math is right.
- **Collecting on "I told you so" if it slips.** It feels good once and costs you for years. The receipt is the receipt; you don't need to underline it.

See [cues.md](cues.md) for what your manager and skip-level are actually filing about you when you push back on a date.
