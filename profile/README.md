# StaticFDP: FAIR Data Points on GitHub

Turn a GitHub repository into a [FAIR Data Point](https://specs.fairdatapoint.org/): machine-readable DCAT metadata served by GitHub Pages. No server, no database, no infrastructure cost.

### 🌱 Start your own FDP ecosystem

**[fdp.semscape.org/ecosystems](https://fdp.semscape.org/ecosystems/)** is the place to start. Use the **[FDP ecosystem template](https://github.com/StaticFDP/fdp-ecosystem-template)** and in a few minutes you have:
- an FDP that describes *every way to get each resource*, with a website
- self-service contributions through an issue form
- contributor credit linked to Wikidata and ORCID
- automatic FAIR assessment

[**Use the template →**](https://github.com/new?template_owner=StaticFDP&template_name=fdp-ecosystem-template) · [Demo](https://fdp.semscape.org/fdp-ecosystem-template/) · [Biodiversity FDP](https://koetai.github.io/biodiversity-fdp/), built with it

### Which repository does what

StaticFDP has one repository per layer. Older repositories are being folded in; they stay readable until they are archived.

| Layer | Repository | Status |
|---|---|---|
| Website | [StaticFDP.github.io](https://github.com/StaticFDP/StaticFDP.github.io): [fdp.semscape.org](https://fdp.semscape.org/) | Active |
| Publish an FDP | [fdp-ecosystem-template](https://github.com/StaticFDP/fdp-ecosystem-template): catalogs, website, contributions, FAIR tests | **Canonical** |
| Index | [fdp-index](https://github.com/StaticFDP/fdp-index): the [FDP Index](https://fdp.semscape.org/fdp-index/), crawled daily; register your FDP there | **Canonical** |
| Virtual Platform | [staticfdp-vp](https://github.com/StaticFDP/staticfdp-vp): aggregates FDP indexes | Experimental |
| Publish (2023 original) | [static-fdp](https://github.com/StaticFDP/static-fdp) | ShEx validation moves to the template ([#1](https://github.com/StaticFDP/fdp-ecosystem-template/pull/1)), then archive |
| Publish (2026 rewrite) | [staticfdp](https://github.com/StaticFDP/staticfdp) | ORCID form and Codeberg mirror move to the template ([#2](https://github.com/StaticFDP/fdp-ecosystem-template/pull/2)), then archive |
| Index (2026 rewrite) | [staticfdp-index](https://github.com/StaticFDP/staticfdp-index) | Registration form moves to fdp-index ([#1](https://github.com/StaticFDP/fdp-index/pull/1)), then archive |

The Codeberg mirrors follow the same plan.
