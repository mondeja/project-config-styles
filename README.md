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
  format files. You can add more files to check adding the styles
  `base/pre-commit/pretter/{format}.json5`, see the current
  [supported files][pre-commit-prettier-formats] or
  [contribute with your own][pull-requests-link].

## Python (`python/`)

- `base.json5`: Base styles for Python. Include it at start. Use [hatch]
  for building, versioning, environments and publishing. Use [pre-commit]
  for linting and formatting.
- `sphinx.json5`: Documentation using Sphinx.
- `readthedocs.json5`: Documentation using ReadTheDocs theme for Sphinx.
- `mdpo.json5`: Documentation with Markdown files, translations using
  [mdpo] with [pre-commit].
- `mypy.json5`: Type checking using [mypy] with [pre-commit].

<!-- External links: -->

[project-config]: https://github.com/mondeja/project-config
[mdpo]: https://mondeja.github.io/mdpo/
[mypy]: https://mypy.readthedocs.io/en/latest/
[pre-commit]: https://pre-commit.com
[md2po2md]: https://mondeja.github.io/mdpo/latest/pre-commit-hooks.html#md2po2md
[markdown-link-check]: https://github.com/tcort/markdown-link-check
[prettier]: https://prettier.io
[hatch]: https://hatch.pypa.io/

<!-- Internal links: -->

[pull-requests-link]: https://github.com/mondeja/project-config-styles/pulls
[pre-commit-prettier-formats]: https://github.com/mondeja/project-config-styles/tree/master/base/pre-commit/prettier
