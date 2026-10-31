---
marp: true
theme: default
paginate: true
size: 16:9
title: Welcome to the Octagon Religious Research Group (ORG)
description: A first walk through ORG's proposals, procedures, decks and reading room, for a newcomer and their AI helper.
style: |
  /* Tone: the four shades of the organisation's family, from my-template/proposals-template/TONES.md (bare hex, no #).
     The ground is the DEEP shade mixed into near-black, headings are the TINT with a PRIMARY rule, so every family
     reads on the dark ground, purple included. Do not hand-edit colours below; change the four placeholders. */
  section { background: color-mix(in srgb, #064e3b 32%, #0b0d12); color: #eef0f3; font-family: "Helvetica Neue", Helvetica, Arial, sans-serif; font-size: 25px; padding: 52px 64px 56px; border-left: 10px solid #059669; }
  section::after { color: color-mix(in srgb, #d1fae5 60%, #6b7280); font-size: 0.6em; }
  section h1 { color: #d1fae5 !important; border-bottom: 3px solid #059669; padding-bottom: 8px; font-size: 1.45em; margin-bottom: 0.45em; }
  section h2 { color: color-mix(in srgb, #059669 45%, white) !important; font-size: 1.1em; margin: 0.2em 0 0.4em; }
  strong { color: #d1fae5; }
  a { color: color-mix(in srgb, #059669 40%, white); text-decoration: underline; text-decoration-color: #047857; }
  code { background: color-mix(in srgb, #064e3b 70%, #1f2937); color: #d1fae5; padding: 1px 6px; border-radius: 4px; font-size: 0.82em; }
  pre { background: color-mix(in srgb, #064e3b 45%, #111318); color: #d1fae5; border: 1px solid #047857; border-radius: 8px; padding: 12px 16px; font-size: 0.68em; line-height: 1.35; }
  pre code { background: transparent; color: inherit; padding: 0; font-size: 1em; }
  table { border-collapse: collapse; width: 100%; font-size: 0.74em; }
  section table th { background: #064e3b; color: #d1fae5; padding: 6px 10px; text-align: left; border: 1px solid #047857; }
  section table td { background: color-mix(in srgb, #064e3b 22%, #14161c); color: #eef0f3; padding: 5px 10px; border: 1px solid color-mix(in srgb, #047857 45%, #14161c); }
  blockquote { border-left: 4px solid #059669; background: color-mix(in srgb, #064e3b 40%, #111318); color: #eef0f3; padding: 8px 16px; margin: 0.6em 0; font-style: normal; }
  li { margin: 0.18em 0; }
  .small { font-size: 0.66em; color: color-mix(in srgb, #d1fae5 55%, #6b7280); }
  .fill { color: #0b0d12; background: #d1fae5; padding: 0 6px; border-radius: 3px; }
  .shades { display: flex; height: 14px; margin: 18px 0 0; border-radius: 3px; overflow: hidden; }
  .shades span { flex: 1; }
  .s1 { background: #064e3b } .s2 { background: #047857 } .s3 { background: #059669 } .s4 { background: #d1fae5 }
  section.lead { border-left: none; background: linear-gradient(135deg, #064e3b 0%, color-mix(in srgb, #064e3b 30%, #0b0d12) 75%); justify-content: center; }
  section.lead h1 { border: none; font-size: 2.3em; color: #ffffff !important; margin-bottom: 0.1em; }
  section.lead h2 { color: #d1fae5 !important; font-weight: 400; font-size: 1.15em; }
  section.lead .kicker { color: #d1fae5; letter-spacing: 0.25em; font-size: 0.6em; font-weight: 700; opacity: .85; }
---

<!--
  ORG's newcomer deck, filled from my-template/decks-template/welcome.marp.md (O-R-G emerald:
  059669 064e3b 047857 d1fae5) and then rewritten where ORG differs: its proposals are members-only,
  its repositories take pull requests into main (no preview branch yet), and its reading room has a
  public shelf and a members' room. Render: decks-template/README.md, "Render it".
-->

<!-- _class: lead -->
<!-- _paginate: false -->

<span class="kicker">WELCOME</span>

# Welcome to ORG

## The Octagon Religious Research Group: where the proposals, the procedures and the decks live, how a change travels, and how to answer

<span class="small">A first walk for a newcomer, and for the AI helper beside them. Every slide points at a real page; the deck only shows the order to open them in.</span>

<div class="shades"><span class="s1"></span><span class="s2"></span><span class="s3"></span><span class="s4"></span></div>

---

# What you will find here

| Kind | What it is | Where |
|---|---|---|
| **The reading room** | one shelf for everything ORG has chosen to share, in a browser | [the public shelf](https://octagon-religious-research-group-org.github.io/reading-room-public/) · [the members' room](https://github.com/Octagon-Religious-Research-Group-ORG/reading-room) |
| **Procedures** (SOPs) | *this is how we do it now*, approved versions tagged | [ORG procedures, public](https://github.com/Octagon-Religious-Research-Group-ORG/ops-standard-operating-procedures-public) |
| **Proposals** | *should we?* One folder, one page, a PDF beside it | [`proposals`](https://github.com/Octagon-Religious-Research-Group-ORG/proposals) (members) |
| **Decks** | walk-throughs like this one, for a call or a first look | [`.github/decks/`](https://github.com/Octagon-Religious-Research-Group-ORG/.github/tree/main/decks) |

> Everything ORG writes wears the same colour, these four shades of emerald, so you can tell whose page it is before you read a word.

<span class="small">The public shelf and the public procedures opened in October 2026 with empty shelves; officers add pages one at a time. A link marked (members) asks you to sign in.</span>

<div class="shades"><span class="s1"></span><span class="s2"></span><span class="s3"></span><span class="s4"></span></div>

---

# Five words, and you can find your way

| Word | Means |
|---|---|
| **Repository** | a folder that remembers every change and who made it |
| **Pull request** | a proposed change, waiting for a person to read it and merge it |
| **`preview` and `main`** | the rehearsal copy and the live copy of the same folder, where a repository has both |
| **Public twin** | a public copy that carries only the pages marked public; nobody edits it by hand |
| **Issue** | a conversation thread: the easiest way to ask or answer |

<span class="small">You never need to type a branch command. You read, you comment, and you say yes or no.</span>

---

# How a proposal reads

1. **TL;DR**: five lines, the only part you have to read.
2. **What is offered**: how things are today, beside what is proposed.
3. **Decisions log**: what was chosen, when, and by whom. Yours stay blank until you choose.
4. **Asks**: usually none, sometimes one.
5. **Sources, and what could not be confirmed**: folded away, never hidden.

Every proposal comes as a **PDF for your eyes** and the **markdown it was made from** for your helper's. Members start with **000 Start here** and **001 ORG's Welcome Map** in [`proposals`](https://github.com/Octagon-Religious-Research-Group-ORG/proposals); the vote itself happens in **ORG (Voting)** on Telegram.

---

# Procedures: how we do it now

- A procedure is named `SOP-<Department>-<ID>-<name>`: `SOP-OPS-001` is the first operations procedure.
- It is a **draft** until the officers tag an approved version; the tag is the approval.
- Each one opens with a badge row: the number in **ORG's emerald**, its status, the date it last changed, and **For** in the slate every organisation shares.
- Every procedure is also a PDF, rendered on each push.

> Read **SOP-OPS-001 "How a change travels"** first. It is the road two slides on, in full.

<span class="small">The procedures visitors may read: [ops-standard-operating-procedures-public](https://github.com/Octagon-Religious-Research-Group-ORG/ops-standard-operating-procedures-public). Members read all of them, drafts included, in the members' room.</span>

---

# The reading room, and your helper

- **The public shelf**, [octagon-religious-research-group-org.github.io/reading-room-public](https://octagon-religious-research-group-org.github.io/reading-room-public/): the decks and procedures ORG has chosen to share. Anyone can open it.
- **The members' room**, [`reading-room`](https://github.com/Octagon-Religious-Research-Group-ORG/reading-room): proposals, procedures and decks as PDFs. Open it signed in to GitHub. A **404** means signed out or not yet in the **readers** team: ask ORG at org@orgspirituality.org.
- **Your helper** (Claude, ChatGPT, any of them) can read the same pages once it is connected with your permission, never more than you can. Point it at the markdown, not the PDF, and start it with [the welcome for your helper](https://github.com/Octagon-Religious-Research-Group-ORG/.github-private/blob/main/WELCOME-FOR-YOUR-HELPER.md) (members).

> A good first question for your helper: *"Read 000 Start here and tell me what is waiting for my answer."*

---

# The road a change travels

```
  an edit  ──→  a pull request      (read it here, comment here)
                   │
                   │  a person with the role merges it, as a merge commit
                   ▼
                  main               (the live copy)
                   │
                   │  automatic sync: only pages marked public
                   ▼
            the public twin  (what visitors see)
```

- ORG's repositories take pull requests straight into `main` today. Where a repository keeps a `preview` branch, the edit rehearses there first and the pull request is called **Promote: …** (what it carries).
- If a link to `main` still shows old words while someone says the change is done, the pull request (or the Promote) has not been merged yet.
- A page that is not marked public never leaves the private repository, on any branch.

---

# How to answer

| You want to… | Do this |
|---|---|
| say yes, no, or "not yet" to a proposal | vote in **ORG (Voting)** on Telegram, or open an **issue** titled with its number |
| comment on a change before it goes live | comment on its **pull request** |
| ask a question about a procedure | open an issue in the procedures repository, naming the SOP |
| ask your helper to answer for you | let it draft; **you** read it and post it under your name |
| get access, or more of it | write to ORG at org@orgspirituality.org, saying which GitHub account is yours |

> There is no wrong door. A question in the wrong place gets moved, not lost.

---

# Who to ask

**ORG, at org@orgspirituality.org, or in [ORG (Public)](https://t.me/ORG_Spirituality) on Telegram**

- for access to the reading room, the proposals or the procedures
- when a link shows 404, or a page looks out of date
- when you are not sure where an answer belongs

Every way to reach ORG is on its [contacts page](https://github.com/Octagon-Religious-Research-Group-ORG/.github/blob/main/CONTACTS.md). For GitHub itself, the technical steward is **Christopher W** ([@drasticstatic](https://github.com/drasticstatic)). Nobody at ORG ever needs your password or a code.

<span class="small">Where to start next: the [public shelf](https://octagon-religious-research-group-org.github.io/reading-room-public/), then **SOP-OPS-001** in the [public procedures](https://github.com/Octagon-Religious-Research-Group-ORG/ops-standard-operating-procedures-public), then, as a member, **000 Start here** in [`proposals`](https://github.com/Octagon-Religious-Research-Group-ORG/proposals).</span>

<div class="shades"><span class="s1"></span><span class="s2"></span><span class="s3"></span><span class="s4"></span></div>
