# Take-Home Test: UI/UX Lead

## The challenge in one paragraph

Our **Apply Now** flow is the current Fundo brand. Everything else a customer sees — the website, the portal, our emails, our Instagram — should look and sound like it, and today it does not. **Audit every surface against Apply Now, tell us what is wrong, improve the one flow or page that matters most, say how you would prove it worked, and show how you would own a Fundo design system with AI so it stays consistent.** Deliver it as one short, clear prototype.

**Start here:** open the [Apply Now prototype](https://claude.ai/artifact/KdUR9FzJjbYQ2GZfKCENzJ) and click through it on a phone-sized window. Then do the four parts:

| Part | You deliver | Suggested time |
|---|---|---|
| [1. Audit](#part-1--audit) | A list of the issues you found, ranked | ~2 h |
| [2. Improve](#part-2--improve) | Before and after of one flow or page, in the Apply Now design | ~2.5 h |
| [3. Prove it](#part-3--prove-it) | How you would validate it: interviews, A/B test, analytics | ~0.5 h |
| [4. Design system](#part-4--design-system) | One page: how you would build and own it with AI | ~1 h |

**Expected effort: about 6 hours. Send it within 4 days.** Tell us how long you actually spent. Speed is part of the role, so it is part of the test.

---

## Context

Fundo gives merchant cash advances of $500 to $10,000 to gig workers, freelancers and small businesses: drivers, contractors, salons, food trucks. They apply **on a phone, in a few spare minutes**, and they are deciding whether to trust a company with their bank account and their SSN.

The surfaces a customer meets:

| Surface | Where | Role in this challenge |
|---|---|---|
| **Apply Now** | The [Apply Now prototype](https://claude.ai/artifact/KdUR9FzJjbYQ2GZfKCENzJ), and the first screen live at [app.fundo.com/apply-now](https://app.fundo.com/apply-now) | **The brand reference** |
| Marketing site and blog | [fundo.com](https://fundo.com) (WordPress) | Audit |
| Customer portal login | [portal.fundo.com](https://portal.fundo.com) | Audit |
| Social | [Instagram @fundo_llc](https://www.instagram.com/fundo_llc/), [Facebook](https://www.facebook.com/Fundo-LLC-115005536559629), [LinkedIn](https://www.linkedin.com/company/fundo-llc) | Audit |
| Competitors | Your choice, at least three | Compare |

## The role, and why the test looks like this

This is not a traditional design role. We need one person who owns the experience and the brand of the **whole company** — product UI, UX writing, the website, email, social — and who:

- **researches before designing** and decides what matters most;
- **ships fast, with quality**, using AI tools every day — Claude, Claude Design, Claude Code — to research, design, write and produce code engineers can merge;
- **thinks in edge cases**: errors, slow networks, small screens, accessibility, declined customers, the person who comes back three days later;
- **owns a design system** so that consistency does not depend on one person checking every screen.

---

## Part 1 — Audit

Walk every surface **on a phone**, the way a new customer does. Compare each one with Apply Now. Then tell us what you found.

Look at least at:

- **Brand consistency** — colours, type, logo, spacing, components, imagery, tone of voice. Where does a surface stop looking like Apply Now?
- **UX** — steps, friction, unclear actions, dead ends, error and empty states, mobile layout, accessibility.
- **Words** — clarity, tone, typos, the same thing called by different names, promises that contradict each other.
- **Time** — for each Apply Now screen, estimate how long a customer spends on it and what slows them down: number of fields, reading, decisions, looking for a document. Where would you expect people to drop off, and why?
- **Financial clarity** — this is a financial product. Flag everything a customer needs to make a safe decision and cannot find, or cannot understand: cost, repayment amount and frequency, total payback, what happens if a payment fails, eligibility, which states we serve, how fast funding really arrives, what "not a loan" means. Flag claims you think need a legal or compliance check.
- **Competitors** — what do at least three of them do better or worse on the same points?

**Deliver** a ranked list or table. For each issue: where it is, what is wrong, why it matters to the customer or to Fundo, how severe it is, and the evidence (screenshot or link). Put the five that matter most at the top. A long list nobody can act on is worse than a short ranked one.

## Part 2 — Improve

Pick **the one flow or page** that, from your audit, Fundo needs most right now. It can be an Apply Now step, a page of the website, an email, an Instagram post template — your call. Say why you chose it over your second and third choice.

Redesign it **in the Apply Now design**. We want Fundo to look better, not to look like a different company. If you change the design language itself, say what and why.

Show:

1. **Before and after**, mobile first. A few screens, one flow, one page — keep it small.
2. **The words you would ship.** No lorem ipsum. UX writing is part of the job.
3. **The edge cases.** At least: error, slow connection, 360 px screen, screen reader, declined customer, a customer in a state we do not serve, someone who returns later. Design the important ones; list the rest.
4. **How it ships.** What you would hand an engineer — or build yourself with Claude Code — in the first week.

## Part 3 — Prove it

A redesign is a guess until customers tell us otherwise. Tell us, briefly, how you would find out:

- **Before you build** — how you would talk to customers. Who you would recruit, how many, and the five questions you would ask. What would change your mind.
- **The experiment** — an A/B test of your change: the hypothesis, the primary metric, the guardrail metrics that must not get worse (for a lender, more completed applications is not good if they are worse applications), and roughly how long it needs to run at our traffic. Say what you assumed about traffic.
- **The instrumentation** — the events you would track, screen by screen, so we can see time per screen and where people leave. We use Amplitude today for analytics and experiments. If you would add or replace a tool — session replay, surveys, a heatmap, a research platform — name it and say why it is worth it.
- **The result that makes you undo it.**

Half a page is enough.

## Part 4 — Design system

Fundo has no shared design system. Each surface — the Next.js app, the WordPress site, the SendGrid emails, social posts, an internal admin tool — was styled on its own.

On **one page**, tell us how you would build and own one, with AI doing as much of the work as possible:

- **Start from Apply Now.** Extract a first set of tokens from it (colour, type, spacing, radius) and show them. A short list is enough.
- **Beyond tokens** — components, voice and tone rules, content patterns for financial information, accessibility rules.
- **Every surface uses it** — how the same system reaches a React app, a WordPress theme, an HTML email, and a social template.
- **AI in the loop** — how you would use Claude, Claude Design or Claude Code to generate, apply and check it: for example a skill that reviews a screen or an email against the system, or that writes on-brand copy.
- **Keeping it alive** — who changes it, how changes ship, and how you catch drift when someone builds a screen without it.

No code required. A small working example — a token file, a prompt, a skill — is welcome.

---

## The Apply Now prototype

You cannot see the full Apply Now flow without submitting personal data, so we rebuilt it for you: **[Apply Now prototype](https://claude.ai/artifact/KdUR9FzJjbYQ2GZfKCENzJ)**.

- It is the first part of the real flow, rebuilt screen by screen from our production code: email, mobile number, name, income source, business details, home address, date of birth, SSN. The flow continues after SSN with bank connection and the offer; that part is not included.
- It shows the business-owner path. The gig-worker and employee paths, error states and pop-ups are not included.
- Press **Play** on the first screen and click through. The fields work. Nothing you type is sent or saved.
- You can comment on the prototype or duplicate it as a starting point for your own work.

Rules:

- **Public information only.** No access to our systems, data, Figma or code is needed or given.
- **Do not submit an application** on fundo.com or app.fundo.com, with real or invented data. Fake applications reach our underwriting team and our marketing lists. Use the prototype.
- Screenshots of Fundo and competitor pages are fine. No personal data in anything you send.
- **Assumptions are fine.** Where you cannot see something — an email, a screen after SSN — say what you assumed and why.

---

## How to deliver

Pick one format:

| Format | What it is |
|---|---|
| **A Claude artifact or Claude Design project** (preferred) | One shareable link that opens without asking us for access. Interactive is welcome. |
| **A GitHub repository** | Markdown and images. A coded prototype is welcome but not required. |

Open with a short summary: the top issues, the one you improved, and the before and after. Then the four parts. Then **how you worked**: the AI tools you used and for what — research, design, copy, code — a few real prompts, and what the tool got wrong and how you caught it.

### It will be read by a person and by Claude

We review every submission twice: once with Claude, once by people on the team. Build for both.

- **A person must understand the point in two minutes**, from the first screen, without you explaining it.
- **Claude must be able to read every claim.** Put text in text, not only inside images. Give every image a caption that says what it shows. Link every source.

A submission that only works for one of the two loses points.

---

## The debrief

Every submission is followed by a **60-minute live session** with the team. Expect to:

- present your work in five minutes, then defend your choices
- change your mind when we give you a reason, or hold your position with a better one
- take a screen, an email or a post we bring and improve it live with your AI tools, in about 20 minutes, sharing your screen
- explain which parts an AI tool produced, and how you checked them

## What we evaluate

- **Audit** — did you find what really hurts Fundo, with evidence, and rank it?
- **Financial clarity and trust** — do you see what a customer needs to make a safe decision?
- **Craft** — design and words, phone first, consistent with Apply Now.
- **Edge cases** — the states nobody asked for.
- **Research and measurement** — interviews, an experiment with the right guardrails, and the data to read it.
- **Design system thinking** — one brand across product, site, email and social, kept alive with AI.
- **Speed with AI** — how much you delivered for the time, and how well you directed and checked the tools.
- **Clarity** — a person and Claude both get the point fast.

If something is missing, say so rather than rushing it. An honest gap costs less than a confident guess.

Questions about scope are welcome. Reply to the email you received. Send us the link when you are done.
