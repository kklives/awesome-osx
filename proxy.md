### 代理地址(http/socks5自适应)

- http(s)
  - http://proxy.fangshi.com:1080
- socks5
  - socks5://proxy.fangshi.com:1080

### 设置代理步骤

##### 1. 在操作系统中设置全局代理

- 对于Windows 系统
  - 首先，按下键盘的win键，就是 windows 图标。然后再开始菜单中单击“设置”。
  
  - 在出现的设置面板中，单击“网络和Internet”。
  
  - 单击“代理”。你就会看到右侧有关代理的详细设置。
  
  - 打开使用代理服务器开关，在下方地址中填入 http://proxy.fangshi.com ，端口中填入 1080 保存后退出。
  
    ![FTyU4KCE7jx6fOm](https://i.loli.net/2020/11/19/FTyU4KCE7jx6fOm.png)
- 对于 MACOSX 系统
  - 打开系统偏好设置，选择 网络。
  
  - 点击 高级... ，在出现的选项卡中选择代理，勾选 socks 代理
  
  - 在 socks 代理服务器一栏中填写 proxy.fangshi.com : 1080 ，保存后退出。
  
    ![iZX2s1ADyOem5g3](https://i.loli.net/2020/11/19/iZX2s1ADyOem5g3.jpg)
- 经过以上设置，系统已经可以使用代理服务器访问国外网址了，但**此时设置的代理是针对整个操作系统全局使用代理的，意味着此时当你访问国内网站时也会使用国外的 ip 地址，导致访问国内网站速度会比较慢**，所以此时我们要借助一款浏览器插件来自动帮我们判断当我们访问一个网站时是否需要使用代理。

##### 2. Chrome浏览器中使用代理

1. Chrome应用商店中安装 [Proxy SwitchyOmega](https://chrome.google.com/webstore/detail/proxy-switchyomega/padekgcemlokbadohgkifijomclgjgif?hl=zh-CN)，如果你不能访问chrome应用商店，此时需要检查第一步的配置。

2. 点击安装好的插件，选择选项-->设定-->导入配置文件(包含gfw地址列表)  [下载地址](http://10.0.7.199:9199/SwitchyOmega/OmegaOptions.bak)

3. 选择 情景模式-->代理模式-->代理服务器 添加代理协议，socks5 ，地址 proxy.fangshi.com:1080 ，保存后退出

4. 根据不同场景，选择情景模式为 
   - 自动切换 （根据你访问的网站自动判断是否需要使用代理，日常情况建议选择此项）
   - 代理模式（访问所有网站都使用代理）
   - 直接连接 （访问所有网站都不使用代理）
##### 3. 取消操作系统的全局代理设置

经过上述步骤，我们已经可以在 Chrome 浏览器中使用代理访问国外网站，接下来为避免出现操作系统访问其他应用程序时出现不能上网的问题，需要按照步骤 1 取消刚才为操作系统设置的全局代理。（步骤 1 的存在仅为了你能访问 Chrome 应用商店下载插件）



### 在命令行中使用全局代理

某些场景下，你可能需要在命令行中访问国外网站，例如需要 curl 命令下载 GitHub 中的源码 ,以下代码为 Linux 环境下参考命令

```bash
#在当前会话中全局使用http(s)代理
export http_proxy=http://proxy.fangshi.com:1080;export https_proxy=http://proxy.fangshi.com:1080;
#在当前会话中全局使用 socks5代理
export ALL_PROXY=socks5://proxy.fangshi.com:1080
#当你不需要代理时可关闭当前会话窗口，或使用以下命令取消代理
unset http_proxy https_proxy ALL_PROXY
```

   可以在自己的`.bashrc` 或者`.zshrc` 中加入`alias` 实现快速切换

```bash
#vim ~/.zshrc
alias proxy='export http_proxy=http://proxy.fangshi.com:1080;export https_proxy=http://proxy.fangshi.com:1080;'
alias socks5_proxy='export ALL_PROXY=socks5://proxy.fangshi.com:1080'
alias unproxy="unset http_proxy https_proxy ALL_PROXY"
#wq
#重新载入配置
source ~/.zshrc 
# 设置完成后可使用 `curl cip.cc` 检查当前ip地址以确认配置是否生效
$ curl cip.cc
IP	: 104.245.14.31
地址	: 美国  加利福尼亚州  洛杉矶
运营商	: xtom.com

数据二	: 美国 | 加利福尼亚州洛杉矶xTOM

数据三	: 美国加利福尼亚

URL	: http://www.cip.cc/104.245.14.31
```

### 其他场景中使用代理

- 容器环境下需要拉取 gcr.io 或 quay.io 的镜像时，需要为 *Docker Engine* 配置代理，详情参见 [Configure Docker to use a proxy server](https://docs.docker.com/network/proxy/)
- 应用软件如 Telegram 等，需要通过代理访问时，找到代理服务器配置填入 http 或 socks5 代理地址即可。