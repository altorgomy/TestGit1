Run this command and it will give you list of in installed packages:

```
code --list-extensions | xargs -L 1 echo code --install-extension
```

I have this packages:

```bash
code --install-extension adrianwilczynski.libman
code --install-extension akamud.vscode-theme-onedark
code --install-extension CoenraadS.bracket-pair-colorizer-2
code --install-extension donjayamanne.jupyter
code --install-extension emmanuelbeziat.vscode-great-icons
code --install-extension Equinusocio.vsc-community-material-theme
code --install-extension Equinusocio.vsc-material-theme
code --install-extension equinusocio.vsc-material-theme-icons
code --install-extension jchannon.csharpextensions
code --install-extension k--kato.docomment
code --install-extension ms-dotnettools.csharp
code --install-extension ms-mssql.mssql
code --install-extension ms-python.python
code --install-extension naumovs.color-highlight
code --install-extension PKief.material-icon-theme
code --install-extension pranaygp.vscode-css-peek
code --install-extension rahulsahay.Csharp-ASPNETCore
code --install-extension remimarsal.prettier-now
code --install-extension ritwickdey.live-sass
code --install-extension ritwickdey.LiveServer
code --install-extension schneiderpat.aspnet-helper
code --install-extension temilaj.asp-net-core-vs-code-extension-pack
code --install-extension thekalinga.bootstrap4-vscode
code --install-extension VisualStudioExptTeam.vscodeintellicode
```

User setting on `json` file
```JSON
{
    "files.autoSave": "afterDelay",
    "workbench.sideBar.location": "left",
    "editor.minimap.enabled": false,
    "workbench.iconTheme": "material-icon-theme",
    "git.confirmSync": false,
    "git.enableSmartCommit": true,
    "window.zoomLevel": 0,
    "python.pythonPath": "/Library/Frameworks/Python.framework/Versions/3.7/bin/python3",
    "breadcrumbs.enabled": false,
    "code-runner.executorMap": {
        "javascript": "node",
        "java": "cd $dir && javac $fileName && java $fileNameWithoutExt",
        "c": "cd $dir && gcc $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
        "cpp": "cd $dir && g++ $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
        "objective-c": "cd $dir && gcc -framework Cocoa $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
        "php": "php",
        "python": "python3 -u",
        "perl": "perl",
        "perl6": "perl6",
        "ruby": "ruby",
        "go": "go run",
        "lua": "lua",
        "groovy": "groovy",
        "powershell": "powershell -ExecutionPolicy ByPass -File",
        "bat": "cmd /c",
        "shellscript": "bash",
        "fsharp": "fsi",
        "csharp": "scriptcs",
        "vbscript": "cscript //Nologo",
        "typescript": "ts-node",
        "coffeescript": "coffee",
        "scala": "scala",
        "swift": "swift",
        "julia": "julia",
        "crystal": "crystal",
        "ocaml": "ocaml",
        "r": "Rscript",
        "applescript": "osascript",
        "clojure": "lein exec",
        "haxe": "haxe --cwd $dirWithoutTrailingSlash --run $fileNameWithoutExt",
        "rust": "cd $dir && rustc $fileName && $dir$fileNameWithoutExt",
        "racket": "racket",
        "ahk": "autohotkey",
        "autoit": "autoit3",
        "dart": "dart",
        "pascal": "cd $dir && fpc $fileName && $dir$fileNameWithoutExt",
        "d": "cd $dir && dmd $fileName && $dir$fileNameWithoutExt",
        "haskell": "runhaskell",
        "nim": "nim compile --verbosity:0 --hints:off --run",
        "lisp": "sbcl --script"
    },
    "code-runner.runInTerminal": true,
    "terminal.integrated.fontSize": 20,
    "editor.formatOnSave": true,
    "editor.suggestSelection": "first",
    "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
    "python.jediEnabled": false,
    "editor.fontSize": 20,
    "code-runner.clearPreviousOutput": true,
    "code-runner.saveFileBeforeRun": true,
    "workbench.colorTheme": "Material Theme Darker High Contrast",
    "[csharp]": {
        "editor.defaultFormatter": "remimarsal.prettier-now"
    },
    "[aspnetcorerazor]": {
        "editor.defaultFormatter": "ms-dotnettools.csharp"
    }
}

```
