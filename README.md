<div align="center">
    <h1>PLYMOUAENA</h1>
    <p float="left">
        <img src="uaena/animation/animation-0087.png" alt="uaena logo">
        <img src="celebrity/animation/animation-0052.png" alt="IU - Celebrity album art">
    </p>
    <p>Collection of <a href="https://en.wikipedia.org/wiki/The_Golden_Hour:_Under_the_Orange_Sun">Golden Hour's</a> <a href="https://www.youtube.com/watch?v=AjYmFc_DzPE">drone show</a>-inspired <a href="https://wiki.archlinux.org/title/plymouth">Plymouth</a> theme.</p>
</div>

### Installation

Clone and copy this repository to `/usr/share/plymouth/themes`

```bash
$ git clone https://github.com/DatSudo/plymouaena
$ sudo cp -r plymouaena/uaena plymouth/celebrity -t /usr/share/plymouth/themes
```

Check if the theme is successfully installed by listing all the themes

```bash
$ sudo plymouth-set-default-theme -l
bgrt
celebrity
details
fade-in
glow
script
solar
spinfinity
spinner
text
tribar
uaena
```

Set either `uaena` or `celebrity` as the default theme

```bash
$ sudo plymouth-set-default-theme -R uaena
```

