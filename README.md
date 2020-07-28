# tele-aria2-openwrt

A tele-aria2 bot for openwrt , based on Node.js .  

瞎抄的，我小白一个，不提供技术支持  
只有主程序，没有Luci(不会写)  
怎么配置以及使用请参考原作者说明  

编译：  
```
git clone https://github.com/EnnawYang/tele-aria2-openwrt  
make menuconfig  
choose Network -> Telegram Bot -> tele-aria2 
make -j1 V=s  
```  
type `tele-aria2 --help` to see how to get started.  

# 原作者链接

GitHub：https://github.com/HouCoder/tele-aria2  
NPM：https://www.npmjs.com/package/tele-aria2  
