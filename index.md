# Why You Won't Find Much Here: A Self-Hoster's Apology

*If you're reading this, you're probably a hiring manager, a recruiter, or an engineer doing due diligence on a candidate. Welcome. Let me explain why this profile looks the way it does.*

## The short version

I run my own git server. Nearly everything I build lives on a Gitea instance in my basement, on hardware I own, behind a firewall I configured, backed up on a schedule I wrote. This GitHub account exists because the industry — reasonably — wants to see public evidence of work, and I'd rather meet that expectation honestly than pretend I don't write code.

So yes: what you see here was put here, at least in part, so that people like you could see it. I'd rather say that plainly than let a sparse contribution graph imply I don't ship.

## The longer version

I've spent most of my career in environments where the network *is* the security boundary — classified systems, air-gapped enclaves, infrastructure where "just put it in the cloud" is either forbidden or a firing offense. Sixteen years in the Army followed by defense-sector infrastructure work will do something to your instincts about where data should live. The habit that formed isn't paranoia; it's a default posture: **understand where your bits are, who can touch them, and what happens when the vendor between you and your data changes the terms.**

When I apply that posture to my personal work, self-hosting wins on almost every axis I care about:

**Ownership is unambiguous.** My repos sit on my disks. No terms-of-service update can change what happens to them. No acquisition, no pricing pivot, no policy shift about training AI models on hosted code. Whatever your opinion on that last one, on my server the question simply never arises — nobody's crawler reaches my basement.

**The failure modes are mine.** When GitHub goes down, half the industry stops. When my Gitea instance goes down, I walk downstairs. I've made that trade knowingly: I accept full responsibility for backups, updates, and uptime in exchange for never being one deprecation notice away from a migration project I didn't schedule.

**It keeps me honest as an engineer.** Running your own git server is a small, constant infrastructure practice: reverse proxy config, TLS certs, backup verification, update hygiene, monitoring. It's the same discipline I apply professionally — Ansible-managed, Prometheus-watched, segmented from the rest of my network — at a scale where I personally absorb every consequence of every shortcut. There is no better teacher.

**Most of my work shouldn't be public anyway.** My repos are full of my network's actual topology: hostnames, IP schemes, service configs, automation that names real machines. Publishing that isn't transparency, it's an attack-surface donation. Sanitizing a project for public release is real work — which is exactly what I did for the repositories you *do* see here.

## What this isn't

This isn't a boycott, and it isn't contempt for people who host everything publicly. GitHub is a genuinely good product. The network effects are real, open source runs on it, and collaboration at global scale needs a commons — a basement server can't be that, and shouldn't try. If I'm contributing to *your* project, I'll happily meet it where it lives.

It also isn't a claim of moral high ground. Self-hosting is a preference shaped by my history and threat model, not a virtue. Plenty of engineers I respect push everything public and are better for it.

## What I'd ask of a reviewer

Judge what's here on its merits — it's real work, genuinely mine, sanitized rather than fabricated. But read the empty space correctly: it isn't absence of output, it's presence of a boundary. Behind it are years of infrastructure automation, a homelab that functions as a small production environment, and a self-hosted LLM stack that I break and rebuild for fun.

If anything, I'd offer this profile itself as a small data point about how I work: I understood the requirement, met it honestly, and told you exactly what trade-offs were behind it.

That's how I run infrastructure, too.
