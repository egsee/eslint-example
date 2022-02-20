### url

```
<!--  -->
https://www.digitalocean.com/community/tutorials/linting-and-formatting-with-eslint-in-vs-code
<!--  -->
https://daveceddia.com/vscode-use-eslintrc/#:~:text=1.%20Install%20VSCode%20ESLint%20Plugin%20In%20VSCode%2C%20open,use%20ESLint%20for%20Formatting%20Open%20up%20VSCode%E2%80%99s%20settings.
<!--  -->
https://juejin.cn/post/6844903661726875656
```

```
// settings.json
{
    "editor.fontSize": 13.9,
    // display white space and tap key.
    "editor.formatOnSave": false,
    "editor.renderControlCharacters": true,
    "editor.renderWhitespace": "all",
    "editor.tabSize": 4,
    "[jsonc]": {
        "editor.defaultFormatter": "vscode.json-language-features"
    },
    "[javascript]": {
        "editor.defaultFormatter": "vscode.typescript-language-features"
    },
    "[markdown]": {
        "editor.wordWrap": "on",
        "editor.quickSuggestions": true,
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[html]": {
        "editor.defaultFormatter": "vscode.html-language-features"
        // "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[json]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[javascriptreact]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[typescript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "editor.suggestSelection": "first",
    "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
    "files.exclude": {
        "**/.classpath": true,
        "**/.project": true,
        "**/.settings": true,
        "**/.factorypath": true
    },
    // git
    "git.path": "/usr/bin/git",
    // maven
    "maven.terminal.useJavaHome": true,
    "redhat.telemetry.enabled": false,
    // 
    "[php]": {
        "editor.defaultFormatter": "bmewburn.vscode-intelephense-client"
    },
    "namespaceResolver.showMessageOnStatusBar": true,
    "namespaceResolver.autoSort": false,
    // php docblocker
    "php-docblocker.returnVoid": false,
    "php-docblocker.returnGap": true,
    "php-docblocker.useShortNames": false,
    "php-docblocker.qualifyClassNames": true,
    "php-docblocker.alignParams": true, //参数对齐
    "php-docblocker.alignReturn": false, //return对齐
    "php-docblocker.varDescription": true, //@var
    "php-docblocker.paramDescription": true,
    "php-docblocker.returnDescription": true, //@return 占位符
    "php-docblocker.extra": [
        "@throws"
    ],
    "php-docblocker.functionTemplate": {
        //"message": {},
        "param": {
            "gapBefore": true
        },
        "return": {},
        "extra": {
            "gapBefore": true
        },
    },
    "php-docblocker.classTemplate": {
        "message": {
            "gapAfter": true
        },
        // "method": {
        //     "content": "@method ${1:mixed} ${2:methodName()}"
        // }
    },
    "git.enableSmartCommit": true,
    "[go]": {
        "editor.defaultFormatter": "golang.go"
    },
    "editor.tabCompletion": "off",
    "vetur.format.options.tabSize": 4,
    "editor.detectIndentation": false,
    "[dockercompose]": {
        "editor.defaultFormatter": "ms-azuretools.vscode-docker"
    },
    "[python]": {
        "editor.defaultFormatter": "ms-python.python"
    },
    "namespaceResolver.sortOnSave": true,
    "namespaceResolver.sortAlphabetically": true,
    "git.confirmSync": false,
    "window.zoomLevel": 1,
    "go.toolsManagement.autoUpdate": true,
    "diffEditor.ignoreTrimWhitespace": false,
    // default formatter
    "editor.defaultFormatter": "dbaeumer.vscode-eslint",
    "vetur.format.defaultFormatter.js": "prettier-eslint",
    "vetur.format.defaultFormatterOptions": {},
    // eslint setting
    "eslint.alwaysShowStatus": true,
    "eslint.format.enable": true,
    // 220 eslint validate 
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true
    },
    "eslint.validate": [
        "javascript"
    ]
}
```