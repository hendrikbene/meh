# Godot

##  External Editor for Visual studio code
Go to `Editor > Editor Settings > Text editor` 
- Use External editor: `On` 
- Exec path: `C:\Program Files\Microsoft VS Code\Code.exe`
- Exec flags: `{project} --goto {file}:{line}:{col}`


# Visual Studio Code

## Activate language server
In **VSCode** go to `Extentions > godot-tools > extention settings`
- Godot tool server: 1`27.0.0.1`
- Godot tool server port: `6005`
In **Godot** go to `Editor > Editor setting > Network > Language server`
- Remote host: `127.0.0.1`
- Remote port:  `6005`
