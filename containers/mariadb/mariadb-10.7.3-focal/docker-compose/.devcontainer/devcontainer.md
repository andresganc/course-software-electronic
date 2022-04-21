// Ver extensiones instaladas
// code --list-extensions

// Config only 1 image - Extensions
{
    "name": "NC Gases",
    
    "build": {
        "dockerfile": "../Dockerfile",
    },
}




// Config to several images + Extensions

{
    "name": "NC Gases",
    //"dockerFile": "Dockerfile",
    "dockerComposeFile": "../docker-compose.yml",
    "service": "api",
    "workspaceFolder": "/api",
    "shutdownAction": "stopCompose",

    "settings": {
        //"terminal.integrated.shell.linux": "/bin/bash",
        "editor.fontSize": 14,
        "workbench.colorTheme": "Dobri Next -A05- Jaguar",
        "workbench.iconTheme": "material-icon-theme"
    },

    "extensions": [
        "christian-kohler.npm-intellisense",
        "christian-kohler.path-intellisense",
        "cirlorm.mobileview",
        "CoenraadS.bracket-pair-colorizer",
        "cweijan.vscode-database-client2",
        //"denoland.vscode-deno",
        "dsznajder.es7-react-js-snippets",
        "eg2.vscode-npm-script",
        "esbenp.prettier-vscode",
        "formulahendry.auto-close-tag",
        "formulahendry.auto-rename-tag",
        "Gruntfuggly.todo-tree",
        "jundat95.react-native-snippet",
        "ms-azuretools.vscode-docker",
        "ms-vscode-remote.remote-containers",
        "ms-vscode-remote.remote-ssh",
        "ms-vscode-remote.remote-ssh-edit",
        "ms-vscode.vscode-typescript-next",
        "msjsdiag.vscode-react-native",
        "naumovs.color-highlight",
        "Orta.vscode-jest",
        "PKief.material-icon-theme",
        "ritwickdey.LiveServer",
        "sldobri.bunker",
        "steoates.autoimport",
        "styled-components.vscode-styled-components",
        "syler.sass-indented",
        //"TabNine.tabnine-vscode",
        "tomoki1207.pdf",
        //"Wscats.eno"
    ]
}





// Config to 1 image + Extension

{
    "name": "NC Gases",
    //"dockerFile": "Dockerfile",
    //"dockerComposeFile": "../docker-compose.yml",
    //"service": "api",
    //"workspaceFolder": "/api",
    //"shutdownAction": "stopCompose",

    "build": {
        "dockerfile": "../Dockerfile",
    },

    "settings": {
        //"terminal.integrated.shell.linux": "/bin/bash",
        "editor.fontSize": 14,
        "workbench.colorTheme": "Dobri Next -A05- Jaguar",
        "workbench.iconTheme": "material-icon-theme"
    },

    "extensions": [
        "christian-kohler.npm-intellisense",
        "christian-kohler.path-intellisense",
        "cirlorm.mobileview",
        "CoenraadS.bracket-pair-colorizer",
        "cweijan.vscode-database-client2",
        //"denoland.vscode-deno",
        "dsznajder.es7-react-js-snippets",
        "eg2.vscode-npm-script",
        "esbenp.prettier-vscode",
        "formulahendry.auto-close-tag",
        "formulahendry.auto-rename-tag",
        "Gruntfuggly.todo-tree",
        "jundat95.react-native-snippet",
        "ms-azuretools.vscode-docker",
        "ms-vscode-remote.remote-containers",
        "ms-vscode-remote.remote-ssh",
        "ms-vscode-remote.remote-ssh-edit",
        "ms-vscode.vscode-typescript-next",
        "msjsdiag.vscode-react-native",
        "naumovs.color-highlight",
        "Orta.vscode-jest",
        "PKief.material-icon-theme",
        "ritwickdey.LiveServer",
        "sldobri.bunker",
        "steoates.autoimport",
        "styled-components.vscode-styled-components",
        "syler.sass-indented",
        //"TabNine.tabnine-vscode",
        "tomoki1207.pdf",
        //"Wscats.eno"
    ]
}

