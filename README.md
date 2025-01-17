# Spoofax Documentation

[![Build](https://github.com/metaborg/metaborg.github.io/actions/workflows/docs.yml/badge.svg)](https://github.com/metaborg/metaborg.github.io/actions)
[![Docs](https://img.shields.io/badge/docs-latest-brightgreen)](https://www.spoofax.dev/)
[![GitHub](https://img.shields.io/github/license/metaborg/metaborg.github.io)](https://github.com/metaborg/metaborg.github.io/blob/main/LICENSE)

This is the repository for the [Spoofax documentation](https://www.spoofax.dev/).
This documentation uses [MkDocs Material][1].

To build the pages and see edits live using Docker:

```bash
make
```

Or using Python 3:

```bash
pip install -r mkdocs_requirements.txt
mkdocs serve
```

Navigate to [localhost:8000](http://localhost:8000/) to see the documentation.
The local documentation is automatically reloaded when changes occur.
Changes pushed to the `main` branch are automatically deployed to Github Pages.

## Adding Pages
New pages should be added to the `mkdocs.yml` `nav` element. The first page mentioned under a section header should be some `**/index.md` without a label, and will be used as the index page for that section.


[1]: https://squidfunk.github.io/