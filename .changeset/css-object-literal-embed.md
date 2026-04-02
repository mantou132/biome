---
"@biomejs/biome": patch
---

Added embedded CSS formatting for ``css({ name: `...` })`` when `javascript.experimentalEmbeddedSnippets` is enabled. Template literal values in the object literal passed as any argument to a call expression named `css` are formatted as CSS, including values in nested objects under that literal.
