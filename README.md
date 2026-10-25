# Swiss AI Trust Tag (SATT)

Independent certification and benchmarking for trustworthy AI. Based in Zürich, Switzerland.

**Trust is computed, not claimed.**

Swiss AI Trust Tag provides a sovereign audit and verification framework for frontier AI. The reference architecture is entirely client-side: there is no SATT cloud in the verification path. The work is written for research institutions, security teams, and enterprise architects who need a method they can inspect.

The product site is launching. [swissaitrusttag.ch](https://swissaitrusttag.ch) is prepared and is not hosted yet. This repository is the public brand presence until that site is live. [swisstrusttag.ch](https://swisstrusttag.ch) is a companion domain.

## What SATT is

SATT is an independent organisation in Zürich. It provides certification and benchmarking for trustworthy AI. A published result follows from a stated method. Clarity takes precedence over marketing language.

Benchmark governance stays separate from the systems under test.

## Pillars

### Client-side execution

Verification runs on the client. The reference architecture is 100% client-side and zero-cloud. Inputs, scoring, and evidence stay with the party running the check. Nothing in the trust path depends on a SATT-hosted runtime.

### Sovereign verification

SATT is a sovereign audit and verification framework for frontier AI. An institution can examine how a result was produced, retain the evidence, and repeat the check without placing models or data in a third-party cloud.

### Neutral benchmark governance

Benchmarks are governed independently of the systems they measure. Methods are stated in advance of the score. Trust is computed, not claimed.

## Links

- Website (launching): [swissaitrusttag.ch](https://swissaitrusttag.ch)
- Companion domain: [swisstrusttag.ch](https://swisstrusttag.ch)
- X: [@SwissAiTrustTag](https://x.com/SwissAiTrustTag)
- Email: [ceo@swissaitrusttag.ch](mailto:ceo@swissaitrusttag.ch)

## This repository

[`index.html`](index.html) at the repository root is a static site for GitHub Pages. Styling is in [`assets/style.css`](assets/style.css). [`.nojekyll`](.nojekyll) keeps Pages from building the site with Jekyll.

Publish from the `main` branch, folder **`/ (root)`**:

1. Open **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Set **Branch** to `main` and **Folder** to `/ (root)`.
4. Save.

The project site is then served at `https://swissaitrusttag.github.io/website/`. No custom domain is configured here: `swissaitrusttag.ch` is reserved for the product site.

## License

Source code for this site — HTML, CSS, and related static assets — is released under the [MIT License](LICENSE).

The MIT License does not grant rights to the Swiss AI Trust Tag name, wordmark, or other brand identifiers.
