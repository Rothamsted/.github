<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/RothResearch/.github/main/profile/logo-lockup-dark.png">
  <img src="https://raw.githubusercontent.com/RothResearch/.github/main/profile/logo-lockup.png" alt="Rothamsted Research" width="440">
</picture>

### Research software, analysis code and data tools from Rothamsted Research

[Rothamsted Research](https://www.rothamsted.ac.uk) is a BBSRC-supported agricultural science institute at Harpenden, Hertfordshire, with further sites at North Wyke and Brooms Barn. It has been running field experiments continuously since 1843.

This organisation is where our code lives — the pipelines behind our papers, the models, the data tools, and the software our scientists build and share.

---

## What belongs here

Anything you would want a colleague, a reviewer, or your future self to be able to run:

- analysis code and pipelines supporting a publication
- models, simulations and statistical workflows
- data processing, cleaning and QC tools
- web applications, APIs and visualisations
- packages and libraries
- teaching and training material

Small, single-purpose repositories age better than one large one. If in doubt, publish it — a rough repository that exists beats a tidy one that does not.

## Publishing your code here

**1. Ask for access.** Open an issue on [this repository](https://github.com/RothResearch/.github/issues), or contact [@Arnedeklerk](https://github.com/Arnedeklerk). Tell us the project and who needs to be on it.

**2. Create your repository.** Name it for what it does, lowercase and hyphenated — `wheat-yield-model`, not `Project1`. Start private if the work is unpublished; make it public when you are ready.

**3. Make it findable.** Add a description, a few topics, and a README that answers: what is this, how do I run it, what does it need, who do I ask.

**4. Release and cite.** When the work is published, tag a release and mint a DOI (see below) so the code can be cited alongside the paper.

## What a good repository looks like

| Include | Why |
|---|---|
| `README.md` | What it does, how to install and run it, expected inputs and outputs, a contact |
| `LICENSE` | Without one, nobody can legally reuse your work — including Rothamsted |
| `CITATION.cff` | So the code is cited correctly. GitHub reads this and shows a *Cite this repository* button |
| Pinned dependencies | `environment.yml`, `requirements.txt`, `renv.lock`, `pom.xml` — whatever your stack uses |
| Example data | A small sample input, so someone can check the thing runs at all |
| Tagged releases | A version you can point a paper at |

## Before your first push

Git history is very hard to clean, so check before it is committed rather than after:

- **No credentials.** No passwords, API keys, tokens or `.env` files. Use environment variables or a secrets store.
- **No personal data.** Anything covered by GDPR stays out of the repository.
- **No third-party data you cannot redistribute.** Check the licence on data you did not generate.
- **Check before making unpublished work public.** Talk to your PI and, where commercial interest or IP is involved, to the relevant office.

## Licensing

For open work we suggest:

- **Code** — [MIT](https://choosealicense.com/licenses/mit/) for maximum reuse, or [Apache-2.0](https://choosealicense.com/licenses/apache-2.0/) if you want an explicit patent grant
- **Documentation and data** — [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/)

If a funder, collaborator or contract specifies something else, that takes precedence.

## Citing software

Add a [`CITATION.cff`](https://citation-file-format.github.io/) to the root of your repository and GitHub will render a citation for you. To get a DOI, connect the repository to [Zenodo](https://zenodo.org) and cut a release — Zenodo archives it and issues a DOI you can put in the paper.

## Help

- **Access, or a new repository** — open an issue on [this repository](https://github.com/RothResearch/.github/issues)
- **Research data management** — the [ELIXIR RDMkit](https://rdmkit.elixir-europe.org/) is a good starting point
- **Good practice in research software** — the [Software Sustainability Institute](https://www.software.ac.uk/) guides are worth the read

---

<sub>Rothamsted Research is strategically funded by the [Biotechnology and Biological Sciences Research Council](https://www.ukri.org/councils/bbsrc/) (BBSRC), part of UK Research and Innovation. · [rothamsted.ac.uk](https://www.rothamsted.ac.uk)</sub>
