Neo 2015 - The final
====================

先按照
  https://github.com/district10/neo_keyboard_layout/tree/master/xx-alols-xcape
的指导安装 xcape。

再运行(如果你用 Neo 键盘布局)：

```bash
./neo.sh
```

相应地，如果你是 Qwerty 用户，运行：
```bash
./qwerty.sh
```

如果你是 Dvorak 用户，运行：
```bash
./dvorak.sh
```

如果你没有装上 xcape，那就用

```bash
./np.sh # neo plain
```

第三布局没有，就是普通的改造了的 dvorak。

Add to your .profile:

```shell
pgrep xcape > /dev/null || (cd ~/git/neo_keyboard_layout/neo2015 && ./neo.sh)
```

Level 1
-------
| 左手 | 左手 | 左手 | 左手 | 左手 | 右手 | 右手 | 右手 | 右手 | 右手 |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| ; | , | . | k | y | f | g | c | l | z |
| a | o | e | i | u | d | r | t | s | n |
| p | q | j | h | x | b | m | w | v | / |

Level 2
-------
| 左手 | 左手 | 左手 | 左手 | 左手 | 右手 | 右手 | 右手 | 右手 | 右手 |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| : | < | > | K | Y | F | G | C | L | Z |
| A | O | E | I | U | D | R | T | S | N |
| P | Q | J | H | X | B | M | W | V | ? |

Level 3
-------
| 左手 | 左手 | 左手 | 左手 | 左手 | 右手 | 右手 | 右手 | 右手 | 右手 |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Insert | " | Up | ] | F2 | F11 | [ | ) | ( | ~ |
| Home | Left | Down | Right | END | Delete | Return | Tab | Escape | \| |
| ' | { | - | _ | } | Backspace | = | + | ` | \ |

(Qwerty 版本的 Level1, 2 为相应的 Qwerty， 第三布局为 Neo的第三布局)


Number Row
----------

| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| ! | @ | # | $ | % | ^ | & | * | Caps_Lock |
| space | : | ! | PgDn | PgUp | Compose_Key | 2 | 0 | 1 |

and the third level may change sometimes.
