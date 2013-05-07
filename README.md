# logikal's dotfiles

## Sublime Text 2

Installation:

1. Use boxen to install ST2
2. Start ST2
3. Install [Package Control](http://wbond.net/sublime_packages/package_control)
4. `rm -rf /Users/logikal/Library/Application Support/Sublime Text 2/Packages/User`
5. `ln -s ~/.dotfiles/sublime/Users /Users/logikal/Library/Application Support/Sublime Text 2/Packages/User`
6. Restart ST2. Package Control will reinstall everything.

### Themes

* [Railscasts](https://gist.github.com/firedev/2948029)

## zsh

* Use boxen to install ZSH
* Install oh-my-zsh
* `rm ~/.zshrc`
* `ln -s ~/.dotfiles/zsh/.zshrc ~/.zshrc`
* `source ~/.zshrc`