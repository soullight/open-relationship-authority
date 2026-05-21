# Open Relationship Authority

The second vertical site in the franchise. Cloned from `tantra-authority/` template 2026-05-15.

**Live target:** `theopenrelationshipblueprint.com` (owned, Cloudflare DNS — needs to be wired)
**Deploy via:** Cloudflare Pages (see `DEPLOY.md`)
**Maps to book:** *Beyond the Myth: A Field Guide to Open Relationships* (book 3 in the stack)

---

## What this site is

Open Relationship Authority is the **practical, SEO-friendly, editorial** front door to the open-relationship / ethical-non-monogamy / polyamory body of work in the Beyond the Myth series. It is NOT the personal Substack. It is the authoritative, non-tribal destination for people who type "should I open my relationship," "how does polyamory work," "is monogamy natural," or "my partner wants an open relationship" into Google.

**Persona:** The Open Relationship Authority Editors. Bylineless in most cases. Calm, authoritative, non-tribal, body-grounded, anti-bullshit on BOTH sides — pro-monogamy mythology AND poly-community mythology both get the same editorial scrutiny.

**Voice rules — same as Tantra Authority** (see `code/verticals/tantra-authority/README.md` for the canonical brand brief — anti-fake-guru, pro-money, mandatory "Invite the animal in" closing structure). Topic-specific delta below.

## Topic-specific voice notes

**The unique editorial position of this site:** The framework is non-tribal. The polyamory community is its own tribe with its own dogma, its own enforcement mechanisms, its own "wrong way to do it" call-outs. The monogamy default is also a tribe with its own dogma, etc. The framework refuses both. Both sides lie. The framework sees both lies.

**Things this site does NOT do:**
- Cheerleads polyamory as "more evolved" or "more enlightened"
- Cheerleads monogamy as "natural" or "morally superior"
- Treats relationship structures as identities
- Sells the "polyamory community" as the answer
- Uses kitchen-table-poly insider vocabulary as authority
- Apologizes for being open OR for being monogamous

**Things this site DOES do:**
- Names what's actually happening in each structure
- Tells the truth about the failure modes both sides hide
- Gives readers tools to figure out what they actually want, not what their tribe wants them to want
- Acknowledges that some readers will conclude monogamy is right for them after reading; others will conclude opening is right; both conclusions are valid
- Distinguishes between "open because you genuinely want to" and "open because you're avoiding the real conversation"
- Distinguishes between "monogamous because you genuinely want to" and "monogamous because you're avoiding the real conversation"

## Funnel architecture

```
Google search → Open Relationship Authority article →
  email signup (Substack form) →
  drip into The Naked Mind →
  preorder Beyond the Myth: A Field Guide to Open Relationships
```

Plus practitioner directory + shop modules (cloned from Tantra Authority, topic-relevant adjustments).

## Practitioner directory — open-relationship-specific

The directory lists, with the same transparency requirements as Tantra Authority's:

- Polyamory-competent therapists
- Relationship coaches working with ENM
- ENM-friendly attorneys (relevant for legal structures, custody concerns, asset planning)
- Communication-focused couples coaches
- Shadow-work specialists who work with relationship trauma
- Sex-positive medical providers

Same vetting rules. Same code of conduct. Same anti-cult bright lines.

## Content strategy — first 30 articles

Mix of:
- Foundations articles (what open actually means, the structures, brief history of ENM)
- Practice articles (specific communication techniques, jealousy work, hierarchy negotiation)
- Reframe articles (what poly is NOT, what monogamy is NOT — both directions)
- Couples articles (the open-the-relationship conversation, mid-opening crisis, etc.)
- Anti-cult articles (the dark side of "poly community" enforcement, the high-control polyamory groups)

## STALE CONTENT WARNING — pre-deploy cleanup needed

This folder was cloned from `tantra-authority/` to preserve the template. The `articles/` directory currently contains tantra articles that must be removed or replaced before this site goes live. Same for `queue_authority/BACKLOG.md`. The README, index.html, and template structure are the parts to keep.

**Cleanup before deploy:**
- [ ] Remove tantra-specific articles from `articles/` (or replace with open-relationship equivalents)
- [ ] Replace `queue_authority/BACKLOG.md` with open-relationship article briefs
- [ ] Customize `book.html` to point at the Open Relationships book
- [ ] Customize `about.html`
- [ ] Customize `directory.html` for polyamory-competent practitioners
- [ ] Customize `shop.html` for open-relationship-relevant products

## Seeded articles (after cleanup) — to brief next

Top-priority article seeds:

- `articles/what-open-relationships-actually-are.html` — the foundational map
- `articles/should-we-open-our-relationship.html` — the "we're considering it" piece
- `articles/the-monogamy-mythology.html` — the corrective for the readers who arrived via "is monogamy natural"
- `articles/the-polyamory-mythology.html` — the corrective for readers who arrived from poly-community burnout
- `articles/jealousy-is-data-not-pathology.html` — the framework's reframe of the central emotion

## Open / pending

- [ ] Clean up stale tantra articles in `articles/`
- [ ] Write the 5 seed articles above
- [ ] Customize all top-level HTML pages (book.html, about.html, directory.html, shop.html)
- [ ] Connect newsletter forms to Substack (same as tantra-authority — point at `https://thenakedmind.substack.com/api/v1/free?nojs=true`)
- [ ] Deploy to Cloudflare Pages
- [ ] Set up custom domain `theopenrelationshipblueprint.com`
- [ ] Add Cloudflare Web Analytics

## Notes on the franchise template

This is the second vertical. The franchise model: each new vertical takes ~30 min to spin up the scaffold + a few weeks of content runway buildout. By year-end 2026, the goal is 7 verticals matching the 7-book stack:

1. ✅ Tantra Authority (live in progress)
2. 🟡 Open Relationship Authority (this folder — scaffolded 2026-05-15, content TBD)
3. ⏳ Energy Sex Authority (forthcoming)
4. ⏳ Modern Enlightenment Authority (forthcoming)
5. ⏳ Female Sexuality Authority (forthcoming)
6. ⏳ Male Sexuality Authority (forthcoming)
7. ⏳ Sexual Shadow Authority — capstone (forthcoming)
