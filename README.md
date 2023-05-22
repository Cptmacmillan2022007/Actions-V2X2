# Actions-V2X2
# I.本实例使用Github Actions编译你想要的自定义版本号以及名称的科学软件，理论上可以被修改为编译其他你想要的软件。来源于其他使用Actions的项目修改而成。
# II.使用方法
## 1.fork本项目
## 2.自定义版本
|**版本号**|
|:--------:|
|修改Actions-V2X2.yml文件第54~57的''中的内容|
## 3.跨平台编译
### 在项目Settings>>Secrets and variables>>Actions>>Repository secrets里添加以下变量
|**`TARGET_ARCH`**|**`TARGET_OS`**|**`BIN_NAME`**|
|:---------------:|:-------------:|:------------:|
|`386`不建议使用|`windows`|`填入自定义文件名，必须是英文`|
|`amd64`|`linux`|`<n/a>`|
## 4.生成文件位置
### 于release中查看
# III.后记
|**留给当下和未来的话**|
|:----------|
|**I.兼听则明，偏信则暗。**|
|**II.愿上帝保佑追击者，同时也保佑被追击者。**|
|**III.相信你一定会自由，同样也要做好面对最糟糕情况的一切准备。**|
|**IV.有信任才会有背叛。——使命召唤6现代战争2**|
|**V.如果想知道一个人真实的一面，请给他力量。**|
|**VI.愿我们能在没有墙的春天再次相遇，愿在墙外的人能够找到属于自己的幸福与快乐。**|
|**VII.愿你被这个世界温柔以待，即使生命总以刻薄荒芜相欺。**|
|**VIII.愿每个看到本项目的人平安喜乐。**|
|**IX.愿我们在没有恐惧的墙外再次相遇，这一天终会到来的。**|
|**X.一杯茶会逐渐冷却下来，一块冰会逐渐融化成水。相反水是不可能汇聚成冰的，因为融化正是熵增的一种表现。——《末世觉醒之入侵》**|
|**XI.夹着尾巴做人也是人，总比死了强。只要你人还活着，它就不怕你没柴烧。——袁腾飞**|
|**XII.黑暗之后，必是黎明。**|
|**XIII.……未完待续**|
