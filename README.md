# 字节代购 - 使用 SS 客户端网上冲浪
在已经有服务端代理的情况下，使用不同的终端，进行科学网上冲浪

## iPhone/iPad 篇
### 知识补齐 - 我们需要什么
### 安装使用步骤

## 安卓篇
### 知识补齐 - 我们需要什么
### 安装使用步骤

## Mac 篇
### 知识补齐 - 我们需要什么
#### shadowsocks Mac 版客户端
shadowsocks 客户端的作用是连接代理，是必要的，shadowsocks 本质是一种代理服务（就类似网络代购），它的客户端在不同的设备上有各种实现形式，我们这里需要它的 Mac 版

去 [这里](https://github.com/shadowsocks/ShadowsocksX-NG/releases/) 下载最新的 shadowsocks Mac 客户端，选择 Latest release 里的 Assets 中的 ShadowsocksX-NG.x.y.z.zip 下载即可，注意 x.y.z 是版本号，诸如1.9.4，会随着官方更新产生变化升级

<p align="center">
  <img alt="SS Mac Client" src="https://raw.githubusercontent.com/YoungLeeNENU/scientific-internet-surfing/master/assets/ss-mac-download.png">
</p>

### 安装使用步骤

下载 Shadowsocks 之后，解压安装到 Mac 上，最好放在扩展坞里，方便后面快速找到

<p align="center">
  <img alt="SS Mac Client" src="https://raw.githubusercontent.com/YoungLeeNENU/scientific-internet-surfing/master/assets/Shadowsocks_in_docker.png">
</p>

打开 Shadowsocks 之后，Mac 的置顶状态和工具栏里会出现这样一个纸飞机图标的东西，点击它，这个就是 Shadowsocks：

<p align="center">
  <img alt="SS Mac Client" src="https://raw.githubusercontent.com/YoungLeeNENU/scientific-internet-surfing/master/assets/Shaodowsocks_open.png">
</p>

然后这边我们导入配置，选导入服务器 url:

<p align="center">
  <img alt="SS Mac Client" src="https://raw.githubusercontent.com/YoungLeeNENU/scientific-internet-surfing/master/assets/Shadowsocks_import_url_1.png">
</p>

把配置粘贴进去（配置具体私信我，这里打码了）:

<p align="center">
  <img alt="SS Mac Client" src="https://raw.githubusercontent.com/YoungLeeNENU/scientific-internet-surfing/master/assets/Shadowsocks_import_2.png">
</p>

然后服务器这里就会出现你刚才导入的配置

<p align="center">
  <img alt="SS Mac Client" src="https://raw.githubusercontent.com/YoungLeeNENU/scientific-internet-surfing/master/assets/Shadowsocks_import_3.png">
</p>

这里还没完，最后一步需要配置 kcptun，用来加速网络，选择服务器设置

<p align="center">
  <img alt="SS Mac Client" src="https://raw.githubusercontent.com/YoungLeeNENU/scientific-internet-surfing/master/assets/Shadowsocks_import_4.png">
</p>

然后在插件这里，写 kcptun

<p align="center">
  <img alt="SS Mac Client" src="https://raw.githubusercontent.com/YoungLeeNENU/scientific-internet-surfing/master/assets/Shadowsocks_import_4.png">
</p>

然后打开插件目录

<p align="center">
  <img alt="SS Mac Client" src="https://raw.githubusercontent.com/YoungLeeNENU/scientific-internet-surfing/master/assets/Shadowsocks_import_5.png">
</p>

找到 kcptun，

<p align="center">
  <img alt="SS Mac Client" src="https://raw.githubusercontent.com/YoungLeeNENU/scientific-internet-surfing/master/assets/Shadowsocks_import_6.png">
</p>

然后把这个文件复制到 ~/Library/Application Support/ShadowsocksX-NG/plugins/ 文件夹下，我知道这个可能看不懂，这个文件夹怎么找到呢？

<p align="center">
  <img alt="SS Mac Client" src="https://raw.githubusercontent.com/YoungLeeNENU/scientific-internet-surfing/master/assets/Shadowsocks_import_7.png">
</p>

在访达中选择前往，然后前往文件夹，按照图片填写路径，进入这个文件夹

<p align="center">
  <img alt="SS Mac Client" src="https://raw.githubusercontent.com/YoungLeeNENU/scientific-internet-surfing/master/assets/Shadowsocks_import_8.png">
</p>

这个文件夹下如果没有名字叫 plugins 的文件夹的话，就自己创建一个

<p align="center">
  <img alt="SS Mac Client" src="https://raw.githubusercontent.com/YoungLeeNENU/scientific-internet-surfing/master/assets/Shadowsocks_import_9.png">
</p>

有的话，可以直接进入，或者创建完进入这个文件夹，然后把刚才找到的 kcptun 文件复制到这里即可，这几步大概率会需要你进行授权，正常填写密码授权即可

<p align="center">
  <img alt="SS Mac Client" src="https://raw.githubusercontent.com/YoungLeeNENU/scientific-internet-surfing/master/assets/Shadowsocks_import_10.png">
</p>

然后在服务器设置里确认刚才的设置

<p align="center">
  <img alt="SS Mac Client" src="https://raw.githubusercontent.com/YoungLeeNENU/scientific-internet-surfing/master/assets/Shadowsocks_complete_1.png">
</p>

然后打开 Shadowsocks 选择自动模式或者全剧模式，以及刚才的服务器，就可以进行科学上网了

<p align="center">
  <img alt="SS Mac Client" src="https://raw.githubusercontent.com/YoungLeeNENU/scientific-internet-surfing/master/assets/Shadowsocks_complete_2.png">
</p>

<p align="center">
  <img alt="SS Mac Client" src="https://raw.githubusercontent.com/YoungLeeNENU/scientific-internet-surfing/master/assets/Done.png">
</p>

## Windows 篇
### 知识补齐 - 我们需要什么
### 安装使用步骤