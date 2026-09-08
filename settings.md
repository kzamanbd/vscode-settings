## VS Code Settings

```json
{
    "git.autofetch": true,
    "git.confirmSync": false,
    "git.enableSmartCommit": true,
    "git.openRepositoryInParentFolders": "always",
    "gitlens.advanced.messages": {
        "suppressGitMissingWarning": true,
        "suppressLineUncommittedWarning": true,
        "suppressIntegrationDisconnectedTooManyFailedRequestsWarning": true
    },
    "gitlens.integrations.enabled": false,
    "diffEditor.wordWrap": "on",
    "diffEditor.renderSideBySide": false,
    "window.openFoldersInNewWindow": "on",
    "window.closeWhenEmpty": true,
    "window.restoreWindows": "preserve",
    "window.commandCenter": false,
    "html.format.indentInnerHtml": true,
    "prettier.tabWidth": 4,
    "prettier.printWidth": 100,
    "prettier.singleQuote": true,
    "prettier.trailingComma": "none",
    "prettier.bracketSameLine": true,
    "prettier.vueIndentScriptAndStyle": true,
    "editor.formatOnSave": false,
    "editor.insertSpaces": true,
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
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": "explicit",
        "source.organizeImports": "never"
    },
    "Laravel.translation.diagnostics": false,
    "eslint.validate": [
        "javascript",
        "javascriptreact",
        "typescript",
        "typescriptreact",
        "vue",
        "vue-html"
    ],
    "eslint.format.enable": true,
    "notebook.stickyScroll.enabled": true,
    "emmet.triggerExpansionOnTab": true,
    "emmet.includeLanguages": {
        "blade": "html",
        "vue-html": "html",
        "react": "html",
        "javascript": "html"
    },
    "workbench.tips.enabled": false,
    "workbench.activityBar.location": "top",
    "workbench.tree.renderIndentGuides": "always",
    "workbench.iconTheme": "material-icon-theme",
    "workbench.tree.enableStickyScroll": true,
    "workbench.browser.showInTitleBar": true,
    "workbench.colorTheme": "Andromeda Italic",
    "workbench.experimental.share.enabled": true,
    "workbench.editor.editorActionsLocation": "titleBar",
    "workbench.editor.customLabels.patterns": {
        "**/{layout,index,loading,error}.vue": "${dirname}/${filename}",
        "**/{layout,page,loading,error,route}.tsx": "${dirname}/${filename}"
    },
    "explorer.compactFolders": false,
    "explorer.confirmDelete": false,
    "explorer.confirmPasteNative": false,
    "explorer.fileNesting.enabled": true,
    "explorer.fileNesting.patterns": {
        "*.ts": "${capture}.js",
        "*.js": "${capture}.js.map, ${capture}.min.js, ${capture}.d.ts",
        "*.jsx": "${capture}.js",
        "*.tsx": "${capture}.ts",
        "tsconfig.json": "tsconfig.*.json",
        "package.json": "package-lock.json, yarn.lock, pnpm-lock.yaml, pnpm-workspace.yaml, bun.lockb",
        "pubspec.yaml": "pubspec.lock,pubspec_overrides.yaml,.packages,.flutter-plugins,.flutter-plugins-dependencies,.metadata",
        "*.dart": "${capture}.g.dart",
        "composer.json": "composer.lock",
        "*.php": "${basename}Test.php",
        "psalm.xml": "psalm-baseline.xml",
        ".php-cs-fixer.php": ".php-cs-fixer.cache",
        "phpunit.xml": ".phpunit.result.cache",
        "*.sqlite": "${capture}.${extname}-*",
        "*.db": "${capture}.${extname}-*",
        "*.sqlite3": "${capture}.${extname}-*",
        "*.db3": "${capture}.${extname}-*",
        "*.sdb": "${capture}.${extname}-*",
        "*.s3db": "${capture}.${extname}-*"
    },
    "files.autoSave": "onWindowChange",
    "files.associations": {
        "*.embeddedhtml": "html",
        ".php_cs.dist": "php",
        ".php_cs": "php",
        "artisan": "php",
        "phpunit.xml.dist": "xml",
        ".pre": "php"
    },
    "redhat.telemetry.enabled": true,
    "accessibility.signalOptions.volume": 20,
    "security.workspace.trust.untrustedFiles": "open",
    "vue.inlayHints.missingProps": true,
    "vue.inlayHints.inlineHandlerLeading": true,
    "vue.inlayHints.optionsWrapper": true,
    "vue.inlayHints.vBindShorthand": true,
    "js/ts.updateImportsOnFileMove.enabled": "never",
    "js/ts.inlayHints.parameterNames.enabled": "all",
    "js/ts.inlayHints.propertyDeclarationTypes.enabled": true,
    "js/ts.inlayHints.parameterTypes.enabled": true,
    "js/ts.inlayHints.functionLikeReturnTypes.enabled": true,
    "js/ts.referencesCodeLens.enabled": true,
    "js/ts.referencesCodeLens.showOnAllFunctions": true,
    "js/ts.format.semicolons": "insert",
    "php-docblocker.returnGap": true,
    "phpSniffer.run": "never",
    "C_Cpp.formatting": "vcFormat",
    "C_Cpp.vcFormat.newLine.beforeOpenBrace.block": "sameLine",
    "C_Cpp.vcFormat.newLine.beforeOpenBrace.function": "sameLine",
    "C_Cpp.vcFormat.newLine.beforeOpenBrace.lambda": "sameLine",
    "[c]": {
        "editor.defaultFormatter": "ms-vscode.cpptools"
    },
    "[cpp]": {
        "editor.defaultFormatter": "ms-vscode.cpptools"
    },
    "[php]": {
        "editor.defaultFormatter": "laravel.vscode-laravel"
    },
    "[blade]": {
        "editor.defaultFormatter": "DEVSENSE.phptools-vscode"
    },
    "[yaml]": {
        "editor.defaultFormatter": "redhat.vscode-yaml"
    },
    "[shellscript]": {
        "editor.defaultFormatter": "foxundermoon.shell-format"
    },
    "[dotenv]": {
        "editor.defaultFormatter": "foxundermoon.shell-format"
    },
    "[dart]": {
        "editor.tabSize": 4,
        "editor.insertSpaces": true,
        "editor.detectIndentation": false
    },
    "cSpell.userWords": [
        "axios",
        "dokan",
        "draftscripts",
        "enderror",
        "endforeach",
        "endforelse",
        "forelse",
        "Inertia",
        "kamruzzaman",
        "kzaman",
        "kzamanbd",
        "laravel",
        "livewire",
        "Nuxt",
        "paystack",
        "texty",
        "vite",
        "woocommerce"
    ],
    "C_Cpp.default.cppStandard": "c++20",
    "C_Cpp.default.cStandard": "c11",
    "C_Cpp.default.compilerPath": "/opt/homebrew/bin/g++-15",
    "C_Cpp.default.intelliSenseMode": "macos-gcc-arm64",
    "code-runner.terminalRoot": "/",
    "code-runner.saveFileBeforeRun": true,
    "code-runner.clearPreviousOutput": true,
    "code-runner.showExecutionMessage": false,
    "code-runner.executorMap": {
        "php": "php",
        "javascript": "node",
        "python": "python3",
        "go": "go run",
        "typescript": "ts-node",
        "dart": "dart",
        "java": "cd $dir && javac $fileName && java $fileNameWithoutExt",
        "c": "cd $dir && gcc $fileName -o $fileNameWithoutExt.exe && $dir$fileNameWithoutExt.exe < input.txt",
        "cpp": "cd $dir && g++ $fileName -o $fileNameWithoutExt.exe && $dir$fileNameWithoutExt.exe < input.txt"
    },
    "security.workspace.trust.banner": "always",
    "security.promptForLocalFileProtocolHandling": false,
    "search.exclude": {
        "**/node_modules": true,
        "**/bower_components": true,
        "**/*.code-search": true,
        "**/.dart_tool": true,
        "_ide_helper.php": true,
        "_ide_helper_models.php": true,
        ".php_cs.cache": true,
        ".phpstorm.meta.php": true,
        ".phpunit.result.cache": true
    },
    "[dockercompose]": {
        "editor.insertSpaces": true,
        "editor.tabSize": 4,
        "editor.autoIndent": "advanced",
        "editor.quickSuggestions": {
            "other": true,
            "comments": false,
            "strings": true
        },
        "editor.defaultFormatter": "redhat.vscode-yaml"
    },
    "[github-actions-workflow]": {
        "editor.defaultFormatter": "redhat.vscode-yaml"
    },
    "chat.mcp.gallery.enabled": true,
    "diffEditor.ignoreTrimWhitespace": true,
    "dart.debugExternalPackageLibraries": true,
    "dart.debugSdkLibraries": true,
    "git.replaceTagsWhenPull": true,
    "chat.instructionsFilesLocations": {
        ".github/instructions": true,
        ".claude/rules": true,
        "~/.copilot/instructions": true,
        "~/.claude/rules": true
    },
    "chat.tips.enabled": false,
    "gitlens.ai.model": "anthropic:claude-opus-4-8",
    "gitlens.ai.gitkraken.model": "gemini:gemini-2.5-flash",
    "terminal.integrated.mouseWheelScrollSensitivity": 3,
    "diffEditor.hideUnchangedRegions.enabled": true,
    "terminal.integrated.gpuAcceleration": "off",
    "terminal.external.osxExec": "Warp.app",
    "chat.viewSessions.orientation": "stacked",
    "claudeCode.preferredLocation": "panel"
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
}
```
