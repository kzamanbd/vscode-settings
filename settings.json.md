## VS Code Settings

```json
{
    "github.copilot.enable": {
        "*": true,
        "plaintext": true,
        "markdown": true,
        "scminput": false
    },
    "editor.unicodeHighlight.ambiguousCharacters": false,
    "gitlens.advanced.messages": {
        "suppressGitMissingWarning": true,
        "suppressLineUncommittedWarning": true
    },
    "git.confirmSync": false,
    "git.autofetch": true,
    "git.openRepositoryInParentFolders": "always",
    "git.enableSmartCommit": true,
    "diffEditor.hideUnchangedRegions.enabled": true,
    "diffEditor.renderSideBySide": false,
    "explorer.confirmPasteNative": false,
    "github.copilot.editor.enableAutoCompletions": true,
    "window.openFoldersInNewWindow": "on",
    "liveServer.settings.donotShowInfoMsg": true,
    "html.format.indentInnerHtml": true,
    "prettier.tabWidth": 4,
    "prettier.singleQuote": true,
    "prettier.trailingComma": "none",
    "prettier.printWidth": 120,
    "prettier.bracketSameLine": true,
    "prettier.vueIndentScriptAndStyle": true,
    "editor.formatOnSave": true,
    "editor.tabCompletion": "on",
    "editor.linkedEditing": true,
    "editor.cursorBlinking": "expand",
    "editor.accessibilitySupport": "on",
    "editor.scrollbar.scrollByPage": true,
    "editor.renderWhitespace": "none",
    "editor.fontLigatures": true,
    "editor.fontFamily": "'Fira Code', Consolas",
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.cursorSmoothCaretAnimation": "on",
    "editor.bracketPairColorization.independentColorPoolPerBracketType": true,
    "editor.guides.bracketPairs": "active",
    "editor.largeFileOptimizations": true,
    "eslint.validate": ["javascript", "javascriptreact", "vue", "vue-html"],
    "files.autoSave": "onWindowChange",
    "javascript.format.semicolons": "insert",
    "emmet.triggerExpansionOnTab": true,
    "emmet.includeLanguages": {
        "javascript": "javascriptreact"
    },
    "bladeFormatter.format.indentInnerHtml": true,
    "explorer.confirmDelete": false,
    "diffEditor.wordWrap": "on",
    "redhat.telemetry.enabled": true,
    "workbench.startupEditor": "none",
    "workbench.sideBar.location": "right",
    "workbench.tree.indent": 15,
    "workbench.tree.renderIndentGuides": "always",
    "workbench.colorTheme": "Andromeda Italic Bordered",
    "workbench.iconTheme": "material-icon-theme",
    "workbench.tree.enableStickyScroll": true,
    "workbench.activityBar.location": "top",
    "workbench.colorCustomizations": {
        "tree.indentGuidesStroke": "#05ef3c",
        "titleBar.activeBackground": "#026CD1",
        "titleBar.activeForeground": "#FFFFFF"
    },
    "explorer.confirmDragAndDrop": false,
    "security.workspace.trust.untrustedFiles": "open",
    "remote.SSH.remotePlatform": {
        "203.188.245.58": "linux"
    },
    "notebook.stickyScroll.enabled": true,
    "C_Cpp.formatting": "vcFormat",
    "C_Cpp.vcFormat.newLine.beforeOpenBrace.block": "sameLine",
    "C_Cpp.vcFormat.newLine.beforeOpenBrace.function": "sameLine",
    "C_Cpp.vcFormat.newLine.beforeOpenBrace.lambda": "sameLine",
    "[c]": {
        "editor.defaultFormatter": "ms-vscode.cpptools",
        "editor.formatOnSave": true
    },
    "[cpp]": {
        "editor.defaultFormatter": "ms-vscode.cpptools",
        "editor.formatOnSave": true
    },
    "[php]": {
        "editor.defaultFormatter": "bmewburn.vscode-intelephense-client",
        "editor.formatOnSave": true
    },
    "[blade]": {
        "editor.defaultFormatter": "shufo.vscode-blade-formatter",
        "editor.formatOnSave": true
    },
    "[yaml]": {
        "editor.defaultFormatter": "redhat.vscode-yaml"
    },
    "[markdown]": {
        "editor.defaultFormatter": "DavidAnson.vscode-markdownlint",
        "editor.formatOnSave": true
    },
    "[shellscript]": {
        "editor.defaultFormatter": "shakram02.bash-beautify"
    },
    "cSpell.userWords": [
        "axios",
        "composables",
        "customizer",
        "draftscripts",
        "inertiajs",
        "Jerp",
        "KAMRUZZAMAN",
        "kzaman",
        "kzamanbd",
        "laravel",
        "Livewire",
        "pinia",
        "Simplebar",
        "tailwindcss",
        "upazila",
        "vuedraggable"
    ],
    "C_Cpp.default.cppStandard": "c++20",
    "C_Cpp.default.cStandard": "c11",
    "terminal.integrated.defaultProfile.windows": "Git Bash",
    "code-runner.terminalRoot": "/",
    "code-runner.saveFileBeforeRun": true,
    "code-runner.clearPreviousOutput": true,
    "code-runner.showExecutionMessage": false,
    "code-runner.executorMapByGlob": {
        "pom.xml": "cd $dir && mvn clean package"
    },
    "code-runner.executorMap": {
        "php": "php",
        "javascript": "node",
        "python": "python -u",
        "go": "go run",
        "powershell": "powershell -ExecutionPolicy ByPass -File",
        "bat": "cmd /c",
        "shellscript": "bash",
        "typescript": "ts-node",
        "swift": "swift",
        "dart": "dart",
        "java": "cd $dir && javac $fileName && java $fileNameWithoutExt",
        "c": "cd $dir && gcc $fileName -o $fileNameWithoutExt.exe && $dir$fileNameWithoutExt.exe < input.txt",
        "cpp": "cd $dir && g++ $fileName -o $fileNameWithoutExt.exe && $dir$fileNameWithoutExt.exe < input.txt"
    },
    "psi-header.templates": [
        {
            "language": "*",
            "template": [
                "Author: <<author>>",
                "Created Date: <<filecreated('dddd MMM yyyy')>>",
                "-----",
                "Last Modified: <<date>>",
                "Modified By: <<author>> (kzamanbn@gmail.com)",
                "-----",
                "Github: https://github.com/kzamanbd",
                "LeetCode: https://github.com/kzamanbd",
                "Copyright (c) <<yeartoyear(fc, now)>> <<author>>",
                "-----",
                "HISTORY:",
                "Date      \tBy\tComments",
                "----------\t---\t---------------------------------------------------------"
            ],
            "changeLogCaption": "HISTORY",
            "changeLogHeaderLineCount": 2,
            "changeLogEntryTemplate": ["", "<<dateformat('DD-MM-YYYY')>>\t<<initials>>\t"],
            "changeLogNaturalOrder": false,
            "changeLogFooterLineCount": 0
        }
    ],
    "javascript.updateImportsOnFileMove.enabled": "never",
    "typescript.format.semicolons": "insert"
```
