# zsh-git-prompt
simple zsh git prompt using libgit2 for speed 🚀

## install

Be sure to have libgit2 installed!

### OSX
```sh
brew install libgit2
git clone git@github.com:avetisk/zsh-git-prompt.git path/to/opt
cd /path/to/opt/zsh-git-prompt
pip install -r requirements.txt
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
