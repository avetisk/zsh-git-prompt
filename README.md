# zsh-git-prompt
simple zsh git prompt using libgit2 for speed 🚀

## install

```sh
git clone git@github.com:avetisk/zsh-git-prompt.git path/to/opt
```

Then in your `.zshrc`:

```sh
local git_prompt=$(eval echo -n $(/path/to/opt/zsh-git-prompt/zsh-git-prompt))
export PS1="$git_prompt >"
```

You can of course make a symlink to your `/usr/local/bin` in order to avoid the
long path.

# licence
MIT
