# Week 04: Delivering bad news / a missed deadline - Walkthrough

> ⏱️ **Time budget:** 10 minutes to draft the heads-up, sent today
> 🎯 **Goal:** Surface the slip early enough that your manager can reforecast upward, with enough specifics that they don't have to chase you - and without absorbing accountability that isn't yours or shedding accountability that is.

---

## 0. Before move 1 - Is it actually going to slip?

Don't deliver bad news that hasn't happened yet. "Probably won't make it" and "won't make it" are different messages, and your manager will treat the first as a soft yes. Spend 20 minutes confirming: is the remaining scope real, is there a credible cut that ships Friday, what's the actual new date. *Then* send - by end of day, not end of week.

> 💬 **How to say it:** *(internally)* "80%+ sure this slips? Send today. 50%? Finish the check first."

## 1. Read the room

Your manager committed a date upward. That commitment is now wrong, and you're the one who knows it first. They will need to reforecast to *their* boss - every hour you sit on this is an hour stolen from their ability to do that cleanly. They're not (mostly) angry that the work slipped; they're angry, if they're angry, that they got surprised. **Surprise is the actual failure mode in this scenario.** "It's not my fault" may be true and is irrelevant for the next four hours - blame-allocation belongs to the retro next month, not your manager today.

> 💬 **How to say it:** *(internally)* "They need this in time to manage their up. Surprise is the failure. Blame is later."

## 2. Name your goal

Your goal is **not** "confess." It's not "explain." It's: *give your manager everything they need to reforecast upward, in one message, with a recoverable plan attached.* If they can forward your note (or paraphrase it) to their boss with two edits, you've won the move. That reframe is what keeps you out of the apology spiral - which is for you, not them. They don't need your guilt; they need a new date and a smaller scope.

> 💬 **How to say it:** *(internally)* "Goal: they can reforecast upward by end of day, with what I send them."

## 3. Separate fact from feeling

The feeling is dread - some mix of "I let them down" and "this is going to look bad on me." Strip it. The facts are bounded:

| Feeling | Underlying fact |
| ------- | --------------- |
| "We're so behind" | "Two of the five workstreams are done; the auth piece needs ~6 more working days." |
| "Everything's on fire" | "The blocker is the third-party SSO sandbox returning 500s since last Thursday; ticket open with vendor." |
| "I should have flagged this sooner" | "I had a soft signal last Tuesday and a hard signal yesterday." |

The facts are calm. The dread is loud. Lead with the facts.

> 💬 **How to say it:** *(internally)* "What's the new date, what's the blocker in one line, what's the recoverable scope?"

## 4. Pick the channel

Slack / Teams DM to your manager, **today**, in writing. Not a calendar invite for tomorrow ("can we talk?" is the worst possible preview - they spend the night assuming it's a resignation). Not a wait-for-the-1:1 on Thursday - by Thursday they've already re-promised the date internally.

Written, async, fast. They can read it twice, you get a receipt, and they get something they can paraphrase upward without scheduling a meeting. If they want to talk after, they'll grab you - and the live conversation is grounded in facts you already wrote down.

> 💬 **How to say it:** *(internally)* "DM, today, written. Not a meeting request. Not next 1:1."

## 5. Headline first

The first sentence is the new date. Not the apology, not the context, not the blocker. **The new date.** Everything else is supporting.

❌ "Hey - so I've been meaning to flag, the auth integration has been a bit of a slog this week, the SSO sandbox is being weird, and I just wanted to give you a heads up that things are tighter than I'd hoped and I'm worried about Friday..."

✅ "Heads up - the full feature won't make Friday. New realistic date is Wednesday the 4th. There's a smaller version we can ship Friday if that helps you upward; details below."

Same situation. Completely different signal. The second one your manager can act on in 30 seconds.

> 💬 **How to say it:** "New date is [X]. Smaller version available Friday if useful. Cause and plan below."

## 6. Stay neutral

Two failure modes:

- **The apology spiral:** "I'm so sorry, I really thought we'd make it, I should have flagged earlier..." → reads as panicked, makes your manager manage *your* feelings instead of the slip.
- **The blame-shift:** "The SSO vendor is unresponsive and design changed scope on Monday..." → reads as deflection, even when every fact is true.

Neutral is the cure for both. State the slip, the cause, the new date, the recoverable scope - flatly, once. Cause in one sentence. Don't pre-emptively confess; don't pre-emptively litigate.

> 💬 **How to say it:** "The blocker is the SSO sandbox - vendor ticket open since Thursday. Independent of that, the auth flow itself needed ~3 more days than I'd estimated. New date: Wednesday."

Notice what's *not* in there: "I'm sorry," "I should have," "to be fair," "in my defense." None of those help your manager reforecast.

## 7. Leave a receipt

The DM *is* the receipt - that's why written matters here. Write it so that if your manager forwards it verbatim to their boss, it makes them look like a manager who's on top of things, not one who's chasing their team.

> ✉️ **The written version:**
>
> "Heads up - the full feature won't make Friday. Realistic new date: **Wednesday July 8th**.
>
> **Recoverable scope for Friday (your call):** we can ship the dashboard + the read-only auth pieces on Friday; the write/admin flow lands Wednesday. That covers the demo path if [skip-level] needs to see something.
>
> **What slipped and why:** the SSO sandbox has been returning 500s since Thursday 26th (vendor ticket #4421, no ETA yet). Independent of the vendor, the auth flow needed about 3 more days than I'd scoped - I underestimated the token refresh path.
>
> **What I'm doing:** chasing the vendor daily, building a stub so we're not blocked on them past Tuesday, and de-risking the rest of the auth work in parallel.
>
> Let me know if you want the Friday-cut version or want to hold for the full thing on Wednesday."

Five short blocks. New date up top. Recoverable option. Cause in one paragraph (vendor + your estimate miss, owned cleanly). Plan. One decision request back to them. Done.

> 💬 **How to say it:** *(internally)* "If they forward this verbatim upward, does it make them look in control? Then it's right."

## 8. Route it up - this is the headline move of the week

For most weeks, "route it up" is one move among ten. **This week it's the whole point.** The single biggest mistake in delivering a slip is not how you word it - it's how long you sit on it hoping you'll recover. You won't. The slip's already happened; you're just choosing whether to deliver it on Tuesday with a plan or Friday with an excuse.

Route it up *today*. Your manager's job from here is to reforecast upward; your job is to make that easy. The recoverable-scope option in your message is the gift - it gives them something to *offer* upward instead of just bad news to deliver.

> 💬 **How to say it (in the DM):** "Sending this now rather than waiting for our 1:1 so you've got time to reset expectations with [skip-level] before Friday."

That single line tells your manager you understand their job. It's the senior move embedded in the slip.

### ⚠️ When this advice flips

The default ("own the timeline, route up cleanly, don't blame-shift") assumes a manager who'll absorb the news and own it upward with you. **Three places it breaks:**

1. **Your manager has a pattern of pinning slips on the closest IC.** "Own it cleanly" assumes good faith. If the credit/blame math is rigged - past slips pinned on you, a peer who got scapegoated - keep the neutral framing in the DM *and* keep a private timestamped record of when you flagged the risk. Don't escalate to "for the record" emails; do make sure your own paper trail exists.

2. **Your manager is the wrong person to tell first.** Rare but real: the slip was caused by a decision *they* made (descoped QA, pulled people off), and the version that goes upward will quietly omit that. Don't go around them - that's career-ending. Send the same neutral DM, *and* make sure the cause section names the structural fact ("QA capacity was reduced on June 12th") without finger-pointing, so it survives the retelling.

3. **You're junior, on a visa, or otherwise structurally under-credited.** "I underestimated the token refresh path" reads as gracious ownership from a senior IC and as confirmation of incompetence from someone whose competence is already discounted. Substitute: *"the token refresh path was more involved than the original scoping suggested"* - same fact, no self-deprecation handle.

Use the default. Note when you're in one of these. The bad-faith case is not rare.

## 9. Hold the boundary

Your manager may push back - "can we still hit Friday if you push harder / pull in [peer] / cut testing?" This is where slips get *worse*: the panicked yes that promises a date you already know is wrong.

Hold the new date. Once, calmly. If there's a real lever (extra hands, scope cut), name what it actually buys.

> 💬 **How to say it:** "Friday on the full scope isn't recoverable even with another body - the SSO blocker is calendar time, not effort. Friday on the cut scope is solid. Wednesday on the full thing is solid. Picking between those is the cleanest call."

Two solid options beat one shaky promise. Don't re-commit to Friday on the full scope because you feel bad - that's how you turn a one-time slip into a credibility problem.

## 10. Close the loop

Two follow-throughs: **hit the new date** (a slip delivered cleanly and then *also* hit reads as a one-time miss with a clean recovery; slipping again reads as a pattern), and **send a short retro note unprompted** a week later. One paragraph: what you learned about estimation, the process gap you're closing, no drama.

> ✉️ **The retro note (sent a week later):**
>
> "Quick retro on the auth slip while it's fresh: the token refresh path was the big estimation miss - I'd scoped it as a day, it was four. Updating my heuristic for anything touching third-party auth (×3 on first pass). Also adding a 'vendor-blocker' field to our weekly status so we surface external risks earlier."

That note is what gets you the *next* hard project. The slip is forgotten in a quarter; the retro is remembered.

---

## Putting it together - the full DM

> "Heads up - the full feature won't make Friday. Realistic new date: **Wednesday July 8th**. There's a smaller version (dashboard + read-only auth) we can ship Friday if that helps you reset upward; the write/admin flow lands Wednesday.
>
> What slipped: the SSO sandbox has been down since Thursday (vendor ticket #4421). Independent of that, the auth flow needed ~3 more days than I'd scoped. What I'm doing: chasing the vendor daily, building a stub so we're not blocked past Tuesday, parallelizing the rest.
>
> Sending this now rather than waiting for our 1:1 so you've got time to reset expectations with [skip-level] before Friday. Want the cut version Friday, or hold for full on Wednesday?"

New date first. Recoverable option. Cause without blame. Plan. Question back. Done in 110 words.

## Common pitfalls

- **Sitting on it.** Tuesday with a plan is professional. Friday morning with an excuse is a career moment. The single biggest determinant of how this lands is *when* you send it.
- **The apology spiral.** Your guilt is not your manager's problem to manage. State it flat.
- **The blame-shift.** Even when the vendor really is the cause, leading with them reads as deflection. Name the structural fact, own the bit that's yours, move on.
- **Asking for a meeting instead of sending the news.** "Can we talk?" is a worse preview than the actual news. Send the news; offer to talk after.
- **Promising a date you already know is wrong** because your manager pushed. The second slip costs ten times what the first one did.
- **No retro note.** A clean delivery without follow-up is a one-time pass. With the follow-up, it's a credibility deposit.

See [cues.md](cues.md) for what your manager is actually scoring while they read your DM.
