<div align="center">
    <h1>Liuaena</h1>
    <img src="animation-0001.png" alt="liuaena logo">
    <p>Plymouth theme with UAENA lion logo</p>
</div>

### Installation

Clone and copy this repository to `/usr/share/plymouth/themes`

```bash
$ git clone https://github.com/DatSudo/liuaena
$ sudo cp -r liuaena /usr/share/plymouth/themes
```

Check if the theme is successfully installed by listing all the themes

```bash
$ sudo plymouth-set-default-theme -l
bgrt
details
fade-in
glow
liuaena
script
solar
spinfinity
spinner
text
tribar
```

Set `liuaena` as the default theme

```bash
$ sudo plymouth-set-default-theme -R liuaena
```

