```json
[
  {
    "key": "cmd+e",
    "command": "workbench.action.quickOpen"
  },
  {
    "key": "cmd+e",
    "command": "workbench.action.quickOpenNavigateNextInFilePicker",
    "when": "inFilesPicker && inQuickOpen"
  },

  {
    "key": "cmd+d",
    "command": "revealInExplorer",
    "when": "editorTextFocus && !sideBarFocus"
  },
  {
    "key": "cmd+d",
    "command": "workbench.action.toggleSidebarVisibility",
    "when": "editorIsOpen && sideBarFocus"
  },

  {
    "key": "n",
    "command": "explorer.newFile",
    "when": "sideBarFocus && !inputFocus"
  },
  {
    "key": "cmd+n",
    "command": "explorer.newFolder",
    "when": "sideBarFocus"
  }, 
  {
    "key": "d",
    "command": "deleteFile",
    "when": "sideBarFocus && !inputFocus"
  },
  {
    "key": "[Period]",
    "command": "-filesExplorer.openFilePreserveFocus",
    "when": "filesExplorerFocus && foldersViewVisible && !explorerResourceIsFolder && !inputFocus"
  }
]
```

comandi standard che uso spesso: 
1. aprire estensioni: cmd+shift+x 