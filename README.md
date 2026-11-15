# 星流 AstraFlow

[![星河岛歌词与面容幻影：胶囊、单副岛和双副岛](https://raw.githubusercontent.com/Xposed-Modules-Repo/com.astraflow.tool/main/assets/lyrics-and-phantom-3055522.gif)](https://astraflow.cc/island/)

**星河岛在屏幕顶部显示歌词、微信消息和人脸识别动画。胶囊与展开卡片可以分别使用相册里的图片、GIF 或视频作背景。**

[下载正式版](https://github.com/Xposed-Modules-Repo/com.astraflow.tool/releases/latest) · [版本更新日志](https://github.com/Xposed-Modules-Repo/com.astraflow.tool/releases) · [星河岛演示](https://astraflow.cc/island/)

**当前正式版：v2.2.7。** 修复云端备份、配置分享与工单处理异常，完善配置恢复、失败重试和附件处理。

## 星河岛能做什么

- **星河岛歌词。** 在胶囊中查看滚动歌词，也可同时显示原文与译文。展开后可切歌、暂停或调整播放进度。支持词幕、SuperLyric 和系统歌词（LyricInfo）；音乐卡片可调整按钮位置与封面配色。
- **人脸识别岛。** 锁屏解锁时显示识别动画。「面容幻影」在识别成功后显示圆环与对勾，再收回胶囊。在星流内可切换主题并试播成功、失败效果。
- **微信消息上岛。** 在「通知上岛」选中微信，收到通知后可展开查看头像和正文。通知支持快捷回复时，可直接在卡片里输入和发送。
- **图片与视频背景。** 在「外观」中分别为胶囊和展开卡片选择素材、裁选显示区域和调整背景深浅。描边、圆角、位置和动画也可单独设置。
- **胶囊、单副岛与双副岛。** 多项内容同时进行时，主岛显示当前事项，其他事项可显示在一侧或两侧。点按副岛可切换至主岛。
- **系统流体云。** OPPO、一加、真我的 ColorOS 15、16、17 设备可在星河岛查看系统提供的外卖、打车、导航和计时等提示。在「星河岛 → 系统流体云」可查看运行状态、选择显示内容。关闭该功能不影响音乐、普通通知和验证码。

<p align="center">
  <img src="https://raw.githubusercontent.com/Xposed-Modules-Repo/com.astraflow.tool/main/assets/wechat-reply.webp" width="396" alt="微信消息在展开卡片内编辑和发送">
  <img src="https://raw.githubusercontent.com/Xposed-Modules-Repo/com.astraflow.tool/main/assets/card-photo-background.webp" width="396" alt="使用相册图片作为展开卡片背景">
</p>

## 安装与适用范围

星流需要 **Android 15 或以上、Root 权限及支持 API 102 的 LSPosed**。星河岛面向符合条件的安卓设备，不限品牌；系统功能的可用范围因设备而异。

1. 从[正式发布页](https://github.com/Xposed-Modules-Repo/com.astraflow.tool/releases/latest)下载安装包。首次安装时，在 LSPosed 中启用星流，并按应用提示授权所需的系统作用域。
2. ColorOS 15、16、17 的系统流体云由星流内置，无需另外安装或启用插件。使用系统流体云需为星流授权「系统界面」；「系统桌面」授权用于打开应用和返回桌面的动画。
3. 更新可直接覆盖安装，保留设置和登录信息。星流会自动清理旧流体云插件，无需因此重启手机。若更新后功能仍未生效，请在首页右上角「维护」中执行「重启作用域」。

## 更多功能与帮助

星流还提供堆叠通知、浮窗回复、状态栏定制、超高帧录屏、配置备份和插件商店。部分系统功能取决于设备能力。

- **问题反馈：** 登录星流后，打开首页「问题反馈与远程调试」；也可查看[公开处理进度](https://astraflow.cc/feedback)。
- **社区：** QQ 群 **979221822** · [酷安：穆远星](https://www.coolapk.com/u/28719807)。
- **应用接入：** [星河岛开发者平台](https://astraflow.cc/island/develop-quickstart.html)。

Copyright © 2026 穆远星（MuYuanXing）。保留所有权利。
