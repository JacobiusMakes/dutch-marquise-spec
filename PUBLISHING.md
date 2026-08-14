# Publishing this specification

This repository is complete and ready to publish. Publishing turns it into the
permanent, citable anchor the rest of the strategy points at. There are three
one-time steps that need your credentials (I cannot do these for you without
your accounts), and then a set of follow-ups I can run.

## What this becomes once published

- A public GitHub repo that search engines, developers, and LLM training
  crawlers can read.
- A permanent **DOI** (from Zenodo) that researchers, AI answer engines, and a
  future Wikipedia editor can cite. The concept DOI always resolves to the
  latest version.
- A CC BY licensed standard, so every reuse must credit Stienhardt by name.

## Step 1: Create the GitHub repo (needs your GitHub login)

1. Create a public repo named `dutch-marquise-spec` under the Stienhardt org or
   your account.
2. Push this folder to it:

   ```
   cd dutch-marquise-spec
   git init
   git add .
   git commit -m "Dutch Marquise: Open Geometry Specification v1.0.0"
   git branch -M main
   git remote add origin https://github.com/stienhardt/dutch-marquise-spec.git
   git push -u origin main
   ```

   (If you use a different org or account name, update the URLs in
   `README.md`, `CITATION.cff`, `.zenodo.json`, and `jsonld/dutch-marquise.jsonld`
   to match. Search for `stienhardt/dutch-marquise-spec`.)

3. Optional but recommended: in the repo, click "Add a license," pick
   "Creative Commons Attribution 4.0 International," and let GitHub insert the
   full legal text in place of the summary `LICENSE` file.

## Step 2: Connect Zenodo and mint the DOI (needs your Zenodo + GitHub login)

1. Sign in to https://zenodo.org with your GitHub account.
2. Go to your Zenodo account, open the GitHub tab, and flip the switch ON for
   `dutch-marquise-spec`.
3. Back on GitHub, create a release: tag `v1.0.0`, title
   "Dutch Marquise: Open Geometry Specification v1.0.0."
4. Zenodo automatically archives the release and mints a DOI. Copy it.

## Step 3: Wire the real DOI back in (I can do this once you paste the DOI)

The DOI appears as `10.5281/zenodo.XXXXXXX` placeholders in:

- `README.md` (How to cite)
- `jsonld/dutch-marquise.jsonld` (`identifier`)

Paste me the minted DOI and I will replace every placeholder and prepare the
v1.0.1 metadata commit.

## Follow-ups I can run once it is live

- Draft the schema.org JSON-LD handoff for the on-site team to embed on
  `/pages/dutch-marquise-diamond`, using `jsonld/dutch-marquise.jsonld`.
- Prepare the Google Dataset Search submission (the `Dataset` JSON-LD is already
  built for this; it needs to be live on a crawlable URL).
- Draft the Wikidata statements that cite this DOI as a reference (a separate
  build; the DOI is the anchor, not itself a Wikipedia-grade citation).

## What stays human

Per the engine's hard rule, nothing about publishing the brand externally
happens without your go-ahead. These three steps are yours to run because they
use your accounts. Everything downstream I can prepare and queue for your
approval.
