# Linux

	以下命令要在 Qwerty 布局下用 Dvorak 指法输入。

	如：在 Qwerty 下以 Dvorak 指法输入 nraet.fo ekrpat，实际输出为："loadkeys dvorak"。

## Arch && Manjaro

刚刚得知，大多数 Linux 发行版都支持 `loadkeys dvorak` 这一命令。

tty中临时切换

```shell
nraet.fo ekrpat
```

Xorg中临时切换

```shell
o.yqtxmal ekrpat
```

长期切换

编辑 `/etc/vconsole.conf`

添加

```
KEYMAP=dvorak
```


## 其他配列

### Programmer Dvorak
### Left handed Dvorak
### Right handed Dvorak
