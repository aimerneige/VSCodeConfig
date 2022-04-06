# My config for Visual Studio Code

## About

This is my own config for VSCode.

## Theme

```json
    "workbench.iconTheme": "material-icon-theme",
    "workbench.colorTheme": "Palenight Theme",
    "editor.fontFamily": "'Operator Mono', Consolas, 'Courier New', monospace",
    "window.zoomLevel": 0,
    "editor.fontSize": 14,
```

## Terminal

This is for windows.

```json
    "terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe",
    "terminal.integrated.fontFamily": "Fira Code",
    "terminal.integrated.fontSize": 12,
    "terminal.integrated.rightClickCopyPaste": true
```

## Markdown

```json
    "[markdown]": {
        "editor.defaultFormatter": "yzhang.markdown-all-in-one"
    }
```

## Spell Check

```json
    "cSpell.userWords": [
        "aimer",
        "aimer neige",
        "aimerneige",
        "anduin",
        "centos",
        "cmap",
        "demenu",
        "dmenu",
        "dmenu run",
        "fcitx",
        "hakase",
        "inory",
        "libreoffice",
        "lybia",
        "marp",
        "mathjax",
        "matplotlib",
        "monika",
        "mylist",
        "natsuki",
        "neige",
        "netease",
        "nums",
        "prefs",
        "pygal",
        "pygame",
        "pyplot",
        "run",
        "sayori",
        "shared",
        "shared prefs",
        "shinpuru",
        "studyaholic",
        "typora",
        "xaxis",
        "xiaoming",
        "xlabel",
        "yaxis",
        "ylabel",
        "zfill"
    ],
```

```
"editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "name": "italic font",
        "scope": [
          "comment",
          "keyword",
          "storage",
          "keyword.control.import",
          "keyword.control.default",
          "keyword.control.from",
          "keyword.operator.new",
          "keyword.control.export",
          "keyword.control.flow",
          "storage.type.class",
          "storage.type.function",
          "storage.type",
          "storage.type.class",
          "variable.language",
          "variable.language.super",
          "variable.language.this",
          "meta.class",
          "meta.var.expr",
          "constant.language.null",
          "support.type.primitive",
          "entity.name.method.js",
          "entity.other.attribute-name",
          "punctuation.definition.comment",
          "text.html.basic entity.other.attribute-name.html",
          "text.html.basic entity.other.attribute-name",
          "tag.decorator.js entity.name.tag.js",
          "tag.decorator.js punctuation.definition.tag.js",
          "source.js constant.other.object.key.js string.unquoted.label.js",
        ],
        "settings": {
          "fontStyle": "italic",
        }
      },
    ]
  },
```
