# Community Forward Georgia — Public Demo

**Community needs. Future infrastructure. Lasting opportunity.**

This static, public-safe demonstration connects a Georgia ZIP, city or county to the wider set of institutions and public records that shape community readiness.

## Public experience

- **Georgia Quick View** is a public demonstration of the governed research architecture. It resolves Georgia geography and presents preloaded evidence or the research lanes a production service would use, without forcing empty cards or real-community scores. The static demo does not perform fresh live internet research.
- **Featured Americus / Sumter County Deep Community Analysis** adds audited finance, school capital, development agreement, utility, environmental, workforce, current-priority and governance evidence.
- **Pinehaven** is a fictional regression fixture and is no longer the primary public experience.

Americus is the featured deep case. Rail and transportation relationships are included as infrastructure context, with parcel-level service, rights, capacity and project use left for verification.

The Community Conditions & Active Priorities layer follows this flow:

**ZIP → jurisdictions → institutions → current public records → active community issues → financial capacity → public investment → opportunity analysis**

Records are cached by the government, school, authority, utility or institution that owns them—not duplicated by ZIP. Public evidence uses only **VERIFIED**, **REPORTED**, **INFERENCE**, and **RESEARCH NEEDED** for real communities.

## Preview locally

Serve this folder with a static HTTP server; direct `file://` loading may block JSON requests. Search `31709`, `31719`, `Americus` or `Sumter County` to open the shared featured profile.

## Key files

- `data/americus-sumter-profile.json` — featured deep analysis and current community conditions
- `data/americus-source-registry.json` — public source provenance and local-asset decisions
- `data/community-conditions-engine.json` — reusable workflow and presentation policy
- `data/generic-zip-smoke-tests.json` — five bounded retrieval-architecture checks
- `data/georgia-zip-index.json` and `data/quick-view-registry.json` — geography and entity-keyed quick-view data
- `data/pinehaven.json` — protected fictional fixture
- `assets/community-forward-georgia-social-v2.png` — LinkedIn/Open Graph share image

## Publication limits

This is research and planning support—not a site recommendation, engineering conclusion, incentive analysis, legal opinion, or statement of community consent. Firm electric, water, wastewater, fiber and environmental suitability require professional confirmation. No API keys, private client records or local machine paths belong in the public build.

Before GitHub Pages deployment, replace relative Open Graph image paths with the final absolute public URL.

## GitHub Pages deployment

This folder is a self-contained static-site repository. The included workflow deploys the repository root whenever the `main` branch is pushed.

1. Create the GitHub repository and push this folder to its `main` branch.
2. In **Settings → Pages**, choose **GitHub Actions** as the source.
3. Wait for the **Deploy Community Forward Georgia to GitHub Pages** workflow to finish.
4. Add the final absolute Pages URL to the Open Graph image metadata before sharing on LinkedIn.

After deployment, the Americus deep case is available at `/?location=31709`.
