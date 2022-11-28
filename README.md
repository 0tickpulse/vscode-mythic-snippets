# vscode-mythic-snippets

## How to make them autocomplete automatically

Go to Preferences > Open User Settings (JSON), and enter this:

```json
    "editor.quickSuggestions": {
        "other": true,
        "comments": false,
        "strings": true
    },
```
