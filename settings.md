## VS Code Settings

```json
{
    "github.copilot.enable": {
        "*": true,
        "plaintext": true,
        "markdown": true,
        "scminput": false
    },
    "gitlens.advanced.messages": {
        "suppressGitMissingWarning": true,
        "suppressLineUncommittedWarning": true
    },
    "git.autofetch": true,
    "git.confirmSync": false,
    "git.openRepositoryInParentFolders": "always",
    "git.enableSmartCommit": true,
    "diffEditor.hideUnchangedRegions.enabled": true,
    "diffEditor.renderSideBySide": false,
    "explorer.confirmPasteNative": false,
    "window.openFoldersInNewWindow": "on",
    "liveServer.settings.donotShowInfoMsg": true,
    "html.format.indentInnerHtml": true,
    "prettier.tabWidth": 4,
    "editor.insertSpaces": true,
    "prettier.printWidth": 120,
    "prettier.singleQuote": true,
    "prettier.trailingComma": "none",
    "prettier.bracketSameLine": true,
    "prettier.vueIndentScriptAndStyle": true,
    "editor.formatOnSave": true,
    "editor.tabCompletion": "on",
    "editor.linkedEditing": true,
    "editor.cursorBlinking": "expand",
    "editor.scrollbar.scrollByPage": true,
    "editor.renderWhitespace": "none",
    "editor.fontLigatures": "'ss01', 'ss02', 'ss03', 'ss04', 'ss05', 'ss06', 'ss07', 'ss08', 'calt', 'dlig'",
    "editor.fontFamily": "'Fira Code', Consolas",
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.cursorSmoothCaretAnimation": "on",
    "editor.unicodeHighlight.ambiguousCharacters": false,
    "editor.bracketPairColorization.independentColorPoolPerBracketType": true,
    "editor.guides.bracketPairs": "active",
    "editor.largeFileOptimizations": true,
    "eslint.validate": ["javascript", "javascriptreact", "vue", "vue-html"],
    "files.autoSave": "onWindowChange",
    "javascript.format.semicolons": "insert",
    "notebook.stickyScroll.enabled": true,
    "emmet.triggerExpansionOnTab": true,
    "emmet.includeLanguages": {
        "blade": "html",
        "vue-html": "html",
        "react": "html",
        "javascript": "html",
        "blade.php": "html",
        "twig": "html"
    },
    "workbench.tree.indent": 15,
    "explorer.confirmDelete": false,
    "diffEditor.wordWrap": "on",
    "redhat.telemetry.enabled": true,
    "workbench.startupEditor": "none",
    "workbench.sideBar.location": "right",
    "accessibility.signalOptions.volume": 20,
    "bladeFormatter.format.indentInnerHtml": true,
    "workbench.tree.renderIndentGuides": "always",
    "workbench.colorTheme": "Andromeda Italic Bordered",
    "workbench.iconTheme": "material-icon-theme",
    "workbench.tree.enableStickyScroll": true,
    "workbench.colorCustomizations": {
        "tree.indentGuidesStroke": "#05ef3c",
        "titleBar.activeBackground": "#026CD1",
        "titleBar.activeForeground": "#FFFFFF",
        "editorSuggestWidget.selectedBackground": "#231739",
        "terminalCursor.foreground": "#C45DFF"
    },
    "security.workspace.trust.untrustedFiles": "open",
    "remote.SSH.remotePlatform": {
        "203.188.245.58": "linux"
    },
    "explorer.compactFolders": false,
    "workbench.activityBar.location": "top",
    "inline-parameters.showPhpDollar": true,
    "vue.inlayHints.missingProps": true,
    "vue.inlayHints.inlineHandlerLeading": true,
    "vue.inlayHints.optionsWrapper": true,
    "vue.inlayHints.vBindShorthand": true,
    "javascript.updateImportsOnFileMove.enabled": "never",
    "javascript.inlayHints.parameterNames.enabled": "all",
    "javascript.inlayHints.propertyDeclarationTypes.enabled": true,
    "javascript.inlayHints.parameterTypes.enabled": true,
    "javascript.inlayHints.enumMemberValues.enabled": true,
    "javascript.inlayHints.functionLikeReturnTypes.enabled": true,
    "typescript.format.semicolons": "insert",
    "typescript.inlayHints.parameterNames.enabled": "all",
    "typescript.inlayHints.propertyDeclarationTypes.enabled": true,
    "typescript.inlayHints.parameterTypes.enabled": true,
    "typescript.inlayHints.functionLikeReturnTypes.enabled": true,
    "php-docblocker.returnGap": true,
    "phpfmt.psr2": false,
    "phpfmt.exclude": ["AllmanStyleBraces", "SpaceAroundParentheses"],
    "phpfmt.passes": [
        "AlignDoubleArrow",
        "AutoSemicolon",
        "SortUseNameSpace",
        "SpaceBetweenMethods",
        "SpaceAroundControlStructures",
        "GeneratePHPDoc"
    ],
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
    "[dart]": {
        "editor.tabSize": 4,
        "editor.rulers": [120],
        "editor.detectIndentation": true,
        "editor.formatOnType": true,
        "editor.suggestSelection": "first",
        "editor.wordBasedSuggestions": "off"
    },
    "cSpell.userWords": ["axios", "kamruzzaman", "kzaman", "kzamanbd", "Nuxt"],
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
    "apc.menubar.compact": true,
    "workbench.tips.enabled": false,
    "apc.stylesheet": {
        ".composite.title h2::before": "content: '💻🚀'; margin-right: 6px;",
        ".quick-input-widget.show-file-icons, .editor-widget.find-widget": "box-shadow: none !important",
        ".filematch .monaco-icon-label:before, .custom-list-row.results .monaco-list-row .monaco-icon-label:before": "background-position: 0 bottom !important",
        ".filematch .monaco-count-badge": "padding: 5px 6px 0 6px !important",
        ".monaco-workbench .part.titlebar>.titlebar-container>.titlebar-left": {
            "width": "auto !important;"
        },
        ".monaco-editor .cursors-layer .cursor": "background-image: linear-gradient(135deg, #67D0FF 10%, #C45DFF 100%)",
        ".monaco-scrollable-element > .shadow.top": {
            "box-shadow": "0px 0px 10px rgba(0, 0, 0, 0.75) !important;",
            "top": "-3px !important;"
        },
        ".monaco-editor-hover,.monaco-hover": {
            "box-shadow": "0px 8px 32px rgba(0, 0, 0, 0.45) !important;",
            "padding": "10px !important;",
            "background-image": "linear-gradient(#3c3c50 0%, #2a2b38 100%) !important;",
            "backdrop-filter": "blur(3px) !important;",
            "border-radius": "10px !important;",
            "border": "none !important;"
        },
        ".quick-input-widget": {
            "transform": "translateY(-50%) !important;",
            "top": "50% !important;",
            "box-shadow": "0px 8px 20px rgba(0, 0, 0, 0.45) !important;",
            "padding": "10px 10px 18px 10px !important;",
            "background-image": "linear-gradient(#3c3c50 0%, #2a2b38 100%) !important;",
            "backdrop-filter": "blur(3px) !important;",
            "border-radius": "20px !important;"
        },
        ".quick-input-filter .monaco-inputbox": {
            "border-radius": "12px !important;",
            "padding": "8px !important;",
            "border": "none !important;",
            "background-color": "rgba(34, 34, 34, 0.4) !important;",
            "font-size": "14px !important;",
            "margin-bottom": "16px !important;"
        },

        "#command-blur": {
            "position": "absolute;",
            "top": "0;",
            "left": "0;",
            "width": "100%;",
            "height": "100%;",
            "background": "rgba(0, 0, 0, 0.15);",
            "backdrop-filter": "blur(8px);"
        },

        ".monaco-inputbox input::placeholder": {
            "color": "rgba(255, 255, 255, 0.3) !important;"
        },
        ".command-center-center": {
            "width": "auto !important;",
            "text-transform": "uppercase !important;",
            "font-weight": "bold !important;",
            "background": "transparent !important;",
            "border": "none !important;"
        },
        ".quick-input-list .monaco-scrollable-element": {
            "border-radius": "10px !important;",
            "padding": "0px"
        },
        ".editor-group-watermark": {
            "max-width": "none !important;"
        },
        ".letterpress": {
            "background-image": "url(https://kzamanbd.github.io/vscode-settings/background.png) !important;",
            "background-position": "center center !important;",
            "background-size": "contain !important;",
            "width": "60% !important;"
        }
    },
    "explorer.fileNesting.patterns": {
        "*.ts": "${capture}.js",
        "*.js": "${capture}.js.map, ${capture}.min.js, ${capture}.d.ts",
        "*.jsx": "${capture}.js",
        "*.tsx": "${capture}.ts",
        "tsconfig.json": "tsconfig.*.json",
        "package.json": "package-lock.json, yarn.lock, pnpm-lock.yaml, bun.lockb",
        "composer.json": "composer.lock",
        "psalm.xml": "psalm-baseline.xml",
        ".php-cs-fixer.php": ".php-cs-fixer.cache",
        "phpunit.xml": ".phpunit.result.cache",
        "*.php": "${basename}Test.php"
    },
    "files.associations": {
        ".php_cs.dist": "php",
        ".php_cs": "php",
        ".pre": "php",
        "artisan": "php"
    },
    "search.exclude": {
        "**/node_modules": true,
        "**/bower_components": true,
        "**/*.code-search": true,
        "_ide_helper.php": true,
        "_ide_helper_models.php": true,
        ".php_cs.cache": true,
        ".phpstorm.meta.php": true,
        ".phpunit.result.cache": true
    },
}
```
