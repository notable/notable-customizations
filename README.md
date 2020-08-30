# Notable Customizations

This repository contains a collection of interesting community-created customizations and tips for Notable.

Add your own interesting customization to this collection by submiting a pull request or sharing it in our [chat](https://chat.notable.app).

## Commands

List of interesting command usages.

- _No customizations yet_

## Context keys

List of interesting context keys expressions.

- _No customizations yet_

## Settings

List of interesting settings configurations.

- _No customizations yet_

## Shortcuts

List of interesting custom shortcuts.

Paste clipboard content surrounded by code fence:
```
  { 
    "shortcut": "Cmd+Shift+D",
    "command": "macro", 
    "args": [
      ["editor.paste",["```\n"]],
      "editor.paste",
      ["editor.paste",["\n```\n"]]
    ]
  }
```

Turn selection into code fence:
```
  { 
    "shortcut": "Cmd+D",
    "command": "macro", 
    "args": [
      "editor.cut",
      ["editor.paste",["```\n"]],
      "editor.paste",
      ["editor.paste",["\n```\n"]]
    ]
  }
```

Surround selected text with e.g. double-asterisks:
```
  { 
    "shortcut": "Cmd+B",
    "command": "macro", 
    "args": [
      "editor.cut",
      ["editor.paste",["**"]],
      "editor.paste",
      ["editor.paste",["**"]]
    ]
  }
```

Insert text at beginning of line, e.g. headers
```
  {
    "shortcut": "Cmd+3",
    "command": "macro", 
    "args": [
      "editor.cursor.line.start",
      ["editor.paste",["### "]]
    ]
  }
 ```

## Theming

List of interesting theming-related configurations.

- 3500+ different themes ported from VS Code are installable via the "Theme: Install..." command


## Other customizations

List of other interesting customizations, mainly involving third-party tools.

- Tags:
  - [Autocomplete YAML tags from Vim](https://github.com/RyanGreenup/Note-Taking-Tools/blob/master/auto-complete-tags-vim/Auto-Complete-Tags.md)
  - [Synchronizing tags with TMSU](https://github.com/RyanGreenup/Note-Taking-Tools/blob/master/tags-to-TMSU/Import-Tags-to-TMSU.md)
- Searching:
  - [Use Recoll Search Engine from Terminal (integrates well with VSCode)](https://github.com/RyanGreenup/Note-Taking-Tools/blob/master/Terminal-Skim-Recoll/Terminal-Skim-Recoll.md)
- Organisation:
  - [Reorder notes in folders matching Notebooks](https://gist.github.com/amelandri/555fdac374a24896f3be2f6ad32e0521)
  - [Print BackLinks](https://github.com/RyanGreenup/Note-Taking-Tools/blob/master/List-BackLinks/ListBacklinks.md)
