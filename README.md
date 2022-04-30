E8820v2-1907和e8820v2-master基于https://github.com/openwrt/openwrt.git

lede和8820v2基于https://github.com/coolsnowwolf/lede.git


======================================
e8820v2-master来源于siwind

-----------------------------------------
1907是按恩山sivs147大侠源码修改的，原Z-Prion/wr720n-710n-700n-lede-file库的不好用，编译报错。恩山sivs147大侠源码不错，编译后刷机成功，再后来找到siwind的库一看，和恩山sivs147大侠源码一摸一样。

-----------------------------------------
lede编译还在报错，以最基础.config编译，以排除.config问题


CONFIG_TARGET_ramips=y

CONFIG_TARGET_ramips_mt7621=y

CONFIG_TARGET_ramips_mt7621_DEVICE_zte_e8820v2=y


lede用这最基础.config能过编译，说明报错有.config因素，刷机后登录页面很卡，但有线和无线都能用，也有kvr。


---------------------------------------------------------------
8820v2按恩山sivs147大侠源码修改，能过编译，能启动，但巨卡，而且没有交换机。
