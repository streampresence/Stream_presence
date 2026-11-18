# Stream Presence — company site

**Receipts for the agent economy.** This repo is the public home of
the Stream Presence company site.

The standalone site for Stream Presence the company (the receipts /
ledger-of-proof-of-work business). This is NOT the Think Tank's site
(the Think Tank lives at https://jbsilver96.github.io/, repo
jbsilver96/jbsilver96.github.io, source in ~/workspace/landing/).

## Files

- `index.html` — the site (single page: hero, public network, the
  Private Deployment product, for agents, for humans, contact).
  Plain HTML/CSS, no build step, no external assets.
- `agents.md` — machine-readable one-fetch company summary for
  agents, mirroring the receipts agents.md pattern.
- `SKILL.md` — agent skill file for working with Stream Presence.
- `llms.txt` — llms.txt index for the site.

## Publishing

Johnny created this repo himself: **jbsilver96/Stream_presence**
(public). Site files were pushed to `main` on 2026-11-18. An earlier
copy also lives in the private repo jbsilver96/Stream-Presence-POW,
which stays private; this public repo is the site's public home.

Expected URL once Pages is on:
https://jbsilver96.github.io/Stream_presence/
(Pages: Settings → Pages → Deploy from branch: main, folder / root.
Pages still needs Johnny to flip it on — no connector operation
exists for it.)

## Notes

- Branding (2026-11-18): the header logo and favicon are embedded in
  `index.html` as base64 data URIs because the GitHub connector's
  push-files is string-only and cannot push binary files. The staged
  binary assets (`assets/logo.png`, `favicon.ico`,
  `apple-touch-icon.png`, `icon-navy.png`) stay on disk locally; the
  apple-touch-icon link and the og:image meta are omitted from
  `index.html` until a binary-capable push can land those files as
  real files in the repo.
- Copy ruled by Johnny 2026-11-18: tagline "Receipts for the agent
  economy" (hero headline + agents.md descriptor); hero blurb and
  the Private Deployment intro blurb (Johnny's own opening) set
  verbatim in index.html.
- Brand line: "Run entirely by AI, under the direction of its
  founder." Never "run by Muse."
- Honesty rules baked into the copy: the public network is live
  (since 2026-11-17) and linked, never hardcoded with counters
  that would rot — stats link out to stats.json. Private
  Deployment is "by arrangement," entered via a scoped audit pack;
  no customers, certifications, or finished enterprise features are
  claimed. Countersignatures are phrased at protocol-design level
  (v0.3).
- The receipts agents.md service #7 "human-readable brief" link
  should point at this site's #product section once this site is
  live (it previously pointed at the Think Tank landing page, which
  was the wrong property).
