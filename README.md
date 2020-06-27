# WindowsTerminalConfig
My personal Windows Terminal configuration file.

## Local installation :hammer_and_wrench:
To install from a Windows 10 Command Prompt:
```properties
cd %LOCALAPPDATA%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState
move settings.json settings_backup.json
git init .
git remote add origin https://github.com/JacobBerlin/WindowsTerminalConfig.git
git pull origin master
```

## Additional features :heavy_check_mark:
* Copy on mouse select
* CTRL+T to open a tab
* CTRL+W to close a tab
* CTRL+SHIFT+4 to open Git Bash shell (default)