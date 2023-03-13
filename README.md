# IntegrandoVSCode-GitBash
Pequeno código json para configurar o terminal do Git Bash dentro do editor de texto Visual Studio Code

Copie e cole essas configurações no arquivo settings.json do Visual Studio code:

```json
{
  "terminal.integrated.profiles.windows": {
    "Git Bash": {
      "path": "C:\\Program Files\\Git\\bin\\bash.exe",
    }
  },
  "terminal.integrated.defaultProfile.windows": "Git Bash"
}
```
