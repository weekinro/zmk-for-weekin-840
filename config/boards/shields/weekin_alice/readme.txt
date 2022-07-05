1、boards文件夹里的文件不用修改
2、kconfig.defconfig文件里只需要更改键盘名字即可，区分大小写
3、Kconfig.shield，是板子信息，只需要更改板子（键盘）名字即可
4、.config文件类似qmk的ruls.mk文件，开RGB和OLED旋钮等配置文件，基本不用修改
5、.keymap文件同qmk的keymap文件，更改对应键值即可
	#define DEFAULT 0    ：DEFAULT只是这个层的名字，为了方便自己看而已，有没有都无所谓

其他注释在文件内
	