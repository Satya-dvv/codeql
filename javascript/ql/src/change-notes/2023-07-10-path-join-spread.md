---
category: minorAnalysis
---
* The `fs/promises` package is now recognised as an alias for `require('fs').promises`.
* The `js/path-injection` query can now track taint through calls to `path.join()` with a spread argument, such as `path.join(baseDir, ...args)`.
