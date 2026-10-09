---
"@biomejs/biome": patch
---

Added embedded CSS formatting for ``css({ name: `...` })`` when `javascript.experimentalEmbeddedSnippetsEnabled` is enabled. Template literal values of properties in an object literal passed as an argument to a call expression named `css` are formatted as CSS.
