# dotfiles

Hey wes what settings do you use?

These are my config setting for various apps, editors and linters. I'd suggest not copying them directly but referencing what I have and what ones might make sense for you.

These are constantly changing as I work on different types of projects so I don't necessarily always have an answer to "y do u do ____ instead of ____"

Enjoy! 😘


## Explanations
* **[Wes Bos .bttpreset](./Wes Bos .bttpreset)** → My [Better Touch Tool]() Settings. This is a collection of shortcuts and automations that I use around window management, video editing, snap areas, and much more. I will do a video on this tool one day - it's amazing.
* **[settings.json](./settings.json)** → VS Code Settings
* **[vs-code-extensions-i-use.md](./vs-code-extensions-i-use.md)** → ya get?
* **[keybindings.json](./keybindings.json)** → Custom Keyboard shortcuts. The emmet Ctrl + E is how I get emmet to work anywhere.
* **[javascript.snippets.json](./javascript.snippets.json)** → Some JS Snippets
* **[hot-tip-vscode-settings.json](./hot-tip-vscode-settings.json)** → Workspace settings I use for recording my short form content


## Keeping up to date

This is for wes to remember what I did.

I created "hard links", so the content is available inside git.

```bash
ln ~/Library/ApplicationSupport/Code/User/settings.json settings.json
ln ~/Library/ApplicationSupport/Code/User/keybindings.json keybindings.json
ln ~/Videos/hot-tips/.vscode/settings.json ./hot-tip-vscode-settings.json

```
