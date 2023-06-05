<div align="center">

  # 💠 .dotfiles

  <sub>My Linux KDE dot files.</sub>
  
  <img src="https://github.com/THEGOLDENPRO/.dotfiles/assets/66202304/2fee3f3f-fcf5-4686-a94c-41d79cf516a5" width="900px">

</div>

<br>

> #### ⚠️ THIS WILL OVERWRITE YOUR SYSTEM'S CONFIGS WITH MINE.
##### ❗ IF IT BRICKS YOUR SYSTEM DON'T BLAME ME BECAUSE I WARNED YOU.

## 🛠 *Install/Usage*
1. **Git clone.**
Make sure you clone this into the HOME directory.
```sh
cd $HOME
git clone https://github.com/THEGOLDENPRO/.dotfiles
```

2. **Run install script.**
⚠️ You should stop here if you don't want your configs to be overwritten and lost forever. :) *(trust me it's not fun, I'm warning you)*
```sh
cd .dotfiles
git submodule update --recursive --remote # Pull devgoldyutils libaray.
python install.py
```

<br>

If you would like to only link a single file, the ``--one-file`` argument will help you with that:
```sh
python install.py --one-file {file_name_as_in_json}
```

If you want to overwrite all files without the yes and no prompt run the script with the ``--overwrite`` argument like so:
```sh
python install.py --overwrite
```
