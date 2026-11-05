# Design references and decisions

Reviewed 20 distinct current or recent economics job market candidate websites. Seven received additional rendered screenshot inspection (Jonghyun Park, Xuandong Chen, Yiying Tan, Max Alston, Will Sandholtz, Ian Pitman, Santiago Lacouture). The other observations are based on retrieved page structure and content, not claims about rendered fonts or spacing.

## Design chosen

- Georgia throughout, with a compact name and navigation header.
- A white background, charcoal text, and muted burgundy links.
- A constrained reading width, portrait alongside the introduction, and short home text.
- Separate Research and Teaching pages because both contain substantial material.
- Research categories as small side labels on desktop and section headings on mobile.
- An expandable JMP abstract using native HTML, without JavaScript.
- Existing photographs and links retained. No decorative animations or extra UI.

# Candidate website review A — 4 November 2026

Ten personal websites opened and read through the web retrieval tool. Candidate status cross-checked against Stanford, MIT, and Princeton current placement rosters. Observations below concern verified content organization and navigation, not unverified font/color/rendering claims.

| Candidate | Institution / market | Website | Concrete observation |
|---|---|---|---|
| Luiz Carpizo | Stanford, 2026–27 | https://sites.google.com/view/luiz-carpizo/home | One long page starts with affiliation, fields, market status, CV/contact and references, then clearly separates Job Market Paper, Working Papers, and Publications. Long abstracts make it fairly dense. |
| João Francisco Pugliese | Stanford, 2026–27 | https://joaofpugliese.github.io/ | Profile/photo leads directly into CV and working papers. Paper entries have dates, coauthors, Abstract/PDF links, with explicit JMP marking. |
| Xuandong Chen | Princeton, 2026–27 | https://xuandong-chen.github.io/ | Three-item Home/Research/CV navigation, short bio, contact block, portrait, and JMP exposed immediately. Clear separate research hierarchy. |
| Yiying Tan | Princeton, 2026–27 | https://yytan1.github.io/ | Research/CV links, concise identity and market statement, then JMP and working papers. Each paper has a show-abstract affordance rather than requiring the long abstract to dominate the initial scan. |
| Max Alston | Princeton, 2026–27 | https://maxalston.github.io/ | Extremely short introduction with inline CV/contact, followed by research grouped into JMP, Working Papers, Publications, and Policy Writing. Repeated Abstract button and Paper link provide consistent actions. |
| Stephanie Hu | Princeton, 2026–27 | https://www.stephanie-hu.com/ | Very short home page: photo, affiliation, fields, market availability, CV and email. This provides a useful lower bound on how little a homepage needs. |
| Amy Kim | Princeton, 2026–27 | https://www.amykimecon.com/ | Home page makes research question intelligible in one paragraph, then gives market status and CV/email. The focus is a readable introduction rather than a long project inventory. |
| Hassan Sayed | Princeton PhD 2025, 2026–27 market | https://www.hassan-sayed.com/ | Leads with intellectual identity and market status, then substantive research themes, current postdoc affiliation, CV and contact. More prose-heavy than the minimal examples. |
| Kate Reinmuth | Stanford, 2026–27 | https://www.kate-reinmuth.com/ | Navigation goes to Working Papers, Publications and CV. The JMP has a separate general-audience three-minute summary alongside PDF/abstract. Publications retain policy-impact and media links as subordinate information. |
| Sivakorn Sanguanmoo | MIT, 2026–27 | https://sites.google.com/view/sivakorn-sanguanmoo/home | Strong theory example: short bio/CV/contact, JMP first, and one-sentence question or explanation under other paper titles. Keeps technical abstracts out of most paper listings. |

## Useful patterns for Promit

- Use a small navigation bar and make CV and email available without hunting.
- Keep home focused on identity, a comprehensible research agenda, current job-market availability, portrait, and featured JMP.
- Separate the full research list from the home biography because Promit has several research projects and substantial teaching content.
- Use native expandable abstracts so research pages remain easy to scan while full detail is accessible.
- Keep paper title, coauthors, status, PDF and abstract controls in a consistent order.
- Make Marginal Falls a clear teaching contribution on Teaching, with a restrained home link, not a separate visual brand competing with the research identity.
- Georgia can carry the entire typographic hierarchy with modest size/weight changes. The actual font is Promit's stated preference, not inferred from these sites.


# Candidate website review — group B

Reviewed 4 November 2026. All ten personal websites below were opened successfully with the web retrieval tool. Observations concern retrieved content, navigation, and information hierarchy. Fonts, pixel spacing, colors, and responsive rendering have not been visually verified.

| Candidate | Affiliation / cohort evidence | Website | Concrete structure observation | Design lesson for Promit |
|---|---|---|---|---|
| Jonghyun Park | Virginia Tech PhD candidate, current JMP on homepage | https://jonghyun-econ.github.io/ | Portrait, compact research introduction, one paragraph describing JMP, then direct CV and research-statement downloads and email. | A homepage can be extremely spare while delivering all essential recruiting links. |
| Jennifer Zou | Harvard, explicitly 2025–26 market | https://jen-zou.github.io/ | Navigation is just name, JMP, CV. Intro includes field, JMP explanation, market statement, and contact. | Put JMP and CV within immediate reach. |
| Will Sandholtz | Berkeley, explicitly 2025–26 market | https://willsandholtz.github.io/ | Research and Teaching navigation. Very short intro with CV link followed immediately by a dedicated JMP heading, title, and PDF. | Strong model for a short homepage whose fuller content lives on separate pages. |
| Justin Katz | Harvard 2025–26 candidate profile, now Boston College assistant professor | https://jdikatz.github.io/ | Brief biography, then Working Papers with titles, coauthors, draft links, abstracts, and research status. | Consistent paper entries matter more than decorative containers. |
| Victoria Angelova | Harvard recent 2025–26 candidate, now lists August 2026 placement | https://sites.google.com/view/victoriaangelova | Compact intro and CV/email, then JMP, Publications, Working Papers, Other Publications. | Clearly label research categories and publication status. |
| Dylan Balla-Elliott | Chicago, explicitly 2026–27 market | https://www.dballaelliott.com/ | JMP, Papers, Code navigation. CV and references near profile. Research includes small PDF/highlights/package links. | Put supporting links on one unobtrusive line below each title. |
| Deniz Dutz | Chicago, explicitly 2026–27 market | https://www.denizdutz.com/ | Brief welcome, fields, market statement, JMP link, then Research/Teaching/CV and email on homepage. | Avoid forcing visitors to read a long biography to locate documents. |
| Santiago Lacouture | Chicago, explicitly 2026–27 market | https://www.santiagolacouture.com/ | Research, Teaching, and CV navigation, a dedicated JMP feature, research category filters, abstracts, and teaching tables. | Category labels and course tables help scanning, but interactive category filters would be optional complexity for Promit's minimal brief. |
| Isaac Norwich | Chicago, explicitly 2026–27 market | https://isaacnorwich.com/ | About, Research, Teaching, CV navigation, portrait, contact, and JMP first. Papers offer Abstract and Draft links. | Progressive disclosure of abstracts keeps the research page readable. |
| Ian Pitman | Chicago, explicitly 2026–27 market | https://ipitman.github.io/ | Research, Teaching, CV navigation and three short homepage paragraphs: affiliation/field, JMP, market statement. | Excellent evidence for using a short homepage and separate research and teaching pages. |

