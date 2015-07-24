# dotspacemacs
My dotspacemacs configuration, always a work in progress.

## Installation
To use this configuration all you need to do is:

Install `spacemacs` from here:
https://github.com/syl20bnr/spacemacs

And then:
```
git clone git@github.com:shaief/dotspacemacs.git ~/.spacemacs.d
```
Due to recent changes in `spacemacs`, the configuration file is now located in `~/.spacemacs.d/init.el`

Read more about it here:
https://github.com/syl20bnr/spacemacs/tree/develop#dotdirectory-spacemacsd

## Contents of this specific configuration
1. load a limited `python-mode` in case of huge Python file (more then 500kb).
2. In case of environment variable `FLYCHECK`, load it instead of the default `flake8`.
3. Highlight lines with `import pdb` and lines with `pdb.set_trace()`.
4. Change `text-scale` with normal keybindings: `C--`, `C-=`, `C-0` and `Ctrl+mouse wheel`.
5. Move lines Up-Down using `M-k` / `M-j`.
6. `SPC-d` `iedit-rectangle-mode`
7. More intuitive move Up-Down between lines in `visual-line-mode` using `j` / `k`.
