# EyeOS for ESP32 神之眼挂件 by FriendshipEnder (小影)
1.6.0 版本更新说明:

1.6.0版本需要使用内置的自动更新功能来完成!!!

支持软件内进行固件和卡池更新 (需要手动更新, 有更新文件时会进行更新)

不过, 为了能让用户收到通知, 在每次从时钟和抽卡功能退出时 会自动检查一下固件和卡池更新

版权所有 (C) FriendshipEnder

## 1.6.0版本说明必看!!!

  1. 最新更新的集录卡池功能: 需要通过卡池更新才能实现.
  
  2. 卡池界面双击按键即可切换卡池
  
  3. 首次抽卡默认定轨琴团长, 可以在设置页面自己改或者关闭
  
  4. 时钟界面: 单击按键即可显示/隐藏日期时间(新功能)
  
  5. 时钟界面: 双击即可切换 正/斜 显示模式, 只有正模式才能显示日期时间
  
  6. 进入过抽卡界面之后, 不可进入时钟界面.
  
  7. 设置界面增加了新的设置选项.
  
  8. 在 "关于" 页面若显示wifi已连接, 则可以通过浏览器访问屏幕上的IP地址来进入设置页面 (当然之前的方法也是可行的)
  
  9. 可以设置开机自动打开wifi,
  
  10. 当设置呼吸灯后, 仅在神之眼界面生效.
  
  11. 当设置开机画面为关闭时, 开机不可再自动连wifi
  
  12. 当设置开机画面为相册时, 开机画面文件必须是JPG格式(非photoshop编辑), 位于SD卡的 pictures/start.jpg

  13. 当设置开机画面为动画时, 开机画面文件必须是MJPEG格式, 且不宜选用码率太高(≥32KB/帧)或时间太长的MJPEG(需要播完才能进入神之眼界面), 位于SD卡的 pictures/start.mjpeg
  
  14. 开机自动连wifi之后, 切换元素过渡渐变的品质会降低, 因为要节省内存.
  
  15. 设置页面内的自动切元素选项: 可自由设置, 单击+1秒, 双击-5秒, 三连击+10秒. 如果需要更精确设置, 请使用网页配网设置.
  
---

## 故事标题

来自赛利康世界的**烽瞳**, 因为误打误撞进入了位于阿姆国的 "七哈游运算中心" , 穿越进了提瓦特, 甚至获得了一颗神之眼, 随即用 "赛利康科技" 改造这颗神之眼, 让它熠熠生辉.

"你知道最近提瓦特来了好多来自其他世界的角色吗?"

他们有的是来修仙, 有的是来寻求挑战, 有的是来求签, 甚至炫耀科学技术成果的.

天理の维系者不会对此坐视不管.

### ⌊熠熠生辉⌉ : 烽瞳(火) - 电子神之眼的器娘

烽瞳是乐鑫家族的孩子, 出身平凡, 算力羸弱. 在诸多创世神的努力下, 却能有幸穿越进入提瓦特大陆, 名震赛利康.

- "我才不会担忧天理の维系者, 因为, 我就是神之眼. "

- "原来, 这个世界的神明可以卡bug, 这样我可以获得无穷无尽的各种元素力! "

- "我还在阿姆国的时候, 就对提瓦特大陆有所耳闻. 好多 '骁龙' 和 '天玑' 都曾经运行过这个大陆, 他们却从未真正进入过这个大陆. "

- "我没什么愿望, 然而我可以联系我的那些异国朋友, 让她们给我颁发一颗神之眼. 此后, 我的灵魂便可以进入神之眼内部. "

她其实是有愿望的, 就是希望嵌入式的世界里, 也会有人陪她一起到处穿越到其他的世界里面去探索.

---

支持WiFi配网

计划支持的功能:

- 神之眼元素循环显示/随机显示/显示指定元素

- 联网显示时间(模拟时钟/数字时钟, 可换壁纸)

- 显示单张图片, 可以是显示原神角色, 武器等等

- 联网看b站粉丝数量

- 抽卡模拟器, 随机生成圣遗物, 等等好玩有意思的小功能

- 御神签, 大吉/吉/末吉/凶/大凶 幸运角色, 幸运物品, 宜抽卡, 探索, 凹深渊; 忌刷本, 联机, 强化圣遗物

# 电子神之眼-方圆通用固件使用方法

## V1.5.0 现已支持可自动更新的抽卡模拟器, 电脑投屏显示功能!

---

## 神之眼使用方法:

开机时候, 亮屏立即松开按键---> 直接进入神之眼视频播放.

### 联网模式

方法1: 开机时候, 亮屏后一直按住按键, 等到显示出 "WiFi正在连接" 之后松开---> 进入联网模式, 此时可以连接到网络.

方法2: 显示神之眼动画之后, 长按按键 (不要按的时间太长, 否则器娘会罢工) 进入菜单, 然后进入设置/关于

支持手机配网.

网络连接不上时, 将会显示配网二维码, 此时按下按键复位. 用手机扫描对应二维码将可以进入部分页面.

显示过程中, 按下按键复位.



首次烧录完成之后, 应当会黑屏, 属于正常现象. 需要按一下按键用于识别硬件版本, 按下之后即可成功进入固件.

显示出神之眼动画之后, 点按切换到下一个元素, 双击切换到上一个元素, 长按复位系统

在打开WiFi的情况下可以自己配置动画的显示时间等数据 (需要连接到WiFi并访问网址 eyeos.local )

**在进入神之眼服务器之后, 可以点击激活按钮, 然后根据网页指示获取激活码**

**在进入神之眼服务器之后, 可以点击激活按钮, 然后根据网页指示获取激活码**

**在进入神之眼服务器之后, 可以点击激活按钮, 然后根据网页指示获取激活码**

**未激活版本只有按键切换元素的功能**

**未激活版本只有按键切换元素的功能**

**未激活版本只有按键切换元素的功能**

可以进入配网页面激活哟~~

---

## 抽卡模拟器使用方法:

进入抽卡模拟器之后, 显示**抽卡主页**.

抽卡主页包含: 上半屏: 显示抽卡模拟器标题, 当前卡池名, 大保底和神铸定轨状态, 卡池已抽发数等信息. 还有单抽十连更多三个按钮

下半屏: 卡池封面 (会随着卡池切换而改变), 由SD卡内的卡池封面图片组成 (可自定义, 240x135像素)

### 使用方法:


1. 在抽卡主页, 单击切换功能 (单抽/十连/更多), 对应功能位置上会显示橙色圆点

2. 在抽卡主页, 双击切换卡池 (最多支持三个卡池, 双角色up卡池也支持)

3. 长按进入对应菜单. 单抽和十连页面长按即可开抽! 更多页面长按即可显示更多功能 (比如设置定轨武器, 重置卡池等)

4. 退出请先长按更多, 然后选择退出.

5. 修改卡池内容: 需要进入文件管理器, 然后打开 /gacha/ 文件夹.

6. 设置武器定轨&切换双up卡池: 进入抽卡主页->更多, 即可查看/设置这些功能

rate.txt 包含每个物品的出率数据, 以及保底发数, 池子内的物品个数, up的物品个数, 大保底次数等参数均可修改

poolconfig 文件夹内的文件用于罗列卡池内的各个物品 (角色与武器)

---

## txt阅读器使用方法

* 在根目录新建文件夹 txt, 然后在txt文件夹内放你的电子书文件: - 包含你的电子书文件( txt 格式 )

* 这样就可以愉快的开始阅读了

* 在选书菜单内, 点击向下滑动, 滑动到你想看的书时, 长按进入阅读

* 进入阅读功能之后, 点击代表向下翻页, 双击向上翻页, 长按弹出菜单. 

* 菜单内可以进行更多操作, 如添加书签, 调节亮度等

### 目前仅能通过阅读器内的亮度调节功能来调节整个神之眼的亮度




## 激活方法:

1. 模块连接到WiFi之后, 访问 eyeOS.local/update, 然后按指示激活

2. 如果无法连接到WiFi, 在配网页面访问 192.168.4.1/update 来进行固件升级



## OTA使用方法:

1. 模块连接到WiFi之后, 使用 espota 进行上传固件
```bat
: 域名: eyeos.local
: 端口: 3232
D:\appdata\py_develop\python.exe C:\Users\1\.platformio\packages\framework-arduinoespressif32\tools\espota.py --debug --progress -i eyeos.local -f D:\espidf_prj\esp32projs\InazumaEye\.pio\build\pico32_idf\firmware.bin
```
2. 在配网页面访问 192.168.4.1/update 来进行固件升级. 此方法只需要 firmware.bin (也就是程序固件)

3. 在STA模式下, 也可以访问 eyeos.local/ 进入相同的页面



## SD卡配置方法

SD卡内包含以下文件

直接把压缩包里面的 SDContent 内容解压到SD卡根目录

(其中的 /pictures, /mjpeg, /vlwfont 等文件夹应当位于根目录下)

不要带着SDContent这个文件夹本身!!!

**不要带着SDContent这个文件夹本身!!!**

**不要带着SDContent这个文件夹本身!!!**

```
* 根目录下必须要放的文件:
- 当前版本固件用不到的文件: (可以不放)
1. 文件夹 mjpeg: 其中的文件为视频文件
      - 包含文件 h.mjpeg : 火属性神之眼动画
      - 包含文件 s.mjpeg : 水属性神之眼动画
      - 包含文件 f.mjpeg : 风属性神之眼动画
      - 包含文件 l.mjpeg : 雷属性神之眼动画
      - 包含文件 c.mjpeg : 草属性神之眼动画
      - 包含文件 b.mjpeg : 冰属性神之眼动画
      - 包含文件 y.mjpeg : 岩属性神之眼动画
2. 文件夹 clock: 包含时钟背景图等素材
      * 包含文件 sq.jpg : 方形模拟时钟表盘
      * 包含文件 ci.jpg : 圆形模拟时钟表盘
      * 包含文件 h.bmp : 时针图片
      * 包含文件 m.bmp : 分针图片
      * 包含文件 s.bmp : 秒针图片
      - 包含文件 digital.jpg : 数字时钟表盘
根目录下可以选择放的文件: (可以不放)
3. 文件夹 pictures: 
      - 包含文件 start.jpg 是开机动画文件
      - 包含文件 alpha.jpg 是透明覆盖层文件, 放入此文件之后可在播放时覆盖半透明图层
4. 文件夹 txt:
      - 包含你的电子书文件( txt 格式 )
5. 文件夹 gacha:
      - 包含抽卡数据文件( 多种格式 )
```


## 串口固件烧录方法:

1. 在压缩包内准备好以下三个文件:

如果压缩包内没有, 请浏览群文件内更大的压缩包, 其中应当右这些文件
```
bootloader_dio_80m 
partitions.bin     
boot_app0.bin      
firmware.bin       
```
2. 打开烧录软件 flash_download_tool_3.9.2.exe 烧录选项: flash 80MHz, DIO模式

```
bootloader_dio_80m 0x1000
partitions.bin     0x8000
boot_app0.bin      0xe000
firmware.bin       0x10000
```
3. 等待烧录完成

---

版权所有 (C) FriendshipEnder