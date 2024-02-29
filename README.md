# tmux-conf
This repo provides configuration options for Tmux.

# Instructions
1. Make sure you have tmux installed. Instructions: https://github.com/tmux/tmux/wiki/Installing
2. Copy tmux.conf in the root directory of this repo to ~/.tmux.conf.
3. Install TPM using:
```
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
tmux source ~/.tmux.conf
```
4. Install the plugins in .tmux.conf using:
```
~/.tmux/plugins/tpm/bin/install_plugins
```
5. Play around with different configurations using:
```
tmux source-file ~/.tmux.conf
```
