# Conf VS Code

## Font
- Donwload [FiraCode](https://github.com/tonsky/FiraCode)
- Install the fonts
  - Create a directory with name `fonts` at `~/.local/share`
  - Past the fonts at this directory
  - Run the command `fc-cache -f -v` in the terminal
  - To see if the font was installed run the command `fc-list | grep "Fira"`
- In the VS Code open the file `settings.json`
  - Press `Ctrl+p` and type `.json` and find for `settings.json`
- Inside of the object json in `settings.json` insert the lines below and save
  - `"editor.fontFamily": "Fira Code",`
  - `"editor.fontLigatures": true`
  
  
## Plugins
- Auto Rename Tag
- Color Highlight
- CSS Peek
- DotENV
- Dracula At Night
- EditorConfig for VS Code
- GitLens
- Highlight Matching Tag
- Laravel Blade Snippets
- Laravel goto views
- Markdown All in One
- Material Icon Theme
- PHP Intelephense
- PHP IntelliSense
- Vetur
- vscode-styled-components
- vue
