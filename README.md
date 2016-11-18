家聊
====
轻量级IM开源项目，基于环信Sdk
------

想直接体验项目运行效果的可[点击这里下载apk](http://ogqrscjjw.bkt.clouddn.com/familychat_debug_v1.1.apk)
<br/>
###更新日志：
####V1.1:
①添加友盟统计，方便搜索崩溃信息<br/>
②更新环信库到最新版本<br/>
③修复部分bug<br/>
####V1.0：
正式发布

###初衷<br/>
很久之前想教家里老人学习使用智能机，让他们能用App和家人交流沟通，但是发现市面上流行的社交软件对于他们来说学习成本太高，毕竟他们从来没使用过智能手机，这些社交软件中很多功能都是不需要的，所以就产生了自己做一个轻量级IM软件的想法。起初没想做成开源的，后来发现其实这也是一个锻炼总结的好机会，所以就有了这个开源项目：家聊<br/>
<br/>
###项目特点<br/>
个人偏向使用原生技术，所以在开发过程中倾向于自己写实现过程，当然也有使用到一些第三方库和控件（在此感谢那些为开源做出贡献的先驱者们，站在前人的肩膀上，必须时刻保持感恩之心！）项目中基础架构类似MVP，但不是按照安卓官方标准来的，而是在自己的理解上精简了部分，且没有做整体的MVP封装，但是应该不会影响代码理解。<br/>
核心通讯组件是使用的环信3.X版本，官网地址：http://www.easemob.com/ ，在此感谢环信！<br/>
<br/>
###主要功能：<br/>
1.聊天模块，包含文字聊天、语音聊天、发送图片、短视频、实时音频通话、实时视频通话。<br/>
2.通讯录：可获取系统通讯录，和环信好友关系整合。<br/>
3.拨号器：自定义的简单拨号盘，方便老人直接拨打电话<br/>
<br/>
###项目截图：<br/>
![](https://github.com/Vanish136/FamilyChat/raw/master/screenshoot/FC01.png)
![](https://github.com/Vanish136/FamilyChat/raw/master/screenshoot/FC02.png)
![](https://github.com/Vanish136/FamilyChat/raw/master/screenshoot/FC03.png)
![](https://github.com/Vanish136/FamilyChat/raw/master/screenshoot/FC04.png)
![](https://github.com/Vanish136/FamilyChat/raw/master/screenshoot/FC05.png)
![](https://github.com/Vanish136/FamilyChat/raw/master/screenshoot/FC06.png)
<br/>
###开源引用
1.EventBus:https://github.com/greenrobot/EventBus<br/>
2.Ormlite:https://github.com/j256/ormlite-android<br/>
3.Pinyin4j:https://github.com/belerweb/pinyin4j<br/>
4.PermissionDispatcher:https://github.com/hotchemi/PermissionsDispatcher<br/>
5.SelectableroundedImageview:https://github.com/pungrue26/SelectableRoundedImageView<br/>
6.SectorProgressView:https://github.com/timqi/SectorProgressView<br/>
7.Android-ScalableVideoView:https://github.com/yqritc/Android-ScalableVideoView<br/>
8.FlatUI:https://github.com/eluleci/FlatUI<br/>
9.Glide:https://github.com/bumptech/glide<br/>
10.Android-Crop:https://github.com/jdamcd/android-crop<br/>
11.PhotoView:https://github.com/chrisbanes/PhotoView<br/>
项目中某些库也有引用到一些别人的代码片段（例如PtrView、QrCode库中部分代码是参考网上资料），但是由于无法找到具体出处，在此暂不贴出引用链接，如果有人能提供详细出处，还请联系我，谢谢！
<br/>
####联系作者
如果发现项目bug或者对项目有好的建议，欢迎提交issue，或者通过下面的联系方式联系我.<br/>
*QQ：505515031  746604151<br/>
*邮箱：505515031@qq.com<br/>
*微信：Vanish520136