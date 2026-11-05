# Promit K. Chaudhuri — academic website

Minimal static website, designed around Georgia, white space, and restrained burgundy links. No build system, dependencies, tracking, or JavaScript is required. Includes your existing photographs and the paper/document links from the live Google Site reviewed on 4 November 2026.

## Preview

Open `index.html` locally. For navigation through directory URLs, run `python3 -m http.server 8000` in this folder and open `http://localhost:8000`.

## Publish on GitHub Pages

1. Sign in to **Promit45** and create a public repository named **promit45.github.io**.
2. Upload the contents of this folder to the repository root. `index.html` must be at the top level. Include `assets/`, `research/`, `teaching/`, `home/`, `404.html`, and `.nojekyll`.
3. In **Settings → Pages**, choose **Deploy from a branch**, branch **main**, folder **/ (root)**, and save.
4. Once GitHub finishes deployment, open the Pages URL shown in Settings. It should be `https://promit45.github.io/`.
5. Check Home, Research, Teaching, CV, the abstract control, and document links.

Repository: https://github.com/Promit45/promit45.github.io

The website is prepared for publication on GitHub Pages. See the conversation for the verified deployment status.

## Move promitkchaudhuri.com when ready

The existing Google Site can remain online during the GitHub preview. No domain change is needed to preview this design.

1. In GitHub account Settings → Pages, verify ownership of `promitkchaudhuri.com` using GitHub's TXT record instructions.
2. In the website repository's Settings → Pages, set the custom domain to **www.promitkchaudhuri.com**. GitHub creates `CNAME` when publishing from a branch.
3. At the domain's DNS provider, change the **www** CNAME to **promit45.github.io**. Point the apex (`@`) A records to the four GitHub Pages addresses below if you want the bare domain to redirect correctly.

| Type | Name | Value |
|---|---|---|
| CNAME | www | promit45.github.io |
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |

Replace the old website-specific records where necessary. Keep unrelated email and verification records intact. GitHub's documentation says DNS propagation and HTTPS availability may take up to 24 hours. Enable **Enforce HTTPS** once available. The `home/` redirect preserves the old `/home` route. The `/research` and `/teaching` paths remain supported by their corresponding directories.

Official instructions checked during preparation:
- https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
- https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

## Editing

| File | Contents |
|---|---|
| `index.html` | Introduction, market year, portrait, and document links |
| `research/index.html` | Papers, coauthors, statuses, and JMP abstract |
| `teaching/index.html` | Teaching experience, course resources, and Marginal Falls |
| `assets/style.css` | Typography, colors, spacing, and responsive layout |
| `assets/portrait.jpg` | Existing homepage portrait |
| `assets/teaching.jpg` | Existing classroom photograph |

The navigation and footer are repeated in the three HTML files so they work without JavaScript. When changing a shared link, update it in all three. Georgia uses the visitor's installed font, falling back to Times New Roman or the system serif when unavailable. Document links continue to use your existing Google Drive and SSRN destinations. When you replace a PDF in Drive, preserving its file ID keeps the site link working.

The homepage prose has been shortened. Research titles, coauthors, statuses, the full JMP abstract, and teaching resources were transcribed from the live site. In particular, this package uses the live site's updated AER status, paper title, Learning Networks status, and Peru project's IRB-stage description. Review these whenever your paper statuses change.

## Checks performed

- All local page, stylesheet, and image targets exist.
- Desktop browser review of Home, Research, and Teaching.
- Mobile-width browser review of all three pages, with no horizontal content overflow.
- Research abstract opens correctly.
- Navigation, accessible labels, keyboard focus styles, and old `/home` route included.
- External destinations are preserved from the existing site, rather than replaced with placeholder links. Access permissions at those external services remain their responsibility.

See `DESIGN_REVIEW.md` for the 20 candidate websites reviewed and the design choices drawn from them.
