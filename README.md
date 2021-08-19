**English** | [中文](https://p3terx.com/archives/build-openwrt-with-github-actions.html)

# Actions-OpenWrt

[![LICENSE](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square&label=LICENSE)](https://github.com/P3TERX/Actions-OpenWrt/blob/master/LICENSE)
![GitHub Stars](https://img.shields.io/github/stars/P3TERX/Actions-OpenWrt.svg?style=flat-square&label=Stars&logo=github)
![GitHub Forks](https://img.shields.io/github/forks/P3TERX/Actions-OpenWrt.svg?style=flat-square&label=Forks&logo=github)

A template for building OpenWrt with GitHub Actions

## Usage

- Click the [Use this template](https://github.com/P3TERX/Actions-OpenWrt/generate) button to create a new repository.
- Generate `.config` files using [Lean's OpenWrt](https://github.com/coolsnowwolf/lede) source code. ( You can change it through environment variables in the workflow file. )
- Push `.config` file to the GitHub repository.
- Select `Build OpenWrt` on the Actions page.
- Click the `Run workflow` button.
- When the build is complete, click the `Artifacts` button in the upper right corner of the Actions page to download the binaries.
# Actions-OpenWrt

[![LICENSE](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square&label=LICENSE)](https://github.com/P3TERX/Actions-OpenWrt/blob/master/LICENSE)
![GitHub Stars](https://img.shields.io/github/stars/P3TERX/Actions-OpenWrt.svg?style=flat-square&label=Stars&logo=github)
![GitHub Forks](https://img.shields.io/github/forks/P3TERX/Actions-OpenWrt.svg?style=flat-square&label=Forks&logo=github)

Build OpenWrt using GitHub Actions

[Read the details in my blog (in Chinese) | 中文教程](https://p3terx.com/archives/build-openwrt-with-github-actions.html)
 
 软件不定期同步大神库更新，适合一键下载到package目录下，用于openwrt编译

两位L大库里都删除了某软件，作为搬运工，passwall的依赖一并找齐了

passwall依赖库下载链接，注意！在openwrt或者lean源码下编译passwall，要下载此依赖库
1、 lede/package$下运行 或者openwrt/package$下运行
 
 git clone https://github.com/kenzok8/openwrt-packages.git

2、 或者添加下面代码到 openwrt 或lede源码根目录feeds.conf.
 
 src-git kenzo https://github.com/kenzok8/openwrt-packages

3、 passwall的依赖
 
 src-git small https://github.com/kenzok8/small

openwrt 固件编译自定义主题与软件
luci-app-openclash ------------------openclash图形

luci-app-advancedsetting ------------------系统高级设置

luci-theme-ifit ------------------透明主题（适配18.06修复主机名错误）

luci-theme-atmaterial ------------------atmaterial 三合一主题（适配18.06）

luci-app-aliddns ------------------阿里云ddns

luci-app-eqos ------------------依IP地址限速

luci-app-gost ------------------隐蔽的https代理

luci-app-adguardhome ------------------去广告

luci-a# Actions-OpenWrt

[![LICENSE](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square&label=LICENSE)](https://github.com/P3TERX/Actions-OpenWrt/blob/master/LICENSE)
![GitHub Stars](https://img.shields.io/github/stars/P3TERX/Actions-OpenWrt.svg?style=flat-square&label=Stars&logo=github)
![GitHub Forks](https://img.shields.io/github/forks/P3TERX/Actions-OpenWrt.svg?style=flat-square&label=Forks&logo=github)

Build OpenWrt using GitHub Actions

[Read the details in my blog (in Chinese) | 中文教程](https://p3terx.com/archives/build-openwrt-with-github-actions.html)
 
 软件不定期同步大神库更新，适合一键下载到package目录下，用于openwrt编译

两位L大库里都删除了某软件，作为搬运工，passwall的依赖一并找齐了

passwall依赖库下载链接，注意！在openwrt或者lean源码下编译passwall，要下载此依赖库
1、 lede/package$下运行 或者openwrt/package$下运行
 
 git clone https://github.com/kenzok8/openwrt-packages.git

2、 或者添加下面代码到 openwrt 或lede源码根目录feeds.conf.
 
 src-git kenzo https://github.com/kenzok8/openwrt-packages

3、 passwall的依赖
 
 src-git small https://github.com/kenzok8/small

openwrt 固件编译自定义主题与软件
luci-app-openclash ------------------openclash图形

luci-app-advancedsetting ------------------系统高级设置

luci-theme-ifit ------------------透明主题（适配18.06修复主机名错误）

luci-theme-atmaterial ------------------atmaterial 三合一主题（适配18.06）

luci-app-aliddns ------------------阿里云ddns

luci-app-eqos ------------------依IP地址限速

luci-app-gost ------------------隐蔽的https代理

luci-app-adguardhome ------------------去广告

luci-app-smartdns ------------------smartdns防污染

luci-app-passwall ------------------Lienol大神

luci-theme-argon_new ------------------二合蓝 紫主题

luci-app-ssr-plus ------------------Lean大神

luci-theme-opentomcat ------------------修复主机名错误（适配18.06）

luci-theme-opentomato ------------------修复主机名错误（适配18.06）

pp-smartdns ------------------smartdns防污染

luci-app-passwall ------------------Lienol大神

luci-theme-argon_new ------------------二合蓝 紫主题

luci-app-ssr-plus ------------------Lean大神

luci-theme-opentomcat ------------------修复主机名错误（适配18.06）

luci-theme-opentomato ------------------修复主机名错误（适配18.06）

