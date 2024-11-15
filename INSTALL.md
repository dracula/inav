### [lnav](https://lnav.com)

#### Install using wget

You can download the theme-file directly from Github. 
Generate `installed` folder in your config path if not existing:
```bash
mkdir /home/$USER/.config/lnav/configs/installed/`
```

Now you can download the theme file:
```bash
wget https://raw.githubusercontent.com/dracula/lnav/refs/heads/main/dracula.json`
```

#### Install manually

Download using the [GitHub `.zip` download](https://github.com/dracula/lnav/archive/refs/heads/master.zip) option and unzip them.

#### Activating theme

1. Copy the `dracula.json` to your `$USER/.config/lnav/configs/installed/` folder
2. Open `lnav`
3. Use the command `:config /ui/theme dracula`
4. Color! 
