fdi用法：
imgmount 0 a.fdi -t floppy
imgmount 1 b.fdi -t floppy
0 和 1 分别对应两个软盘驱动器
==========
同一个驱动器加载多张fdi用法：
imgmount 0 a.fdi b.fdi c.fdi d.fdi e.fdi -t floppy
换盘快捷键 F11 + O（欧不是零）
==========
需要把dosbox设置为pc98模式才能玩pc98的游戏：
conf文件里，有一项 machine = pc98，这样就可以了
==========
游戏声音太大怎么办？使用命令行：
mixer master 50:50
即左右声道的音量各为50%
mixer master 0:0 就是静音，100:100就是100%音量