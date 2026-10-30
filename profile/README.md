# Lean FDP: FAIR Data Points without containers

Turn a repository on GitHub or another forge into a [FAIR Data Point](https://specs.fairdatapoint.org/): machine-readable DCAT metadata, built by the forge's CI and served by its Pages. No server, no containers, no database, no infrastructure cost.

Lean FDP was called StaticFDP until October 2026. It was never really static: the forge validates, crawls, assesses and rebuilds it all the time. Old `github.com/StaticFDP/…` links redirect here.

### 🌱 Start your own FDP ecosystem

**[fdp.semscape.org/ecosystems](https://fdp.semscape.org/ecosystems/)** is the place to start. Use the **[FDP ecosystem template](https://github.com/LeanFDP/fdp-ecosystem-template)** and in a few minutes you have:
- an FDP that describes *every way to get each resource*, with a website
- self-service contributions through an issue form
- contributor credit linked to Wikidata and ORCID
- automatic FAIR assessment

[**Use the template →**](https://github.com/new?template_owner=LeanFDP&template_name=fdp-ecosystem-template) · [Demo](https://fdp.semscape.org/fdp-ecosystem-template/) · [Biodiversity FDP](https://koetai.github.io/biodiversity-fdp/), built with it

### Which repository does what

Lean FDP has one repository per layer. Older repositories have been folded in; they stay readable until they are archived.

| Layer | Repository | Status |
|---|---|---|
| Website | [LeanFDP.github.io](https://github.com/LeanFDP/LeanFDP.github.io): [fdp.semscape.org](https://fdp.semscape.org/) | Active |
| Publish an FDP | [fdp-ecosystem-template](https://github.com/LeanFDP/fdp-ecosystem-template): catalogs, website, contributions, FAIR tests | **Canonical** |
| Index | [fdp-index](https://github.com/LeanFDP/fdp-index): the [FDP Index](https://fdp.semscape.org/fdp-index/), crawled daily; register your FDP there | **Canonical** |
| Virtual Platform | [staticfdp-vp](https://github.com/LeanFDP/staticfdp-vp): aggregates FDP indexes | Experimental |
| Publish (2023 original) | [static-fdp](https://github.com/LeanFDP/static-fdp) | ShEx validation moved to the template ([#1](https://github.com/LeanFDP/fdp-ecosystem-template/pull/1)); to be archived |
| Publish (2026 rewrite) | [staticfdp](https://github.com/LeanFDP/staticfdp) | ORCID form and Codeberg mirror moved to the template ([#2](https://github.com/LeanFDP/fdp-ecosystem-template/pull/2)); to be archived |
| Index (2026 rewrite) | [staticfdp-index](https://github.com/LeanFDP/staticfdp-index) | Registration form moved to fdp-index ([#1](https://github.com/LeanFDP/fdp-index/pull/1)); to be archived |

The Codeberg mirrors follow the same plan.
