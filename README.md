# My own [project-config] styles

## Base styles (`base/`)

- `project-config.json5`: Configuration for [project-config] using a
  `pyproject.toml` file and [pre-commit] to run it.

### Pre-commit hooks (`base/pre-commit/`)

- `md2po2md.json5`: [md2po2md] configuration for [pre-commit]
  to convert Markdown to PO and back.
- `markdown-link-check.json5`: [markdown-link-check] configuration
  for [pre-commit] to check links in Markdown files.
- `prettier.json5`: minimal [prettier] configuration for [pre-commit] to
  format files.

## Python (`python/`)

- `base.json5`: Base styles for Python. Include it at start. Use [hatch]
  for building, versioning, environments and publishing.
- `single-quotes.json5`: Single quotes for strings. Use [autopep8] and
  [add-trailing-comma] for formatting.
- `double-quotes.json5`: Double quotes for strings. Use [black] for
  formatting.
- `line-length-80.json5`: 80 characters as maximum line length.
- `tests.json5`: The project has tests. Use [pytest].
- `google-docstrings.json5`: Google docstrings convention.
- `sphinx.json5`: Documentation using Sphinx.
- `readthedocs.json5`: Documentation using ReadTheDocs theme for Sphinx.
- `mdpo.json5`: Documentation with Markdown files, translations using [mdpo].
- `mypy.json5`: Type checking using [mypy].

[project-config]: https://github.com/mondeja/project-config
[autopep8]: https://pypi.org/project/autopep8/
[add-trailing-comma]: https://pypi.org/project/add-trailing-comma/
[black]: https://pypi.org/project/black/
[pytest]: https://docs.pytest.org/en/latest/
[mdpo]: https://mondeja.github.io/mdpo/
[mypy]: https://mypy.readthedocs.io/en/latest/
[pre-commit]: https://pre-commit.com
[md2po2md]: https://mondeja.github.io/mdpo/latest/pre-commit-hooks.html#md2po2md
[markdown-link-check]: https://github.com/tcort/markdown-link-check
[prettier]: https://prettier.io
[hatch]: https://hatch.pypa.io/
