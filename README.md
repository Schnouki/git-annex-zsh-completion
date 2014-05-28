# ZSH completion for git-annex

This compdef allows tab completion for most of the [git-annex][] commands.
See also [tips in the git-annex ikiwiki](http://git-annex.branchable.com/tips/ZSH_completion/).

# Install

If you use [oh-my-zsh][] then just clone the repository inside your oh-my-zsh repo:

```Shell
git clone https://github.com/Schnouki/git-annex-zsh-completion.git ~/.oh-my-zsh/custom/plugins/git-annex
```

and enable it in your ```.zshrc```:

```zsh
plugins+=(git-annex)
```

[git-annex]: http://git-annex.branchable.com/
[oh-my-zsh]: http://github.com/robbyrussell/oh-my-zsh
