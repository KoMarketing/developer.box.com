---
rank: 100
related_endpoints: []
related_guides: []
required_guides: []
alias_paths: []
---

# Limitations

A few limitations exists when working with files.

## Name restrictions

There are some restrictions to a file's name. Names containing non-printable
ASCII characters, forward and backward slashes (`/`, `\`), and protected names like
`.` and `..` are automatically sanitized by removing the non-allowed characters.
