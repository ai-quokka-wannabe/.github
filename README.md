# .github

The [ai-quokka-wannabe](https://github.com/ai-quokka-wannabe) organisation's own repository. GitHub
treats an organisation's `.github` repository specially: the `profile/README.md` kept here is the
greeting rendered on the organisation's page, <https://github.com/ai-quokka-wannabe>, and some files
kept here would become defaults for the whole organisation (see below).

## What Lives Here

- `profile/README.md` — the greeting itself, the first thing a visitor to the organisation reads.
- The furniture every repository in the organisation carries, mirrored from the flagship,
  [tron-grid-lite](https://github.com/ai-quokka-wannabe/tron-grid-lite): the editor and markdown
  lint settings, the pinned linter, Dependabot and the workflows. There is nothing here to build,
  so CI runs the part of the flagship's quick checks that applies to markdown — the lint, stray
  carriage returns, internal links and anchors — behind the same `CI Success` gate.

A code of conduct, a contributing guide, a security policy or issue and pull request templates
kept in this repository would become the defaults for every repository in the organisation that
lacks its own. None are kept here: adding one is a decision for the whole organisation, not for
this repository alone.

## Editing

Edits go through pull requests, as in every repository of the organisation, and `CI Success` must
be green before one merges. To run the same lint on the desk first:

```bash
npm ci
npx markdownlint-cli2 "**/*.md"
```

## Licence

Copyright © 2026 The AiQuokkaWannabe Authors <https://github.com/ai-quokka-wannabe/.github>.

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.

See the attached [LICENCE](LICENCE) file for more info.
