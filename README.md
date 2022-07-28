# My own [project-config] styles

## Python (`python/`)

- `base.json5`: Base styles for Python. Include it at start.
- `single-quotes.json5`: Single quotes for strings. Use [autopep8] and [add-trailing-comma] for formatting.
- `double-quotes.json5`: Double quotes for strings. Use [black] and [add-trailing-comma] for formatting.
- `line-length-80.json5`: 80 characters as maximum line length.
- `tests.json5`: The project has tests. Use [pytest].
- `google-docstrings.json5`: Google docstrings convention.
- `sphinx.json5`: Documentation using Sphinx.
- `readthedocs.json5`: Documentation using ReadTheDocs theme for Sphinx.
- `mdpo.json5`: Documentation with Markdown files, translations using [mdpo].
- `mypy.json5`: Type checking using [mypy].

### Minimum requirements

- `version/min-36.json5`: Python 3.6 as the minimum required version.
- `version/min-37.json5`: Python 3.7 as the minimum required version.

[project-config]: https://github.com/mondeja/project-config
[autopep8]: https://pypi.org/project/autopep8/
[add-trailing-comma]: https://pypi.org/project/add-trailing-comma/
[black]: https://pypi.org/project/black/
[pytest]: https://docs.pytest.org/en/latest/
[mdpo]: https://mondeja.github.io/mdpo/
[mypy]: https://mypy.readthedocs.io/en/latest/
