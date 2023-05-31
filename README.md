<div align="center">

  # 💠 .dotfiles

  <sub>My Linux KDE dot files.</sub>

</div>

> #### ⚠️ THIS WILL OVERWRITE YOUR SYSTEM'S CONFIGS WITH MINE.
> ##### ❗ IF IT BRICKS YOUR SYSTEM DON'T BLAME ME BECAUSE I WARNED YOU.

## 🛠 *Install/Usage*
1. **Git clone.**
Make sure you clone this into the HOME directory.
```sh
git clone https://github.com/THEGOLDENPRO/dotfiles
```

2. **Run install script.**
⚠️ You should stop here if you don't want your configs to be overwritten and lost forever. :) *(trust me it's not fun, I'm warning you)*
```sh
cd .dotfiles
python install.py
```

If you want to overwrite all files without the yes and no prompt run the script with the ``--overwrite`` argument like so:
```sh
python install.py --overwrite
```