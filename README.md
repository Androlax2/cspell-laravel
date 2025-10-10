# CSpell Laravel Dictionary

Laravel framework dictionary for cspell.

This is a dictionary for use with cspell that contains common Laravel framework terms.

## Requirements

| Tool                                                   | Version |
|--------------------------------------------------------|---------|
| [cspell](https://github.com/streetsidesoftware/cspell) | `>= 8`  |

## Installation

```bash
npm install --save-dev @androlax2/cspell-laravel
```

## Configuration

Add the following to your project's cspell configuration file (e.g. `cspell.json`, `.vscode/cspell.json`):

```json
{
  "import": [
    "@androlax2/cspell-laravel/cspell-ext.json"
  ]
}
```
