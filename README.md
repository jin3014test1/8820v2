1907基于https://github.com/openwrt/openwrt.git

lede和8820v2基于https://github.com/coolsnowwolf/lede.git

8820v2为lede的参照newifi-d2的增加交换机修改




-----------------------------------------
1907编译可以过，但机器不启动，研究中

lede编译还在报错，研究中

目前：以最基础.config编译，以排除.config问题


CONFIG_TARGET_ramips=y
CONFIG_TARGET_ramips_mt7621=y
CONFIG_TARGET_ramips_mt7621_DEVICE_zte_e8820v2=y
