## Utilities


### `pre-commit`

A Git hook that verifies that:

1. Added files don't have non-ASCII characters in their names.
2. Jupyter notebooks don't have output cells.

To use, copy this script to the `.git/hooks` directory:
```sh
cp utils/pre-commit .git/hooks/
```
