# setting.json

{
    "workbench.colorTheme": "Developers Theme - Ocean",
    "explorer.fileNesting.patterns": {
        "*.ts": "${capture}.js",
        "*.js": "${capture}.js.map, ${capture}.min.js, ${capture}.d.ts",
        "*.jsx": "${capture}.js",
        "*.tsx": "${capture}.ts",
        "tsconfig.json": "tsconfig.*.json",
        "package.json": "package-lock.json, yarn.lock, pnpm-lock.yaml, bun.lockb",
        "*.sqlite": "${capture}.${extname}-*",
        "*.db": "${capture}.${extname}-*",
        "*.sqlite3": "${capture}.${extname}-*",
        "*.db3": "${capture}.${extname}-*",
        "*.sdb": "${capture}.${extname}-*",
        "*.s3db": "${capture}.${extname}-*"
    },
    "explorer.compactFolders": false,
    "files.autoSave": "afterDelay",
    "git.autofetch": true,
    "[dart]": {
        "editor.formatOnSave": true,
        "editor.formatOnType": true,
        "editor.rulers": [
            80
        ],
        "editor.selectionHighlight": false,
        "editor.tabCompletion": "onlySnippets",
        "editor.wordBasedSuggestions": "off"
    },
    "liveServer.settings.donotShowInfoMsg": true,
    "php.debug.executablePath": "",
    "database-client.autoSync": true,
    "git.confirmSync": false,
    "workbench.iconTheme": "material-icon-theme"
}
