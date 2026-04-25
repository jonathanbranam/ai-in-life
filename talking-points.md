# Talking Points — AI in My Life

Narration notes for each slide. Aim for ~5 minutes total.

---

## Slide 1 — Hook

"I built a video game with my daughter about an otter."

Let that land for a second. This talk isn't about work — it's about what I've been doing with AI tools on my own time, for fun, and what I learned from it. Some of it worked great. Some of it didn't. And somewhere along the way, I ended up making a game about an otter with my kid.

---

## Slide 2 — Vibe Coding

I started where a lot of people start: just describing what I wanted and seeing what came out. This is what people call vibe coding — low friction, fast feedback, surprisingly good results on small stuff.

It felt like magic. I was building things I wouldn't have built otherwise.

But then the projects got bigger. The codebase grew. And the AI started losing the thread. I'd ask it to change one thing and it would break two others. Context would drift. The code would get tangled in ways that were hard to explain or untangle.

Vibe coding is great until you're not vibing anymore.

---

## Slide 3 — Spec-Driven Development

So I changed my approach. Instead of jumping straight to prompts, I started writing specs first — just plain descriptions of what I wanted to build, how it should behave, what the edge cases were.

The difference was significant. When the AI has a contract to hold itself to, the output is more consistent and the codebase stays manageable. You spend more time building and less time untangling.

It also forces *you* to think more clearly about what you want. Which, it turns out, is half the battle.

---

## Slide 4 — Projects

I built a few things I actually use. Some productivity tools — apps for organizing notes and brainstorming. A time tracker that works exactly how I think about tracking time, no feature bloat, no onboarding.

Nothing production-grade. Just things I wanted to exist that I didn't want to pay a subscription for.

---

## Slide 5 — The Parking Lot

Here's my favorite part of this whole story.

My son was running video at a high school basketball game. I was waiting in the parking lot to pick him up. I had maybe 20–30 minutes.

I opened Claude on my phone and started describing the game I wanted to build with my daughter — a casual game about the life of an otter. Claude would output an HTML file. I'd open it in the browser on my phone, see what it looked like, and send back feedback. No laptop. No dev environment. Just a parking lot and time to kill.

That's the thing about these tools — the barrier is a lot lower than people expect.

---

## Slide 6 — The Otter Game

So my daughter got involved. She started making changes herself — using the chat interface to tell Claude what she wanted.

At one point she told Claude to make the otters look hideous. And Claude did. And she thought it was the funniest thing she had ever seen.

There's something genuinely great about that. She wasn't coding. She wasn't thinking about the AI. She was just playing, and the tool got out of her way.

One honest challenge: because the game was built with Phaser.js — a JavaScript game library that renders to a canvas — the AI couldn't actually see the game or test it. It had no idea what was on screen. So the workflow was: generate code, open the browser, take a screenshot, share it with Claude, iterate. The AI needed my eyes to understand what was happening. Once I figured that out and started doing it consistently, things moved a lot faster.

---

## Slide 7 — Takeaways

Three things I'd tell you to try:

**Start with something purely for fun.** No stakes means faster learning. Build a thing you actually want to exist.

**When vibe coding stalls, write a spec.** The clearer you are about what you want, the better the AI can help you build it. This isn't just AI advice — it's just good engineering.

**The barrier is lower than you think.** A parking lot. A phone. An HTML file. That's enough to get started.
