<div align='center'>
    <a><img src='https://s21.ax1x.com/2024/03/13/pFco3Js.png' width='280px' height='270px' akt='maimaidx'></a>
</div>

<div align='center'>

# 曲奇BOT

由 [@澪度](https://qm.qq.com/q/AKKatQJnRm) 所独立开发的 基于街机游戏《舞萌DX》的便民BOT

基于 [@VikiBoss](https://github.com/vikiboss) 所开发的开源 [@Keli](https://www.npmjs.com/package/keli) 框架运行

</div>

## 简介

一款基于街机音游《舞萌DX》所制作的便民QQ机器人-曲奇BOT

使用NodeJS进行开发制作 所有功能都仅限于学习交流及增强游戏体验使用 切勿滥用

[官方群](https://qm.qq.com/q/3ZaGA5vERO) - [作者QQ](https://qm.qq.com/q/AKKatQJnRm) - [BOTQQ](https://qm.qq.com/q/MsPZk0CW4g)

## 感谢名单

衷心感谢所有为BOT开发提供技术支持/灵感/漏洞报告的贡献者

- [@曲奇-提供BOT名称](https://qm.qq.com/q/YWndmkSrKu)
- [@寒桠-提供部分功能支持/灵感](https://github.com/HanYaaaaaaa)
- [@开脆兔-BOT对应滴蜡熊插图来源于此](https://space.bilibili.com/13474674)
- 所有群友通过宣传和支持助力了BOT的成长

## BOT入群

需要BOT入群 请在QQ中添加[BOTQQ](https://qm.qq.com/q/MsPZk0CW4g)为好友

待自动同意后 发送群聊入群邀请 后续在群内发送 .help 皆可

但请注意 无论如何发生了什么 都**不得禁言/踢出BOT** 有退群需求**请联系作者** 看到第一时间处理 **不要禁言/踢出!**

以上操作会导致BOT被风控/封号 影响其他人的使用 **不要为了一己私欲影响其他人**

## 使用文档

BOT的所有命令**均可群聊/私聊触发** 下述命令不需要添加任何符号

> 如需调用查歌模块并查询乐曲 四月的雨 仅需要发送 .mai cg 四月的雨

> 无需在调用命令前添加[]符号

下述所有标题内容均为调用指令

### 菜单

#### .help

查看BOT帮助菜单

> 调用例子: .help

> 返回菜单图片

### 查歌

#### .mai cg [歌曲名]

查询《舞萌DX》中的任意歌曲及定数详情

> 调用例子: .mai cg 福瑞圣剑

> 返回查询结果 如未查找到则返回对应提示

#### .mai bm [歌曲名]

查询《舞萌DX》中的任意歌曲的别名 目前仅支持精确查询

> 调用例子: .mai bm 四月の雨

> 返回查询结果 如未查找到则返回对应提示

#### .mai ds [歌曲定数]

指定返回《舞萌DX》中的任意一个定数中的随机一首乐曲(范围为 Basic 1.0 - Re:Master 15.0)

> 调用例子: .mai ds 四月の雨

> 返回查询结果 如未查找到则返回对应提示

### 小黑屋

#### .mai xhw

返回BOT解禁小黑屋模块菜单

> 调用例子: .mai xhw

> 返回小黑屋模块菜单

#### .mai xhw bind [二维码内容]

将此QQ号绑定玩家UserID 负责解禁小黑屋

如出现绑定失败等问题 请检查玩家二维码内容是否正确 或重新获取一份

> 调用例子: .mai xhw bind SGWCMAID****

> 返回对应提示

#### .mai xhw logout 或 .xhw

解禁小黑屋 向华立服务器发送登出请求

如未绑定玩家UID则返回绑定教程 不做处理

上述两个命令均可调用

> 调用例子: .mai xhw logout 或 .xhw

> 返回对应提示

#### .mai xhw unbind

解绑小黑屋

在此QQ已绑定小黑屋UID的前提下 解绑小黑屋

> 调用例子: .mai xhw unbind

> 返回对应提示

### 查分器更新器

#### .mai cfq 

查看查分器更新器菜单

> 调用例子: .mai cfq

> 返回对应提示

#### .mai cfq bind user [查分器账户]

绑定 [水鱼查分器](https://www.diving-fish.com/maimaidx/prober/) 账号

账号请自行注册

> 调用例子: .mai cfq bind user cookie114514

> 返回对应提示

#### .mai cfq bind pwd [查分器密码]

绑定 [水鱼查分器](https://www.diving-fish.com/maimaidx/prober/) 密码

> 调用例子: .mai cfq bind pwd 114514

> 返回对应提示

#### .mai cfq bind fd [MaiMaiDX好友代码]

此好友代码需在 舞萌|中二 公众号中获取

> 调用例子: .mai cfq bind fd 114514

> 返回对应提示

#### .mai cfq sync

同步查分器 调用之后请自行前往 舞萌|中二 公众号中通过BOT好友申请

通过公众号内好友PK功能获取游玩数据 并更新查分器

> 调用例子: .mai cfq sync

> 返回对应提示

#### .mai cfq unbind

解绑查分器

> 调用例子: .mai cfq unbind

> 返回对应提示

### 排卡

#### .mai pk

获取 广州白云 机厅排卡信息

目前仅支持白云区机厅排卡信息查询 如有需要可小窗BOT主添加机厅 全自动更新

支持的机厅查询有：

- 百信
- 黄边
- 同和
- 嘉禾

> 调用例子: .mai pk

> 返回机厅排卡信息

### 网络状态查询

#### .mai status

获取 舞萌DX-CN 网络状态

> 调用例子: .mai status

> 返回对应状态提示

### BEST50查询

#### .mai b50

查询舞萌DX BEST50成绩图

数据来源于水鱼查分器 可使用BOT的查分器更新器更新

支持在命令后面@群友或加上水鱼查分器用户名 来查询其他人的BEST50

> 调用例子: .mai b50 / .mai b50 @澪度 / .mai b50 lingdu

> 返回BEST50成绩图

### 更新日志查看

#### .bot update

查看BOT更新日志

> 调用例子: .bot update

> 返回更新日志