# config for windows-terminal
Manage all my settings for windows terminal and profile settings from same repository.

## Usage
### Windows Terminal
- Install the Windows Terminal from the Microsoft Store or using winget
`winget install --id Microsoft.WindowsTerminal -e`

- cd into Windows Terminal folder
`cd %localappdata%\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe`

- Delete the LocalState folder
`rd /S /Q LocalState`

- Create a symlink to LocalState from windows-terminal folder
`mklink /D LocalState "C:\SLinks\windows-terminal"`