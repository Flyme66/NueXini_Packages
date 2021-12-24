# Mt-wifi

------



## 1.如何使用Mt-wifi？ / How to use Mt-wifi?
```bash
cd lede
sed -i '$a src-git NueXini_Packages https://github.com/NueXini/NueXini_Packages.git' feeds.conf.default
./scripts/feeds update -a && ./scripts/feeds install -a
```
## 2.使用非lede源码编译时，部分插件显示英文 修复方法
```bash
#cd feeds/NueXini_Packages
curl -s https://raw.githubusercontent.com/NueXini/BuildOpenWrt/master/sh/language_fix.sh | sudo bash
```
