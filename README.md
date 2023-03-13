# IntegrandoVSCode-GitBash
Pequeno código json para configurar o terminal do Git Bash como terminal padrão dentro do Visual Studio Code

Copie e cole essas configurações no arquivo settings.json do VS Code:

```json
  "terminal.integrated.profiles.windows": {
    "Git Bash": {
      "path": "C:\\Program Files\\Git\\bin\\bash.exe",
    }
  },
  "terminal.integrated.defaultProfile.windows": "Git Bash"
```
