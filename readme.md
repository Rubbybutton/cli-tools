# 那些cli tools

以下是我曾用(有些现在也在用)的cli工具们，以下列出了我认为强大的cli工具(不是系统自带的(如ls、gunzip)或是特别领域相关的(如git、docker、clash))。  
顺便提一下我用的是fish shell，自定义函数功能强大。搭配下列cli工具再好不过。原创不易，以后会持续更新。
## 下载类

| 名称                                                  | 功能简介                                                                                                                                                                                                                                                                                      |
| :------| :------|
| [you-get](https://github.com/soimort/you-get)         | 视频下载器，可应用的网站众多。 像对bilibili可以下载整部免费的番剧哦                                                                                                                                                                                                                           |
| [youtube-dl](https://github.com/ytdl-org/youtube-dl/) | 功能强大的视频下载器，可应用的网站众多。<br>同上者一样star很多。                                                                                                                                                                                                                              |
| [aria2](https://github.com/aria2/aria2)               | 很著名，也很强大的bt，磁力下载器。但是由于原装需要自己配置种子服务器才能提速，比较复杂。个人下载的话用Deluge(CLI和GUI都有)感觉更好                                                                                                                                                            |
| [tget](https://www.npmjs.com/package/tget)            | 也是一个种子和磁力下载器，用nodejs写成。                                                                                                                                                                                                                                                      |
| [Deluge](https://www.deluge-torrent.org/)             | 配置好的bt，磁力下载器。国内用速度也比较快。GUI 和 CLI 都有。                                                                                                                                                                                                                                 |
| [gallery-dl](https://www.deluge-torrent.org/)         | 强烈推荐。图片下载器。个人用于下载pixiv图片。支持代理和用户验证。自定义功能强大(通过修改配置文件)。可以快速下载pixiv某个艺术家的全部公开作品或从文件读取url下载。<br> 并且更重要的是，由于可以用户登陆验证，可以直接下载全部自己收藏的图片(即传入这个参数:https://www.pixiv.net/bookmark.php) |
| [music-dl](https://github.com/0xHJK/music-dl)         | 从网易云音乐、QQ音乐、酷狗音乐、百度音乐、虾米音乐、咪咕音乐等搜索和下载歌曲                                                                                                                                                                                                                  |
| [mps-youtube](https://github.com/mps-youtube/mps-youtube) | 从you-tube上下载音乐                                                                                                                                                                                                                                                                          |

## 文件管理器

| 名称                                       | 功能简介                                                                                      |
| :------| :------|
| [ranger](https://github.com/ranger/ranger) | 很出名的一个终端文件管理器，快速跳转，终端**预览**(图片，word文档，excel文档)等等，功能很强大 |

## 翻译工具

| 名称                                                       | 功能简介                                                                                                                            |
| :------| :------|
| [ydict](https://github.com/TimothyYe/ydict)                | 极客的有道词典，只可以中英文互译，发音可以发音、收藏、回放单词。                                                                    |
| [translate-shell](https://www.soimort.org/translate-shell) | 默认终端google翻译(同时也可以bing和有道),同样也可以发音，支持多种语言的翻译，以及对文件和网页的翻译。两者各有千秋。界面没上者好看。 |

## 搜索类(不同于终端浏览器)

| 名称                                        | 功能简介     |
| :------| :------|
| [googler](https://github.com/jarun/googler) | 终端谷歌搜索 |
| [ddgr](https://github.com/jarun/ddgr)       | 终端DuckDuckGo搜索 |

## 聊天客户端(不含IRC)

| 名称                                                      | 功能简介                               |
| :------| :------|
| [rainbowstream](https://github.com/orakaro/rainbowstream) | 用python写的twitter终端客户端,美丽高效 |
| [RTV](https://github.com/michael-lazar/rtv)               | 终端的reddit客户端                           |

## 终端文本编辑器(不含vim,emacs)

| 名称                                        | 功能简介                                                            |
| :------| :------|
| [micro](https://github.com/zyedidia/micro)  | 终端文本编辑器，使用习惯(快捷键等)和现代GUI编辑器相差无几，支持插件 |
| [slap](https://github.com/slap-editor/slap) | 终端仿sublime的文本编辑器                                           |

## 文件查找工具

| 名称                                                | 功能简介                                                                                                                 |
| :------| :------|
| [fd](https://github.com/sharkdp/fd)                 | 「 fd是一种简单ㄡ快速和用户友好的`find`替代方案.」                                                                       |
| [fzf](https://github.com/junegunn/fzf)              | 命令行模糊搜索工具，可以与tab键自动补全结合。如果用fish shell还需要[专门的自定义函数](https://github.com/jethrokuan/fzf) |
| [ag](https://github.com/ggreer/the_silver_searcher) | 快速聪明的文件搜索工具                                                                                                   |

## 传输文件类

| 名称                                         | 功能简介                                         |
| :------| :------|
| [ffsend](https://github.com/timvisee/ffsend) | firefox send 的cli命令行工具，用起来效果不错。   |
| [transfer.sh](https://transfer.sh/)          | 传输文件用一条命令搞定。上传文件最大容量可以达到10GB |

## 图像处理类

| 名称                                                     | 功能简介                                                                 |
| :------| :------|
| [korkut](https://github.com/oguzhaninan/korkut)          | 快速处理图像，多种功能，并且有良好的用户交互界面                         |
| [imagemin-cli](https://github.com/imagemin/imagemin-cli) | nodejs做的图片压缩工具，支持目录文件压缩、文件格式转化等等，同时支持插件 |

## 终端录制

| 名称                                                  | 功能简介                                                             |
| :------| :------|
| [asciinema](https://github.com/asciinema/asciinema)   | 终端屏幕录制，还有自己专门的网站提供时评上传(还提供视频博客嵌入功能) |
| [svg-term](https://github.com/marionebl/svg-term-cli) | 把asciinema录制的视频转化为svg格式                                  |

## 音乐、视频类别

| 名称                                                  | 功能简介                                                            |
| :------| :------|
| [musicbox](https://github.com/darknessomi/musicbox)   | 终端网易云音乐，美丽丝滑                                            |
| [mpv](https://mpv.io/installation/)                   | 音乐播放为终端播放，视频播放是GUI的。支持流式传输。个人喜欢其界面。 |
| [curseradio](https://github.com/chronitis/curseradio) | 命令行电台播放                                                          |

## 系统性能检测类

| 名称                                               | 功能简介                                                   |
| :------| :------|
| [s-tui](https://amanusk.github.io/s-tui/)          | 终端图形化的cpu查看器，可以显示cpu的温度，频率，使用率等等 |
| [neofetch](https://github.com/dylanaraps/neofetch) | 快速，美观的系统信息获取器                                 |
| [htop](https://github.com/hishamhm/htop)           | 交互式进程查看器                                           |
| [gtop](https://github.com/aksakalli/gtop)          | cpu，内存，磁盘，进程的终端面板                                |

## 与操作系统关联类

| 名称                                                 | 功能简介                                                                                                                                                        |
| :------| :------|
| [snap](https://snapcraft.io/)                        | [snapcraft(snap应用商店)](https://snapcraft.io/) ; 解决跨不同linux平台app难题,不过个人感觉尚且不是特别好                                                        |
| [debtap](https://aur.archlinux.org/packages/debtap/) | 适用于arch linux ; 把deb包转化为pkg,用pacman -U FILE 来本地安装 <br> 在转化过程中需要输入许可证(自己用的话随便舔就行) 。个人亲自用此安装了百度网盘官网linux版。 |
| [gdebi](https://github.com/linuxmint/gdebi)          | 适用于ubuntu及其衍生版 ； 相对dpkg可以更好地检测兼容性和自动安装依赖。                                                                                          |

## 其他工具

| 名称                                                | 功能简介                                                                            |
| :------| :------|
| [wtf](https://linux.die.net/man/6/wtf)              | 英文缩写翻译。ubuntu安装`sudo apt-get install bsdgames`;macos安装`brew install wtf` |
| [pm2](https://github.com/Unitech/pm2)               | nodejs做的后台进程守护工具                                                          |
| [tldr](https://github.com/tldr-pages/tldr)          | 一个社区驱动型的简洁的(给出命令实例)man手册                                         |
| [mycli](https://github.com/dbcli/mycli)             | python写的美丽的mysql客户端                                                         |
| [js2image](https://github.com/xinyu198736/js2image) | 把js代码压缩成代码树，压缩后的代码仍然可以运行                                      |
| [cloc](https://github.com/AlDanial/cloc)            | 计算代码行数，空格数，注释数等等                                                    |
| [lolcat](https://github.com/busyloop/lolcat)        | 终端渐变彩色输出                                                                    |
| [fx](https://github.com/antonmedv/fx)               | 终端json文件交互式查看(支持鼠标操作)                                                |
| [httpie](https://github.com/jakubroztocil/httpie)   | 官方说法:HTTPie是一个让你微笑的http客户端。                                                   |

## 与curl交互的网站

| 命令                                                                               | 介绍                     |
| :------| :------|
| `curl cip.cc`                                                                      | 查看ip,服务器商等信息    |
| `curl wttr.in`或`curl wttr.in/<此处填你的城市名称，如beijing>`                     | 查看天气预报，返回很漂亮 |
| `命令在下方` | 网速检测 |

网速检测:`curl -s https://raw.githubusercontent.com/sivel/speedtest-cli/master/speedtest.py | python -`


---

未完待续

