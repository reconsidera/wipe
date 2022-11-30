# WP反人力搜查手机方法汇总

2、3 部分内容整合自 iYouPort 和长毛象公共留言板  

（如需实操，建议事先使用闲置备用机反复尝试练习，寻找最快捷的方法，提高自己的熟练度，以免临场手忙脚乱）

---

目录1 
- [1.备用机](#1备用机)
- [2.隐藏内容](#2隐藏内容)
- [3.删除内容](#3删除内容)

---

目录2
- 0.概述
- 1.备用机
	- 1.1 概述
	- 1.2 伪装
- 2.隐藏内容
	- 2.1 隐藏现场拍摄的视频照片
		- 2.1.1 iOS/Android通用
			- Stingle
			- 伪装隐藏文件应用
		- 2.1.2 iOS
			- 关闭「显示已隐藏相簿」   
	- 2.2 隐藏翻墙软件、墙外软件
		- 2.2.1 iOS
			- 方法1-编辑主屏幕
			- 方法2-屏幕使用时间
			- 专注模式
			- Spotlight设置隐藏
		- 2.2.2 Android
			- 方法1：多用户
			- 方法2：替换应用程序图标
				- 方法2.1 使用apk编辑器
				- 方法2.2 使用第三方桌面
			- 三星-安全文件夹
			- VMOS
- 3.删除内容
	- Android
		- Duress
		- Wasted
- 锁定设备
	- iOS
	- Android

---

## 0.概述

利用系统未披露的零日漏洞进行破解的数字取证设备是无法防范的，理论上任何写入闪存的数据在删除后都可以恢复。无论对方是否有这种设备，是否有资源投入此类设备解锁你的手机，在料敌从宽原则下的保守做法是使用【备用机】——坚壁清野，让可能对你不利的数据自始就不存在于被检查的手机上。 

【隐藏内容】只能瞒过外行，或利用对方资源限制取胜，并不保险。  

笔者只建议使用如 Duress 等具备一定【隐匿性】的删除方法。除非设备中存有可能导致自己或他人被定罪的关键信息，不建议锁定设备并坚决拒绝解锁设备，或者事后使用远程锁定/删除等方式清除数据，以免加重对方疑心，或导致协助者被控毁灭证据。  

---

## 1.备用机

### 1.1 概述
至少准备三部手机，一部【翻墙用机】（安装翻墙软件，获取资讯（发布信息建议用桌面系统+Tor Browser）），一部【工作生活用机】（安装微信、QQ、支付宝等中资软件/风险软件），一部【线下专用机】（接收实时资讯，拍摄现场照片视频）

### 1.2 伪装
将【线下专用机】伪装成【工作生活用机】，减少人力检查者的疑心：  
- 安装微信、微博、支付宝、小红书、抖音、快手等墙内流行应用
- 微信、微博等通讯/社交软件登录备用帐号，填充一些与家人朋友的聊天内容
- 导入一些生活/工作文件、照片、视频等文件
- 不要存储近期敏感话题的文本、视频、图片或截图

## 2.隐藏内容

### 2.1 隐藏现场拍摄的视频照片

#### 2.1.1 iOS/Android通用

##### Stingle 
[Stingle](https://stingle.org/) – 自由开源的端对端加密云相册，需要使用电子邮件注册（勿用国产邮箱），提供 1 GB 免费空间，支持将拍摄内容自动加密上传云端，并从本地相册删除。  

[Play Store](https://play.google.com/store/apps/details?id=org.stingle.photos) | [App Store](https://apps.apple.com/am/app/stingle-photos/id1582535448)  

设置方法：打开 app，前往 Settings > Import，打开「Enable auto import」和「Delete original files after import」

##### 伪装隐藏文件应用

[Photo Vault Calculator](https://play.google.com/store/apps/details?id=com.hld.anzenbokusucal) – Android  
- 功能：闯入警报功能；可以为假空间设置密码；AES加密算法，对文件格式、大小没有任何限制；支持直接拍照和录制私密视频

[Calculator#](https://apps.apple.com/gb/app/calculator-hide-photos-videos/id1165276801) – iOS
- 使用方法：选择 "计算器"，输入密码，点击"%"，选择想隐藏的文件类型，导入文件。
- 功能：密码保护隐藏的文档和其他文件；锁定音频以安全地记录语音笔记。可以从 PC、Mac 或其他设备进行 WiFi 传输。还有内置的 Web 浏览器、内置的密码管理器和钱包，内置安全笔记、待办事项和提醒，内置的联系人管理器。

https://t.me/iyouport/12035

#### 2.1.2 iOS 

##### 关闭「显示已隐藏相簿」   
在「设置 > 照片」中，关闭「显示已隐藏相簿」。  
拍摄完成后立即打开相册 app，在右上角选择「隐藏」。  

https://m.cmx.im/users/shrieker/statuses/109423809813429878

### 2.2 隐藏翻墙软件、墙外软件

#### 2.2.1 iOS

##### 方法1-编辑主屏幕

长按屏幕，或长按任意 app，选择「编辑主屏幕」 
选中需要隐藏的 app，点击「从主屏幕移除」    

https://m.cmx.im/@LeaveCSNet/109422210014922449


##### 方法2-屏幕使用时间
> 屏幕使用时间 > 内容与隐私访问限制 > 内容访问限制 > app > 不允许  
> 返回主页之后大部分app都不在了，留下的基本都是系统自带的，问就是手机刚买还没来得及下软件/手机屏幕碎了寄出去修怕被知道隐私把软件卸了/自由发挥  
> update：谨慎尝试，如果有给app分类放进文件夹的话，打开不允许再关掉app会全部跑出文件夹（

https://g0v.social/users/kks_111/statuses/109421647106036738

> 設置菜單中「屏幕使用時間」➡️打開「內容和隱私訪問限制」➡️「內容訪問限制」➡️「應用」設置年齡限制，微博微信等社交app還有其他新聞類等一般都是17+才可以使用的，可以在年齡限制里選擇12+/9+/4+來限制顯示在手機上的相應年齡限制允許的應用，甚至可以選擇該菜單中的第一個「不允許應用」選項，這樣只有系統app才會顯示，並且通過這個方法屏蔽顯示的app也無法在系統中及iphone存儲空間中搜索到，屏蔽期間app不工作但是資料依然存在。該訪問限制也可以設置密碼，避免其他人進行設置。缺點是恢復顯示屏蔽的app後，需要重新整理順序。 參考教學視頻：https://youtu.be/PLblg-gnmZg

https://mstdn.jp/users/seekinoko/statuses/109423110191693290

##### 专注模式
> iOS 15 开始，系统引入一个新功能叫 「专注模式」，这个模式类似于智能手机刚刚兴起时代的「情景模式」，系统允许用户自定义多个不同的模式来区分不同的使用场景。用户可以在 系统设置 > 专注模式 中自定义一个新的模式，并自定义在这个模式下，主屏幕显示的内容。用户可以自由决定哪些 App 不被显示。

https://t.me/AppleNuts/1596

##### Spotlight设置隐藏

> 设置 > Siri 与搜索 > 找到对应的 App 关闭所有相关选项。

https://t.me/AppleNuts/1596

Siri 与搜索 > 关闭「显示建议」和「显示最近项目」

##### ~~iOS不支持更换应用程序图标~~
iYouPort 分享的方法 https://t.me/iyouport/12079 具有误导性，在桌面创建自定义图标的快捷方式并不能隐藏应用程序本身。


#### 2.2.2 Android

**注：国产安卓 ROM 不一定支持以下功能。尽可能使用原生/类原生 Android。**

##### 方法1：多用户

>  setting > system > multiple user 中可以添加新的 user，这个 user 可以安装不同的 app，有不同的密码，也可以取消人脸或者指纹解锁。  
大家可以把国外的 app 装到一个新的 user 里面，然后不开指纹和人脸解锁，设长密码，把名字起的吓人一点 “系统分区” 之类的，如果被发现就说这是系统，我不知道怎么进去。记得把这个 user 的 lock screen notification 关掉。

https://mas.to/@ordinarychinese/109428646612237788

##### 方法2：替换应用程序图标

###### 方法2.1 使用apk编辑器

> 来个比较通用且毫无技术含量的安卓app换壳教程。这么换出来的图标无法像原有图标一样适应方形圆形，效果就是上面那样。但胜在有手就能换，简单易懂。  
0.准备好你要换壳的app，把app放在手机储存里面你找得到的位置。  
1.下载一个mt管理器，没有root权限给它也没关系，我用的是这个觉得不错，别的可能也有可以的。下载一个apkeditor（apk编辑器）。  
2.打开apkeditor，点击第一项”apk文件",选中你想换壳的app，选择“通用编辑”，在这里更改“安装包名”（改成和原来格式差不多的就可以，比如com.tencent.mm改成com.zhangxiaolong.sm)。更改“软件名称”，即你想伪装的软件。改完后点击“保存”。然后不选安装选关闭。  
不要在这里更改图标，一般来说是没用的。  
3.接下来更改图标。打开mt管理器，打开文件夹"ApkEditor",继续打开"tmp“，你会发现里面有一个结尾是signed.apk的文件（即你刚刚修改的文件）。单击这个文件，在弹出的窗口中点”查看“。  
现在就来到了apk的内部。现在找到"AndroidManifest.xml”这个文件，单击它，选择“反编译”。你可以看到一堆完全看不懂的代码。这时候点击右上角三个点，选择“搜索”，在屏幕下方出现的查找框里输入“android:icon”，找到第一个出现"android:icon"的地方，你会发现后面跟着一串路径，@什么东西之类的。  
没图我编不下去了，语言组织能力太烂。剩下的和图片结合一下吧。图文教程从链接下载。
https://anonfiles.com/r1w3b2Kcy0/_docx
总而言之，言而总之，最后可以把软件打扮成又红又专的样子。  

https://social.datalabour.com/@sweetbook/109427669842601334

> 一些app是可以直接修改包名和图标的。下载一个apkeditor之类的apk编辑器直接修改包名和图标和apk名字就可以了。你甚至可以把apk的图标和名字都改成学习强国的，但点开还是原本的应用。

https://me.ns.ci/@mightydesert/109425643640258465


##### 方法2.2 使用第三方桌面

> 下载一个第三方启动器（或者叫桌面，launcher），这里推荐nova启动器，功能够且兼容的安卓版本比较多。再下载一个图标包（选个你喜欢的就可以，比如轻雨图标包等等）。在设置里把你下载的第三方启动器设置成默认启动器（这一步不会的百度）。
大部分第三方启动器是可以自己随意更换显示的图标和显示的应用名字的。这时候你就可以把你手机里的twitter的图标换成图标包里的学习强国图标，名字改成学习强国了。

https://me.ns.ci/@mightydesert/109425643640258465


##### 三星-安全文件夹

「安全文件夹」功能  
> 可以把软件加入调整好文件夹内的后把自己原本那个删掉，所以可以实现表面上没有海外软件实际有的效果。相应的保护功能有：这个文件夹本身可以隐藏不在桌面显示，锁屏后再次打开文件夹需要密码，并且加入文件夹的软件推送的通知信息等会隐藏不显示内容，在软件上的截图也是在文件夹内的相册单独放。  

https://bgme.me/users/jumptowardsnight/statuses/109421789020447063

##### VMOS

在 [VMOS](https://www.vmos.com/) 虚拟机中运行翻墙/墙外软件。

https://bgme.me/@yukitskitsururinnn/109422148448969935

## 3.删除内容

### Android

#### Duress

[Duress](https://github.com/x13a/Duress)  
[F-Droid](https://f-droid.org/packages/me.lucky.duress/) | [Play Store](https://play.google.com/store/apps/details?id=me.lucky.duress) 

> Tiny app to listen for a duress password on the lockscreen.
When found, it can send a broadcast message or wipe the device.


> [Duress](https://play.google.com/store/apps/details?id=me.lucky.duress) 是一个允许你生成无效密码的应用程序，一旦输入该密码，它将向你指定的亲人/队友发送通知。你也可以用这个假密码来擦除你想隐藏的敏感数据。攻击者甚至不会注意到。正常的密码仍然有效，如果你输入密码，设备就会被解锁。当然希望你不要陷入这种情况，尤其是，尽可能不要在手机上保留那种非常重要的信息。

https://t.me/iyouport/12039

#### Wasted

[Wasted](https://github.com/x13a/Wasted)  
[F-Droid](https://f-droid.org/packages/me.lucky.wasted/) | [Play Store](https://play.google.com/store/apps/details?id=me.lucky.wasted)
> You can use PanicKit, tile, shortcut or send a message with a secret code. On trigger, using Device Administration API, it locks a device and optionally runs wipe (factory reset). Or it can send a broadcast message instead of the wipe.  
Also you can:  
    fire when a device was not unlocked for X time  
    fire when a USB data connection is made while a device is locked  
    fire when a fake messenger app is launched  
    fire when a duress password is entered (companion app: Duress)  


> [Wasted](https://play.google.com/store/apps/details?id=me.lucky.wasted) - 在紧急情况下完全锁定和擦除您的手机。

https://t.me/iyouport/12029

## 锁定设备

### iOS

事先关闭生物验证（Face ID/Touch ID）  
临时停用生物验证，强行使用密码验证——可以长按「电源键」和「 音量 + 键」，调出关机界面。此时，生物验证会被暂时关闭，必须使用密码验证。）

https://t.me/AppleNuts/1596

### Android

> 安卓：进入锁定模式  
如果你需要参加游行，请使你的安卓设备进入锁定模式，以确保安全。  
功能：  
隐藏所有锁屏上显示的通知消息。  
禁用安卓的生物识别解锁功能和其他智能解锁功能（比如使用附近的蓝牙设备）。
强制要求使用主解锁方式（密码/图形）解锁屏幕。  
设置：  
设置-安全与位置-锁屏界面设定-显示“锁定”选项。  
使用：  
长按电源按钮，出现“锁定”选项。  
注意：  
此功能需要 Android 版本9（API 28）以上。  
部分（可能是全部？）国行ROM可能删除了此功能。

https://nya.one/notes/984fedl743
