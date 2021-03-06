
# 概述

微信电脑客户端多开工具，支持防消息撤销，支持语音消息备份（demo）。

1. WeChatResource目录是防撤销插件源码，暂时只支持固定版本(非通用，[具体见更新日志](#更新日志))，如有需要请联系我兼容或者自行修改。
2. MultiWeChat是多开源码
3. bin目录是已经编译好可直接使用的文件。

使用方法：

1. 双击运行WeChat多开(防撤销).exe即可。
2. 如更新了WeChatResource.dll，请使用如下参数运行：`WeChat多开(防撤销).exe n`。
3. `superwx.ini`配置如下：
```
	[config]
	revokemsg=1  #0：关闭防消息撤销，1：打开消息防撤销
	voicemsg=c:\ #填入备份语音消息的目录，空为关闭语音消息备份功能
```

# 更新日志

**2019年2月16日(v1.1.3)**
1. v1.1.3.2，更新支持2.6.6.44
2. bin目录为最新可执行文件[下载地址](https://github.com/anhkgg/SuperWeChatPC/tree/master/bin)

**2019年2月13日(v1.1.3)**
1. 更新支持2.6.7.32
2. bin目录为最新可执行文件[下载地址](https://github.com/anhkgg/SuperWeChatPC/tree/master/bin)

**2019年2月1日(v1.1.3)**
1. 增加支持语音消息备份（仅支持2.6.6.28），只是个demo，有特殊需要请自行修改或者联系我。
2. 增加`superwx.ini`配置文件，可自行开关防消息撤销和语音消息备份
3. [下载地址](https://github.com/anhkgg/SuperWeChatPC/releases/tag/v1.1.3)

**2018年12月28日(v1.1.2)**
1. 更新支持微信（2.6.6.28）
2. 更新支持随机mutex多开
3. [下载地址](https://github.com/anhkgg/SuperWeChatPC/releases/tag/v1.1.2)

**2018年11月30日(v1.1.1)**：
1. 增加消息防撤销功能，暂时只支持固定版本(2.6.5.38，2.6.6.25），如有需要请联系我兼容或者自行修改。
2. MultiWeChat增加更新安装防撤消插件和更新插件功能。
3. [下载地址](https://github.com/anhkgg/multi_wechat_pc/releases/tag/v1.1.1)
4. multi_wechat_pc更名为SuperWeChatPC

**v0.0.1**：
1. 仅支持多开功能，[下载地址](https://github.com/anhkgg/multi_wechat_pc/releases/tag/v0.0.1)

# 更多

技术细节请参考文章：

1. [https://mp.weixin.qq.com/s/bb7XMxop7e8rd7YqQ88nyA](https://mp.weixin.qq.com/s/bb7XMxop7e8rd7YqQ88nyA)（多开）
2. [https://mp.weixin.qq.com/s/E7N6LzAH4p88Gu4f_qwGlg](https://mp.weixin.qq.com/s/E7N6LzAH4p88Gu4f_qwGlg)（消息防撤销）
3. [https://mp.weixin.qq.com/s/h9d8aO79OvkpV9bknVT60A](https://mp.weixin.qq.com/s/h9d8aO79OvkpV9bknVT60A)（备份语音）

# TODO

1. 加好友
2. 批量回复，发送、定时发送
3. ....

# 支持作者

![img](pay.png)