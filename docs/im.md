# WP加密即时通讯应用汇总

部分内容整合自长毛象、iYouPort  

- 加密 IM  
	- 去中心化、免手机号：Session、Matrix、Jami  
	- 中心化、需手机号：Telegram、Signal  
- 离线可用的 IM：Briar、Berty  

目录    
- [选择标准（供参考）](#选择标准供参考)
- [去中心化加密IM](#去中心化加密IM)
- [中心化加密IM](#中心化加密IM)
- [视频通话/视频会议](#视频通话/视频会议)
- [离线可用的IM](#离线可用的IM)


---

## 选择标准（供参考）  
- **加密/端对端加密**
- **自由开源软件**
- **持续开发维护中**
- **跨平台**

## 去中心化加密IM
- [Session](https://getsession.org/) – 免手机号；默认端对端加密；实时同步
- [Matrix](https://matrix.org/get-started) – 免手机号；联邦式去中心化；默认端对端加密；实时同步；部分服务器免翻墙（请用 [Blocky](https://blocky.greatfire.org/) 自测）
	- [Matrix 客户端](https://matrix.org/clients/)
		- [Element](https://element.io/) – Windows/macOS/Linux/Android/iOS/[Web](https://app.element.io/)
		- [FluffyChat](https://fluffychat.im/) – Linux/Android/iOS/Web
		- ...
	- [Matrix 教程 1](https://mastodon.online/@baoyue/109195419891683229)
	- [Matrix 教程 2](https://bin.moritz-fromm.de/?b717fdf35b2cb4a6#CFgneMrHtF4T35vEN3SaGkZRZ6ZHAA3oX5Kr79UBVTFz)（作者[在江湖而遠江湖](https://me.ns.ci/@zaijianghueryuanjianghu)。如有错请指正）
- [Jami](https://jami.net/) – Windows/macOS/Linux/Android/iOS；免手机号；默认端对端加密


## 中心化加密IM

- [Signal](https://signal.org/) – Windows/macOS/Linux/iOS/Android；注册需手机号码；默认端对端加密
- [Telegram](https://telegram.org/) – Windows/macOS/Linux/Web/iOS/Android；客户端开源；注册需手机号码；私密模式支持端对端加密；实时同步
<details>
<summary>Telegram 注意事项</summary>
<br>

BitRunX 保护Telegram隐私详细版：  
https://nitter.net/BitRunX/status/1597241595451277312#m  
1.设置【两步登录】，不然别人利用你的短信验证码就可以登录你账号  
2.将Phone Number设置为Nobody  
3.在Calls中【PEER-TO-PEER】设置为Never  
4.在添加联系人时候记得把【Share Number】去掉，切记  
5.【最后在线时间】最好也去掉  
6.私聊时尽量使用【私密聊天】或设置【自动删除时间】  
7.紧急情况时，时间如果完全来不及，则快速立马卸载app，如果还有多余时间可以删除退出相关聊天再卸载app  
8.设置Passcode，尽量不用指纹或者FaceID，如果锁屏密码忘了则只能重新安装app用账号登录  
9.不要轻易点击陌生地址的链接，因为这样可能会泄露你的真实IP  
10.最好买个Google voice号码来作为telegram绑定号码  
11.不定期注销账号重新注册，这样你的userid系统会重新生成，防止有人用api爬你的过往记录，注销重新注册哪怕号码是一样系统userid也会不相同。  
12.在注册的时候不要选择开启通讯录同步以及任何手机通讯录相关的操作，因为这样你的手机通讯录其他人如果有tg会收到提醒。将telegram的通讯录权限设置为不允许。  
如果有开过通讯录同步的最好注销账号重新注册，去删除同步的通讯录并把同步通讯录开关去掉。  
</details>


<details>
<summary>获取不记名号码</summary>
<br>

Google Voice虚拟手机号购买渠道，可靠性请自行判断  
风险警告：可能被谷歌封号，申诉后有机率解封  
https://buyaccs.com/en/buy-google-voice-accounts.php/  
https://www.accbay.com/service/buy-google-voice-number-accounts/  
https://www.selldra.com/product/buy-google-voice-account-for-1-5/  
以上接受BTC等加密货币支付；不要填写真实信息，建议使用临时邮箱（https://t.me/s/iyouport/11629）  
如使用加密货币付款，不推荐使用中资交易所  
https://t.me/gvstore  
https://t.me/voice_google  
参见  
https://telegra.ph/%E5%A6%82%E4%BD%95%E9%9D%9E%E5%AE%9E%E5%90%8D%E8%B4%AD%E4%B9%B0-Google-Voice-%E5%8F%B7%E7%A0%81-07-24  
https://github.com/ssnhd/googlevoice
</details>  

## 视频通话/视频会议 

- [Jitsi](https://jitsi.org/) – Windows/macOS/Linux/Android/iOS/Web
	- [Jitsi Meet](https://jitsi.org/jitsi-meet/) – 视频会议

## 离线可用的IM
- [Briar](https://briarproject.org/) – Android；默认端对端加密
	- [F-Droid](https://f-droid.org/en/packages/org.briarproject.briar.android/)
	- [Play Store](https://play.google.com/store/apps/details?id=org.briarproject.briar.android)
- [Berty](https://github.com/berty/berty) – iOS/Android；默认端对端加密
	- [App Store](https://apps.apple.com/tt/app/berty/id1535500412)
	- [Play Store](https://play.google.com/store/apps/details?id=tech.berty.android)
- 加密短信
	- [Silence-Android](https://git.silence.dev/Silence/Silence-Android/)
- 不推荐使用名气更大的Bridgefy，它原先不加密，目前虽然采用 Signal 协议，但它的用法仍被认为不安全，见 [Breaking Bridgefy](https://eikendev.github.io/breaking-bridgefy-again/)。

