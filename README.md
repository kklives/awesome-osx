# awesome-osx

### 简介

This scripts will install  `oh-my-zsh` , `homebrew` , `vim` and other plugins

#### 安装教程

```bash
##下载脚本
curl -L https://raw.githubusercontent.com/kklives/awesome-osx/master/zsh.sh -o ~/zsh.sh
##使用代理
export http_proxy=http://127.0.0.1:1087;export https_proxy=http://127.0.0.1:1087; export ALL_PROXY=socks5://127.0.0.1:1080
##需多次运行⤵️
##需多次运行⤵️
##需多次运行⤵️
bash ~/zsh.sh && source ${ZDOTDIR:-$HOME}/.zshrc
```

#### brew cli 清单

| 名称                                                      | 介绍                                                         | 安装 |
| --------------------------------------------------------- | ------------------------------------------------------------ | :--: |
| ack                                                       | ack是为程序员设计的grep的替代产品                            |  ✔   |
| [bat](https://github.com/sharkdp/bat)                     | 具有语法高亮和Git集成的cat                                   |  ✔   |
| [fd](https://github.com/chinanf-boy/fd-zh)                | *fd*是一种简单又快速和用户友好的 find 替代方案.              |  ✔   |
| [htop](https://github.com/hishamhm/htop)                  | Htop是一款运行于Linux系统监控与进程管理软件，用于取代Unix下传统的top |  ✔   |
| [wget](https://zh.wikipedia.org/wiki/Wget)                | 是一个在网络上进行下载的简单而强大的自由软件                 |  ✔   |
| neofetch                                                  | A fast, highly customizable system info script               |      |
| [nmap](https://zh.wikipedia.org/wiki/Nmap)                | 用于网络发现和安全审计的网络安全工具                         |  ✔   |
| [p7zip](https://zh.wikipedia.org/wiki/7-Zip#p7zip)        | 7-Zip是一个开放源码的数据压缩程序                            |  ✔   |
| [pandoc](https://zh.wikipedia.org/wiki/Pandoc)            | 标记语言转换工具，可实现不同标记语言间的格式转换             |  ✔   |
| ssh-copy-id                                               | SSH无密码登录                                                |  ✔   |
| html2text                                                 | 将html文件转换成text文件                                     |  ✔   |
| [wrk](https://github.com/wg/wrk)                          | wrk是一种现代HTTP基准测试工具                                |  ✔   |
| [tree](https://www.runoob.com/linux/linux-comm-tree.html) | Linux tree命令用于以树状图列出目录的内容。                   |  ✔   |
| [telnet](https://zh.wikipedia.org/wiki/Telnet)            | Telnet是一种应用层协议，使用于互联网及局域网中，使用虚拟终端的形式，提供双向、以文字字符串为主的命令行接口交互功能 |  ✔   |
| minikube                                                  | minikube在macOS，Linux和Windows上实现了本地Kubernetes集群。 minikube的主要目标是成为本地Kubernetes应用程序开发的最佳工具，并支持所有合适的Kubernetes功能。 |      |
| kubernetes-cli                                            | Kubectl                                                      |      |
| maven                                                     |                                                              |      |
| mysql@5.7                                                 |                                                              |      |
| redis                                                     |                                                              |      |
| jenv                                                      |                                                              |      |

### brew cask 清单

| 名称                                                         | 介绍                                                         | 安装 | 安装方法                                           |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ---- | -------------------------------------------------- |
| [iterm2](https://iterm2.com/)                                | iTerm2是Terminal的替代品                                     | ✔    |                                                    |
| open-in-[code](https://github.com/sozercan/OpenInCode)       | Finder工具栏应用程序可在Visual Studio Code中打开当前文件夹   | ✔    |                                                    |
| [findergo](https://github.com/onmyway133/FinderGo)           | macOS应用程序和Finder Sync Extension可从Finder打开Terminal，iTerm，Hyper | ✔    |                                                    |
| [visual-studio-code](https://code.visualstudio.com/)         |                                                              | ✔    |                                                    |
| google-chrome                                                |                                                              | ✔    |                                                    |
| typora                                                       | Typora 是一款**支持实时预览的 Markdown 文本编辑器**。它有 OS X、Windows、Linux 三个平台的版本，并且由于仍在测试中，是**完全免费**的。[Typora 完全使用详解](https://sspai.com/post/54912) | ✔    |                                                    |
| upic                                                         | 图床，作为 typora 的依赖                                     | ✔    |                                                    |
| postman                                                      |                                                              | ✔    |                                                    |
| docker                                                       |                                                              |      |                                                    |
| [switchhosts](https://github.com/oldj/SwitchHosts/blob/master/README_cn.md) | 这是一个用于快速切换 hosts 文件的小程序，基于 Electron 开发，同时使用了 React、Ant Design 以及 CodeMirror 等框架/库。 | ✔    |                                                    |
| virtualbox                                                   |                                                              |      |                                                    |
| [iina](https://github.com/iina/iina)                         | IINA是适用于macOS 的**现代**视频播放器。                     | ✔    |                                                    |
| baidunetdisk                                                 |                                                              |      | brew                                               |
| thunder                                                      |                                                              |      | brew                                               |
| sougouinput                                                  |                                                              |      | brew                                               |
| another-redis-desktop-manager                                |                                                              |      | brew                                               |
| intellij-idea                                                |                                                              |      | [安装地址](http://10.0.7.199:9199/mac-install.zip) |

### other software

| 名称                | 介绍                                                         | 安装                                               |
| ------------------- | ------------------------------------------------------------ | -------------------------------------------------- |
| Alfred              | [Alfred](http://alfredapp.com/) 是一款 Mac OS X 的快速启动类应用，可以快速启动应用及系统关联功能，激活可拓展的功能，通过与互联网的高度融合实现畅快淋漓的浏览体验等。 | [安装地址](http://10.0.7.199:9199/mac-install.zip) |
| BetterZip           | 压缩解压                                                     | [安装地址](http://10.0.7.199:9199/mac-install.zip) |
| Bartender           | MenuBar 管理                                                 | [安装地址](http://10.0.7.199:9199/mac-install.zip) |
| CleanMyMac          | 清理、卸载、维护                                             | [安装地址](http://10.0.7.199:9199/mac-install.zip) |
| Dash                | 开发文档管理                                                 | [安装地址](http://10.0.7.199:9199/mac-install.zip) |
| PDF Expert          | pdf 阅读，修改                                               | [安装地址](http://10.0.7.199:9199/mac-install.zip) |
| office              |                                                              | [安装地址](http://10.0.7.199:9199/mac-install.zip) |
| Xmind               |                                                              | [安装地址](http://10.0.7.199:9199/mac-install.zip) |
| Tuxera Disk Manager | NTFS磁盘读写                                                 | [安装地址](http://10.0.7.199:9199/mac-install.zip) |
| Shimo               | VPN                                                          | [安装地址](http://10.0.7.199:9199/mac-install.zip) |
| Navicat             |                                                              | [安装地址](http://10.0.7.199:9199/mac-install.zip) |
| 自动切换输入法      |                                                              | Applestore                                         |
| 超级右键            |                                                              | Applestore                                         |

#### HomeBrew常用命令

```bash
$ brew --help #简洁命令帮助
$ man brew #完整命令帮助
$ brew install git #安装软件包(这里是示例安装的Git版本控制)
$ brew remove git #卸载软件包
$ brew uninstall git #卸载软件包
$ brew search git #搜索软件包
$ brew list #显示已经安装的所有软件包
$ brew update #同步远程最新更新情况，对本机已经安装并有更新的软件用*标明
$ brew outdated #查看已安装的哪些软件包需要更新
$ brew upgrade  # 更新所有的包
$ brew upgrade git #更新单个软件包
$ brew info # 显示安装了包数量，文件数量，和总占用空间
$ brew info git #查看软件包信息
$ brew home git #访问软件包官方站
$ brew cleanup #清理所有已安装软件包的历史老版本
$ brew cleanup git #清理单个已安装软件包的历史版本
$ brew pin $FORMULA      # 锁定某个包
$ brew unpin $FORMULA    # 取消锁定
$ brew deps --installed --tree # 查看已安装的包的依赖，树形显示
$ brew service start(stop、restart) mysql@5.7 #启动，停止，重启 服务
```



#### Alfred

[使用详解](https://sspai.com/post/27900)

[Alfred上可提高工作效率的Workflow推荐](https://www.cnblogs.com/xindoo/p/11380072.html)

[alfred 插件]( https://github.com/learn-anything/alfred-workflows)

### oh-my-zsh plugins

- z
- kubectl
- history
- zsh-syntax-highlighting
- themes
- zsh_reload
- extract
- command-not-found
- colored-man-pages
- zsh-autosuggestions

### OSX系统介绍

##### 1. 基础快捷键

- 文件改名 return(回车)

- 文件预览 space(空格)

- 截图 

  - 全屏

    - 截图保存到桌面

      Command(⌘) + Shift(⇧) + 4

    - 截图保存到剪贴板

      Command(⌘) + Shift(⇧) + Control(⌃) + 3

  - 选择区域

    - 截图保存到桌面

      Command(⌘) + Shift(⇧) + 4

    - 截图保存到剪贴板

      Command(⌘) + Shift(⇧) + Control(⌃) + 4

- 全选/复制/粘贴/剪切 

  - Command(⌘) + a
  - Command(⌘) + c
  - Command(⌘) + v
  - Command(⌘) + Option(⌥) + v

- 切换应用(应用最小化时) 

  - Command(⌘) + 制表符（Tab键）
  - Command(⌘) + 制表符(Tab键)切换至该应用，先松开制表符(Tab键)，接着按住 Option(⌥) ，然后松开Command(⌘)

- 关闭当前窗口（或者标签页）如 chrome 标签页、idea 标签页

  - Command(⌘) + w 

- 退出当前应用 

  - Command(⌘) + q

- 系统设置 

  - Command(⌘) + ,

- 文本编辑

  - 至行首 Control(⌃) + a
  - 至行尾 Control(⌃) + e
  - Vim 模式下  Shift(⇧) + a 至行尾，Shift(⇧)+ i 至行首

- Chrome 常用快捷键

  - Command(⌘) + r 刷新页面
  - Command(⌘) + Shift(⇧) + r  强制刷新页面(去缓存刷新)

- Finder(访达) 常用快捷键

  - Command(⌘) + Shift(⇧) + G 前往某个文件夹
  - Command(⌘) + K 连接某个服务器 
    - 例如  
      - afp://10.0.7.199    #连接群晖文件服务器
      - smb://10.0.7.199  #连接群晖文件服务器
      - ftp://x.x.x.x    连接某 ftp 服务器
      - vnc://x.x.x.x 连接某vnc远程桌面

##### 2.系统配置

1. 系统偏好配置 
   - 触摸板相关
     1.  系统偏好设置-触控板 -轻点来点按。
     2.  系统偏好设置-辅助功能-鼠标与触控板-触控板选项-启用拖移-三指拖移。
   - 鼠标相关 
     - 苹果菜单 >“系统偏好设置”，然后点按“鼠标”  ✘滚动方向:自然 
   - 程序坞 
     - 苹果菜单 >“系统偏好设置”，然后点按“程序坞”。 
     - 置于屏幕上的位置，左 
     - ☑️将窗口最小化为应用程序图标 
     - ✘在程序坞中显示最近使用的应用程序
   - 安全性与隐私
     -  请选取苹果菜单 >“系统偏好设置”，点按“安全性与隐私”
     - 然后点按“通用 ”，允许从以下位置下载的应用：所有来源 终端中输入 `sudo spctl --master-disable` 
   - 触发角 
     - 请选取苹果菜单 >“系统偏好设置”，点按“桌面与屏幕保护程序”，然后点按 “屏幕保护程序”，触发角。
   -  更改键盘设置 
     - 请选取苹果菜单 >“系统偏好设置”，点按“键盘”，然后点按“键盘”。 
     - ☑️将 F1、F2 等键用作标准功能键 
     - 修改修饰键 针对大写锁定键、Control、Option 和 Command 修饰键更改默认行为。 
   - 更改 “用户与群组”中的“客人用户”偏好设置 
     - ✘ 允许客人登录到这台电脑
   -  共享 
     - ☑️屏幕共享 设置所有用户
     - ☑️远程登录 设置所有用户
2. Finder 配置 
   1. 通用-开启新访达窗口时打开-用户目录 
   2. 边栏-✘最近使用 ☑️用户目录 
   3. 高级-显示所有文件扩展名


#### 参考文献

1.  [zsh介绍-维基百科，自由的百科全书](https://baike.baidu.com/item/Zsh)
2.  [oh-my-zsh介绍](https://ohmyz.sh/)
3.  [Homebrew-维基百科，自由的百科全书](https://zh.wikipedia.org/wiki/Homebrew)
4.  [Homebrew更换国内源](https://www.jianshu.com/p/9592826c254b)
5.  [Homebrew 镜像](https://developer.aliyun.com/mirror/homebrew) 
6.  [iterm2 快捷键大全 Mac item2常用快捷键](https://www.jianshu.com/p/68e1c92564dc)
7.  [构建开发环境-生成/添加SSH公钥](https://gitee.com/help/articles/4181#article-header0)
8.  [打造 Mac 下高颜值好用的终端环境](https://blog.biezhi.me/2018/11/build-a-beautiful-mac-terminal-environment.html)
9.  [打不开 xxx，因为它来自身份不明的开发者” “ xxx已损坏，你应该将它移到废纸篓”的解决方法](https://blog.csdn.net/weixin_41470864/article/details/90062840)
10.  [custom-alfred-iterm-scripts](https://github.com/vitorgalvao/custom-alfred-iterm-scripts)

