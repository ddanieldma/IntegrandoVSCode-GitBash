# IntegrandoVSCode-GitBash
Pequeno código json para configurar o terminal do Git Bash dentro do editor Visual Studio Code

Cole essas linhas no settings.json do Visual Studio Code:
{
  "terminal.integrated.profiles.windows": {
    "Git Bash": {
      "path": "C:\\Program Files\\Git\\bin\\bash.exe",
    }
  },
  "terminal.integrated.defaultProfile.windows": "Git Bash"
}
