[Tmux Plugin Manager](https://github.com/tmux-plugins/tpm)
[Tmux Resurrect - restore tmux environment after system restart](https://github.com/tmux-plugins/tmux-resurrect)

### Installation
```bash
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
ln -s $PWD/tmux.conf ~/.tmux.conf
tmux kill-server
```

```bash
# type this in terminal if tmux is already running
$ tmux source ~/.tmux.conf
```

### Installing plugins

1. Add new plugin to `~/.tmux.conf` with `set -g @plugin '...'` (Already Done)
2. Press `prefix` + <kbd>I</kbd> (capital I, as in **I**nstall) to fetch the plugin.

### Tmux Resurrect Key bindings

- `prefix + Ctrl-s` - save
- `prefix + Ctrl-r` - restore