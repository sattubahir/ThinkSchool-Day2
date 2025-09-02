## VS Code Settings
Below is the full content of my ".vscode/settings.json" file --
{
    "code-runner.runInTerminal": true,
    "liveServer.settings.donotShowInfoMsg": true,
    "editor.codeActionsOnSave": {
        "source.organizeImports": "explicit"
    },
    "editor.linkedEditing": true,
    "editor.minimap.enabled": false,
    "editor.rulers": [
        {
            "column": 80,
            "color": "#00FF0010"
        },
        {
            "column": 100,
            "color": "#BDB76B15"
        },
        {
            "column": 120,
            "color": "#FA807219"
        }
    ],
    "editor.unicodeHighlight.includeComments": true,
    "emmet.variables": {
        "lang": "en"
    },
    "workbench.colorCustomizations": {
        "[Default Dark Modern]": {
            "tab.activeBorderTop": "#00FF00",
            "tab.unfocusedActiveBorderTop": "#00FF0088",
            "textCodeBlock.background": "#00000055"
        },
        "editor.wordHighlightStrongBorder": "#FF6347",
        "editor.wordHighlightBorder": "#FFD700",
        "editor.selectionHighlightBorder": "#A9A9A9"
    },
    "workbench.editor.revealIfOpen": true,
    "workbench.tree.indent": 20,
    "files.eol": "\n",
    "[bat]": {
        "files.eol": "\r\n"
    },
    "terminal.integrated.enablePersistentSessions": false,
    "terminal.integrated.tabs.hideCondition": "never",
    "java.configuration.updateBuildConfiguration": "automatic",
    "java.debug.settings.hotCodeReplace": "auto",
    "java.sources.organizeImports.staticStarThreshold": 1,
    "cSpell.diagnosticLevel": "Hint",
    "trailing-spaces.includeEmptyLines": false,
    "terminal.integrated.defaultProfile.windows": "JavaSE-21 LTS",
    "maven.executable.path": "C:\\Users\\Satyajit\\AppData\\Roaming\\Code\\User\\globalStorage\\pleiades.java-extension-pack-jdk\\maven\\latest\\bin\\mvn",
    "java.import.gradle.home": "C:\\Users\\Satyajit\\AppData\\Roaming\\Code\\User\\globalStorage\\pleiades.java-extension-pack-jdk\\gradle\\latest",
    "java.configuration.runtimes": [
    
        {
            "name": "JavaSE-1.8",
            "path": "C:\\Users\\Satyajit\\AppData\\Roaming\\Code\\User\\globalStorage\\pleiades.java-extension-pack-jdk\\java\\8"
        },
        {
            "name": "JavaSE-11",
            "path": "C:\\Users\\Satyajit\\AppData\\Roaming\\Code\\User\\globalStorage\\pleiades.java-extension-pack-jdk\\java\\11"
        },
        {
            "name": "JavaSE-17",
            "path": "C:\\Users\\Satyajit\\AppData\\Roaming\\Code\\User\\globalStorage\\pleiades.java-extension-pack-jdk\\java\\17",
            "default": true
        },
        {
            "name": "JavaSE-21",
            "path": "C:\\Users\\Satyajit\\AppData\\Roaming\\Code\\User\\globalStorage\\pleiades.java-extension-pack-jdk\\java\\21"
        },
        {
            "name": "JavaSE-24",
            "path": "C:\\Users\\Satyajit\\AppData\\Roaming\\Code\\User\\globalStorage\\pleiades.java-extension-pack-jdk\\java\\latest"
        }
    ],
    "java.import.gradle.java.home": "C:\\Users\\Satyajit\\AppData\\Roaming\\Code\\User\\globalStorage\\pleiades.java-extension-pack-jdk\\java\\21",
    "maven.terminal.customEnv": [
        {
            "environmentVariable": "JAVA_HOME",
            "value": "c:\\Users\\Satyajit\\AppData\\Roaming\\Code\\User\\globalStorage\\pleiades.java-extension-pack-jdk\\java\\21"
        }
    ],
    "terminal.integrated.env.windows": {
        "PATH": "c:\\Users\\Satyajit\\AppData\\Roaming\\Code\\User\\globalStorage\\pleiades.java-extension-pack-jdk\\java\\17\\bin;${env:PATH}",
        "JAVA_HOME": "c:\\Users\\Satyajit\\AppData\\Roaming\\Code\\User\\globalStorage\\pleiades.java-extension-pack-jdk\\java\\17"
    },
    "terminal.integrated.profiles.windows": {
        "JavaSE-1.8 LTS": {
            "overrideName": true,
            "env": {
                "PATH": "C:\\Users\\Satyajit\\AppData\\Roaming\\Code\\User\\globalStorage\\pleiades.java-extension-pack-jdk\\java\\8\\bin;${env:PATH}",
                "JAVA_HOME": "C:\\Users\\Satyajit\\AppData\\Roaming\\Code\\User\\globalStorage\\pleiades.java-extension-pack-jdk\\java\\8"
            },
            "path": "cmd"
        },
        "JavaSE-11 LTS": {
            "overrideName": true,
            "env": {
                "PATH": "C:\\Users\\Satyajit\\AppData\\Roaming\\Code\\User\\globalStorage\\pleiades.java-extension-pack-jdk\\java\\11\\bin;${env:PATH}",
                "JAVA_HOME": "C:\\Users\\Satyajit\\AppData\\Roaming\\Code\\User\\globalStorage\\pleiades.java-extension-pack-jdk\\java\\11"
            },
            "path": "cmd"
        },
        "JavaSE-17 LTS": {
            "overrideName": true,
            "env": {
                "PATH": "C:\\Users\\Satyajit\\AppData\\Roaming\\Code\\User\\globalStorage\\pleiades.java-extension-pack-jdk\\java\\17\\bin;${env:PATH}",
                "JAVA_HOME": "C:\\Users\\Satyajit\\AppData\\Roaming\\Code\\User\\globalStorage\\pleiades.java-extension-pack-jdk\\java\\17"
            },
            "path": "cmd"
        },
        "JavaSE-21 LTS": {
            "overrideName": true,
            "env": {
                "PATH": "C:\\Users\\Satyajit\\AppData\\Roaming\\Code\\User\\globalStorage\\pleiades.java-extension-pack-jdk\\java\\21\\bin;${env:PATH}",
                "JAVA_TOOL_OPTIONS": "-Dstdout.encoding=UTF-8 -Dstderr.encoding=UTF-8",
                "JAVA_HOME": "C:\\Users\\Satyajit\\AppData\\Roaming\\Code\\User\\globalStorage\\pleiades.java-extension-pack-jdk\\java\\21"
            },
            "path": "cmd",
            "args": [
                "/k",
                "chcp",
                "65001"
            ]
        },
        "JavaSE-24": {
            "overrideName": true,
            "env": {
                "PATH": "C:\\Users\\Satyajit\\AppData\\Roaming\\Code\\User\\globalStorage\\pleiades.java-extension-pack-jdk\\java\\latest\\bin;${env:PATH}",
                "JAVA_TOOL_OPTIONS": "-Dstdout.encoding=UTF-8 -Dstderr.encoding=UTF-8",
                "JAVA_HOME": "C:\\Users\\Satyajit\\AppData\\Roaming\\Code\\User\\globalStorage\\pleiades.java-extension-pack-jdk\\java\\latest"
            },
            "path": "cmd",
            "args": [
                "/k",
                "chcp",
                "65001"
            ]
        }
    },
    "cmake.configureOnOpen": true,
    "java.configuration.detectJdksAtStart": false,
    "trailing-spaces.backgroundColor": "rgba(255,0,0,0.1)",
    "terminal.integrated.automationProfile.windows": {
        "path": "cmd"
    },
    "java.test.config": {
        "vmArgs": [
            "-Dstdout.encoding=UTF-8",
            "-Dstderr.encoding=UTF-8"
        ]
    },
    "java.dependency.packagePresentation": "hierarchical",
    "java.compile.nullAnalysis.mode": "automatic",
    "java.maxConcurrentBuilds": 8,
    "python.defaultInterpreterPath": "c:\\Users\\Satyajit\\AppData\\Local\\Programs\\Python\\Python312\\python.exe",
    "json.schemas": [
    

    ],
    "editor.formatOnSave": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.codeActionsOnSave": { "source.fixAll.eslint": "explicit" },
  "prettier.requireConfig": true  
}

## Installed VS Code Extensions
- esbenp.prettier-vscode         <!-- Prettier code formatter 
- dbaeumer.vscode-eslint         <!-- ESLint integration for code linting 
- formulahendry.code-runner      <!-- To run code snippets in terminal 
- ritwickdey.LiveServer          <!-- Live Server for local development
- redhat.java                   <!-- Java Language Support 
- vscjava.vscode-maven           <!-- Apache Maven for Java projects 
- vscjava.vscode-java-pack       <!-- Java Extension Pack 
- ms-python.python               <!-- Python language support (based on python interpreter path) 
- ms-vscode.cpptools             <!-- C/C++ tools maybe for cmake support 
- ms-vscode.cmake-tools          <!-- CMake integration 
- streetsidesoftware.code-spell-checker <!-- Spell checker as cSpell used 
- eamodio.gitlens                <!-- GitLens for enhanced git capabilities 
