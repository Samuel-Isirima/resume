# Outreach Templates

How to use these:
- **Lead with the live demo, not the pitch.** People who open kuttl.xyz can click the ✦ panel and restyle the site itself. That 20-second experience does more for you than any paragraph. Every template below points them to it.
- **Fill in every `[bracket]` with something specific.** If you can't write one real sentence about their company, don't send it yet.
- **Keep DMs short enough to read on a phone without scrolling.** Ask for one small thing.

---

## 1. Application / Cover Letter (job marketplaces, careers pages, emails)

> Subject: [Role]: I built an AI layer that rewrites React UIs live (kuttl.xyz)

Hi [Name / Hiring Team],

I'm applying for the [Role] position at [Company]. Before you read the rest of this, try something: open **kuttl.xyz**, click the ✦ button in the bottom-right, and type *"make this dark mode with more contrast"*. The page will rebuild itself in front of you.

That's Kuttl, and I built it solo. It's an AI layer that any web app can add with one script tag. It lets end users reshape the interface in plain English: move components, hide what they don't need, turn cards into a table. Changes apply live, without a page refresh, and they stay. Building it meant:

- intercepting DOM operations before paint so there's no flicker,
- hooking into React's fiber reconciler so changes happen at the component level instead of fighting re-renders,
- turning LLM output into structured, validated patches that can be undone, and handling it cleanly when the model gets something wrong,
- running a Go backend that keeps model credentials out of the browser.

It's the kind of problem I like most: hard, poorly defined, and something I'm responsible for from start to finish.

Before Kuttl, I spent 6+ years at early-stage startups doing the same kind of end-to-end work:
- At **Adsit Digital**, I designed the identity-resolution algorithm that generated **80%+ of company revenue**, and the pipeline that processes **billions of records a week**.
- At a **California startup**, I rebuilt the flagship product with a zero-downtime migration. That rebuild was the foundation of the demo behind a **$500K raise**. I ran my own sprints and reported directly to the CEO.

[One or two sentences about *them*: why this company or this problem specifically. Example: "Your move toward AI-assisted workflows in [product] is exactly the problem space Kuttl lives in: making software adapt to the person using it."]

I work remotely (UTC+1) and have 3+ years of experience overlapping with US teams. I can start immediately. I'd love a 20-minute call, and I'm happy to walk through Kuttl's architecture live.

Best,
Samuel Isirima
psalmey01@gmail.com · kuttl.xyz · [LinkedIn] · [GitHub]

> **Short version** (for marketplace text boxes with character limits):
> I built Kuttl (kuttl.xyz), an AI layer that lets users reshape any web app's UI in plain English, live, by hooking into the DOM and React's reconciler. Before that I spent 6+ years at startups: I built the algorithm behind 80%+ of one company's revenue, pipelines that process billions of records a week, and a product rebuild that helped close a $500K round. Try the ✦ button on kuttl.xyz. It restyles the site itself. I'd love to bring that end-to-end ownership to [Company].

---

## 2. DM to a CEO / Founder

Founders care about output and ownership, so emphasize that you ship on your own.

> Hi [Name]. I saw [specific thing: their launch, a post, a hiring note, a product change]. [One genuine sentence about it.]
>
> I'm a senior full-stack engineer, and I just shipped Kuttl solo. It's an AI layer that lets users reshape a web app's UI in plain English. Try the ✦ button on kuttl.xyz: it restyles the site live.
>
> Before that, I built the algorithm behind 80%+ of one startup's revenue, and I rebuilt the product behind another's $500K raise.
>
> If you're adding engineering capacity at [Company], I'd love 15 minutes. If not, I'd still value your honest take on Kuttl.

**Why this works:** it's specific to them, it gives them a demo they can try in seconds, it offers proof of results, and it asks for something small. The last line gives them an easy way to reply even if they aren't hiring.

---

## 3. DM to a CTO / Engineering Lead

Engineers care about how hard the problem was. Lead with the technical challenge.

> Hi [Name]. Quick one from one engineer to another.
>
> I built Kuttl (kuttl.xyz), which lets users rewrite a live React app's UI with a prompt. The interesting part was getting LLM-generated changes to survive React re-renders. I ended up hooking into the fiber reconciler instead of patching the DOM after the fact, and applying vanilla-JS changes before paint so there's no flicker. Click ✦ on the site to see it work.
>
> My background is 6+ years of startup backend and infrastructure work: billions-of-records-a-week pipelines, RabbitMQ, AWS, and a zero-downtime platform rewrite.
>
> Saw you're hiring for [role] / working on [thing]. Would you be open to a short chat? I'm happy to walk you through the architecture.

**Tip:** if they reply with technical questions, that *is* the interview. Answer in detail.

---

## 4. DM to a Technical Recruiter

Recruiters match keywords to roles. Make their job easy with clear facts.

> Hi [Name]. I'm a senior full-stack engineer (TypeScript, React, Node, Go, AWS, LLM integration) looking for remote [senior full-stack / AI product engineer] roles.
>
> Quick highlights:
> • Built and launched Kuttl (kuttl.xyz), an AI UI-customization SDK. The live demo is on the site.
> • Built the algorithm behind 80%+ of revenue at a data SaaS (billions of records a week).
> • Owned the rebuild that helped close a $500K funding round.
>
> 6+ years of experience, remote in UTC+1 with US time-zone overlap, and I can start immediately. Resume attached. Are you working on anything that fits?

---

## 5. Follow-up (send 4–6 days later, once only)

> Hi [Name], bumping this in case it got buried. Since my last message I [shipped X on Kuttl / wrote up how the React integration works: link]. Still keen to chat about [role/Company] if the timing works.

Always include something new in a follow-up. Never send only "just checking in."

---

## Things to fill in before sending

1. **LinkedIn and GitHub links.** Add them to the resume header (there's a TODO in `resume-3.html`) and to your signature.
2. **Real traction numbers for Kuttl.** Examples: waitlist signups, partner teams, prompts processed. One honest number is worth more than any adjective. There's a TODO for this in the resume.
3. **A 60–90 second Loom or GIF** of Kuttl changing a real dashboard. Some people won't click through to a site but will watch a GIF inline.
4. **A short write-up** such as "How I made LLM edits survive React re-renders". Link it in CTO DMs. It gets you taken seriously as an engineer.
