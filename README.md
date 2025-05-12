# Thoughts on READMEs
Thinking out loud on technical documentation and audiences.  

> **When you build something impactful, don't just ensure that it flies; also make sure that it _lands_.**

I'm beginning to realize, through my Cybersecurity class, creating open-source tooling, and writing technical documentation and applying for jobs, that there is a real lack of "technical" READMEs and "prospective employer/those wanting to learn what the tool does" READMEs.

In other words, what I'm noticing is a real gap in how most open-source tools are presented.

## 🔍 The problem:

Most projects end up with one README that’s either:

- 👨‍💻 **Too technical**: assumes the reader is already deep in the weeds  
- 🙋 **Too high-level**: just a mission statement and some installation steps  
- 📉 **Or worse** — out of date, incomplete, or not tailored to anyone  

## 🧠 What I'm doing — and why it matters:

I'm attempting to naturally distinguish between two audiences:

1. **Users / Employers / Learners** — want to understand:
   - What does this tool do?
   - Why should I trust it?
   - What makes it different or useful?
   - Can I run it without breaking something?

2. **Contributors / Peers / DevOps** — want to know:
   - How do I install and run this thing?
   - What are the dependencies?
   - Can I build or modify it?
   - Where’s the code that matters?

## ✅ What this leads to:

Building a professional skill most engineers don’t learn:

> ✍️ Communicating technical work clearly to both decision-makers and implementers.

This makes an engineer _way_ more hireable — not just as a tool author, but as someone who can:
-	Write security policies
-	Draft threat models
-	Explain tooling to devs, ops, and execs alike
-	Document internal systems properly

## How do we move forward?
Do we build:
- A dual-purpose README.md format
- A docs/ folder in repositories with "Developer Notes" vs "User Guide"
- Perhaps even, always generate an index.html to make little GitHub Pages mini-doc sites

# I would probably label this as one of my strong "soft skills"

In fact, this isn't just a soft skill — it's a *technical communication superpower* that bridges the gap between:
- 🧠 Deep understanding of systems and tooling
- 🗣️ The ability to explain them to someone who didn’t build them
- 📚 Creating clarity, trust, and usability — whether it’s for a hiring manager, a teammate, or a user in the wild

## Alas, we fall into the same old routine

How do I list this (on a resume or profile)?

I could phrase it like:
- **Technical Communication & Tooling Documentation**  
Write developer- and user-facing documentation for custom security tooling, with an emphasis on clarity, audience awareness, and adoption-readiness.

Or, more casually in a README bio or project blurb:

> I care deeply about making tools not just powerful, but understandable — every script or service I write comes with clear, structured documentation to help others use, learn, and build on it.

But then we're back to where do we put it, and what audience is looking at it.

## Ultimately, this soft skill is a real differentiator in cybersecurity — where most people can build the exploit but few can explain the technique. You’re already doing both.

Going forward, I'll be thinking about templates for future projects that separates sections for:
- Users
- Contributors
- Recruiters
