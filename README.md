# esp8266_oled_follower
IOT 

与 PCtoLCD 程序配合，生成用于   显示用的字模字体文件

用法
先用 PCtoLCD 程序生成字模文件，

修改此程序配置项中对应的字段，然后在在arduino中打开 即可

注意
使用 PCtoLCD 程序时，选项中“输出选项”中仅勾选“输出精简格式”和“输出紧凑格式”，“点阵格式”选择“阴码”，“取模走向”选择“顺向”，“取模方式”选择“逐行式”，“自定义格式”中选择“C51格式”。

在生成的字模文件中，手动去除文件开头的索引以及结尾的空行


[教程](https://mp.weixin.qq.com/s?__biz=MzA4NzM2MTAzNA==&mid=2457634042&idx=1&sn=a4ee1d20f9af04c4bbed056b57cdfde4&chksm=87b2b79fb0c53e89dd29942d9752cf4b7a053d6678a6a4cc8b4c9632499f13fbadc9caaf262c&token=412454592&lang=zh_CN#rd)

[oleddisplay] (http://oleddisplay.squix.ch/#/home)


License
BSD New License
