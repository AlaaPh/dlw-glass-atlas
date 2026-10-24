# DLW Glass Atlas

Glasses used for femtosecond direct laser writing (DLW) of waveguides: material properties,
how each glass responds to the laser, writing parameters reported in papers, the experiments,
and suppliers (German suppliers first).

Open the site: `index.html` (served by GitHub Pages). It is a static snapshot from October 2026.

## Data

All numbers come from the files in `data/` (JSON, one row per item):

| File | Content |
|---|---|
| `glasses.json` | one row per glass: family, optical class, composition, laser response; short text plus full research notes (`*_full`) |
| `properties.json` | material properties per glass, each with its source URL |
| `papers.json` | one row per paper and glass: bibliography, writing laser (λ, τ, f, E, P, NA, speed, depth), waveguide result, experiment, where the details were read |
| `vendors.json` | supplier offers: product, formats, published price with date seen, services |
| `groups.json`, `group_papers.json` | key research groups and their papers |
| `india.json` | groups in India working on fs-written waveguides |
| `laser.json` | output range of the lab's CARBIDE laser, used for the "With our laser" comparison |

Writing parameters are taken from the papers; an empty value means not stated or not accessible,
never estimated. DOIs were matched through search results, not Crossref: check a DOI before citing it.
