<div align="center">
    <h1>PLYMOUAENA</h1>
    <img src="animation/animation-0087.png" alt="uaena logo">
    <p>Plymouth theme with UAENA logo</p>
</div>

### Installation

Clone and copy this repository to `/usr/share/plymouth/themes`

```bash
$ git clone https://github.com/DatSudo/plymouaena
$ sudo cp -r plymouaena /usr/share/plymouth/themes
```

Check if the theme is successfully installed by listing all the themes

```bash
$ sudo plymouth-set-default-theme -l
bgrt
details
fade-in
glow
plymouaena
script
solar
spinfinity
spinner
text
tribar
```

Set `plymouaena` as the default theme

```bash
$ sudo plymouth-set-default-theme -R plymouaena
```

