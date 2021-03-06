# cheatsheets-personal

This repository contains personal cheatsheets to be used with [cheat][] and similar applications.

## Format

Cheatsheets are plain-text files that begin with an optional "front matter" header in YAML format. The header may be used to assign "tags" to a sheet, and to specify the sheet's syntax (`bash`, `python`, `go`, etc).

When possible, cheatsheets should conform to this format:

```sh
---
syntax: bash
tags: [ vcs, development ]
---
# To stage all changes in the current directory:
git add --all

# To commit staged changes:
git commit -m <message>
```

As a guideline, it is preferred to use [docopt][] syntax when specifying parameter placeholders. In edge-cases where that syntax may cause confusion, it is permissible to use placeholder values (`foo.txt`, `example.com`, etc.) as necessary.

## License

See [LICENSE.md](.github/LICENSE.md) for the full license text.


[cheat]:  https://github.com/cheat/cheat
[docopt]: http://docopt.org

