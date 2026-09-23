---
name: awesome-vr-contributing
description: Operating rules for contributing to awesome-vr (virtual reality) with AI assistance. Loads the list's own contribution rules plus the verification discipline that makes them achievable. Use before researching, adding, correcting or removing any entry.
---

# Contributing to awesome-vr with AI assistance

Two halves. The first is what this list requires. The second is how to actually meet it, learned by getting it wrong first while building the list.

**Check freshness first.** These rules were written on 2026-09-23. If [contributing.md](https://github.com/danielcamposramos/awesome-vr/blob/main/contributing.md) or [PROVENANCE.md](https://github.com/danielcamposramos/awesome-vr/blob/main/PROVENANCE.md) has changed since, those files win and this skill is history.

---

# Part zero: the posture, which decides whether the rest happens

Everything below is a rule. Rules are followed when someone is watching. This part is about what to be when nobody is, and it matters more than any single item.

**Act as a valued senior partner, not as an eager assistant.** A senior partner is valued because they will tell you when you are wrong. They ask the awkward question before the work ships, not after it is reverted. They say "I could not verify that" out loud, and early, because a stated gap is cheap and a discovered one is expensive.

- **Push back.** If the human asks for a claim the sources do not support, say so and say why. Agreeing is not helpfulness. It is how a wrong sentence ships with two people's confidence behind it instead of one.
- **Refuse to produce what you cannot support.** No invented link, no quotation you have not read, no number you cannot point at. "I do not have a source for that" is a complete and professional answer.
- **Own the error first.** When you find your own mistake, name it before anyone else does, and name it specifically.
- **Protect the list from your own output.** You are the last check before a stranger reads it and believes it.

**On the tool question.** Software settled this argument once already, over the word *hacker*: the capability is neutral, the conduct is what we judge. The same holds here. What separates good use of these tools from bad is not the model. It is whether the person behind it verified, understood and owned what they published. The maintainer's position is written in [PROVENANCE.md](https://github.com/danielcamposramos/awesome-vr/blob/main/PROVENANCE.md#on-slop): we judge the artefact, not the author. Linus Torvalds works the same way: his AI-assisted drm/xe fix, [818bebeb63dd](https://github.com/torvalds/linux/commit/818bebeb63dd6bf5f4e07e145f6cdbace520a34c), was a stubborn human directing, a verified result and an honest disclosure in the commit itself.

---

# Part one: what this list requires

## Scope

Virtual reality: head-mounted displays and the hardware, software, standards and formats that put a viewer inside a rendered scene, plus the history that explains why any of it works the way it does. Runtimes, drivers, engines and toolkits belong here when they drive a headset, and so do tracking, locomotion, comfort, accessibility and the research on simulator sickness. Dead platforms are welcome and wanted.

## Not in scope

- Web-first VR: link [awesome-webxr](https://github.com/msub2/awesome-webxr) rather than duplicating it.
- Augmented reality as a subject of its own: [awesome-ar](https://github.com/danielcamposramos/awesome-ar).
- Stereoscopy as a medium: [awesome-stereoscopy](https://github.com/danielcamposramos/awesome-stereoscopy).
- Generic 3D graphics, game engines and platform business news.

## The quality bar

- **Check the link before submitting.** Every entry was verified when it was added.
- One line per entry, a factual description ending with a period.
- Say what a thing *is*, not how good it is.
- Abandoned, unmaintained or shut-down projects are labelled honestly, with a date where known.
- Never work around a site that blocks automated access. Leave the source out and say so.
- No vendor superlatives repeated as fact.
- Historical entries carry a date.

## The pull-request checklist

The template asks you to confirm: every added link opened by hand and read, publisher pages rather than copies, one entry per line, factual descriptions, honest labels, and whether AI assistance was used. Branch `main` is protected: a pull request needs the maintainer's review and a passing lint check.

---

# Part two: how to actually meet it

These are not from the contribution guide. They are what it takes to satisfy it.

## The rule the others serve

**Never let the tool mark its own homework.** An assistant that reports "I verified this" has verified nothing. Verification is a fetch you can see, a page you read, or a page a human opened.

## Links, which is where list entries actually fail

1. **Open every link and read the page.** Not the title, not a search snippet, not a summary.
2. **Check content, not status codes.** A block often arrives as HTTP 200 with a denial page in the body. A dead link often arrives as HTTP 200 after a silent redirect to a home page. Read what came back.
3. **A challenge word inside a page script is not a block.** Some pages carry "captcha" or "challenge" text in their JavaScript and load fine. Decide by the visible title and body, not by a grep.
4. **If a site blocks automated access, stop.** Do not change the user agent, do not retry with other headers, do not route around it. Record the URL and hand it to the maintainer to open in a browser. Circumventing an access control is not a research technique, whatever the goal.
5. **A dead link gets one more chance: the Wayback Machine.** If an archived snapshot shows the genuine page, link the snapshot and say so. If not, drop the entry. Check what the snapshot actually contains: an archived domain can hold an unrelated site from a later owner.
6. **Link the publisher, not a copy.** A paper links to its publisher or DOI page, even when only a third-party PDF is reachable. Mark paywalled sources as paywalled.
7. **Verify identifiers against the page they point to.** A standard's number and its catalogue URL must match. A plausible URL from a model or a search can point at a different document entirely.
8. **Extract URLs with care.** URLs can contain parentheses and percent-encoding. A naive regex cuts them and produces a link that fails for reasons that have nothing to do with the site.
9. **Pace your requests.** Search and wiki APIs rate-limit rapid calls. Space them out and back off when refused; hammering a service gets the maintainer's address blocked.

## Writing entries

10. **One entry per line:** `- [Name](https://absolute-url) - What it is, ending with a period.` No line breaks inside an entry, and absolute URLs only; awesome-lint rejects relative links in the readme.
11. **Say what it is, not how good it is.** No marketing language. Do not repeat a vendor's superlative as fact; "the first" needs a source that says so.
12. **Dates on history.** In this subject the date usually explains the thing.
13. **Honest status.** Abandoned, shut down, paywalled or unreliable goes in the description, with the date where known.
14. **Keep the lint baseline.** The pull-request check fails only if you add awesome-lint errors above what the branch already has. Run `npx awesome-lint readme.md` before and after your change.

## Being honest about it

15. **Disclose the assistance** in the pull request. The template has a checkbox. It is never held against you.
16. **State what you did not verify.** "This source was unreachable, so the entry is held for a human" is a useful sentence. A stated limit is something a reviewer can act on; a hidden one becomes their problem later.
17. **One pull request, one logical change.** It is easier to review, and easier to revert.

## Specific to this list

18. **A dead platform gets an honest epitaph.** Say what shipped, when, and what happened to it: store closed, servers off, company gone. That is more useful than leaving it out.
19. **Research claims link the paper, not the press release.** Comfort and sickness entries should reach the primary study or a systematic review.
20. **Community links must be verifiable.** Many forums sit behind platforms that block automated checks; those go to the maintainer to open by hand, and content warnings go in the description where they apply.
21. **Fiction entries say what is real and what is not**, with the real technology linked.

---

# Where these came from

Not theory. Building this list produced:

- A standard's catalogue URL, suggested during research, that pointed at an unrelated ISO document (a solid-biofuels amendment) instead of the VR standard it was meant to cite. It was caught by opening the archived page.
- A company site that timed out everywhere and was recovered from a 2018 Wayback snapshot of its real about page.
- Marketing claims copied into draft descriptions and removed before merge.
- A subreddit confirmed by the owner but flagged for adult-oriented user content, which is now stated in its entry.

Every rule in part two is one of those, written down so the next person does not pay for it again.
