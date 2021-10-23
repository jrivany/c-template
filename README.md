# Intro

A bare bones makefile based c project template for OSX with some extra configurations for vscode.

# Setup

Install clangd for better code completion found [here](https://marketplace.visualstudio.com/items?itemName=llvm-vs-code-extensions.vscode-clangd)

Disable the default c++ intellisense in settings.json (clangd should already prompt for this by default):

```
    "C_Cpp.intelliSenseEngine": "Disabled",
```

# Running

Open `src/main.c`.

From the debug tab, click run.

Profit.
