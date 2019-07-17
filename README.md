# Policr Bot [![Build Status](https://github-ci.bluerain.io/api/badges/Hentioe/policr/status.svg)](https://github-ci.bluerain.io/Hentioe/policr)

大概是 Telegram 平台最强大的审核机器人

## 介绍

本项目的设计原则是定制、专注和私有部署。核心审核功能完备且复杂，能应对各种意外情况，还有人性化的验证容错设计。

专注体现在不做不相干的功能，定制体现在提供友好的设置菜单和众多的可选项，并支持多种验证方式（之所以称之为最强大，这也是核心原因。如果不是，请打醒）。

**注意**：无论是官网还是本页面都可能是过时的，想知道最新功能请关注更新频道。

### 功能概括

#### 构成审核的四大子功能

1. 新入群用户验证（支持六种方式）
1. 封杀清真名称和发表清真消息的用户
1. 自动限制普通成员新拉入的机器人
1. 黑名单系统：举报、投票和预先封禁

#### 附带的周边小功能

1. 调查通过验证用户的来源
1. 给通过验证用户发送欢迎消息

#### 强大的定制能力

1. 定制审核子功能启用状态
1. 定制周边功能启用状态
1. 定制各种痕迹消息的删除以及延迟时间
1. 定制验证方式
1. 自定义验证问题
1. 定制验证倒计时时长

#### 自由、安全而开放

1. 可启用容许错误的验证机制
1. 基于被信任管理员的机器人调整权
1. 所有用户皆可举报违规消息
1. 自助申请投票权（暂未开放）

额外特殊说明：

1. 本项目（永远）不会支持验证码，因为我们提供了更加高级而友好的验证方式（[这里有详细原因](https://policr.bluerain.io#verification_code)）
1. 黑名单系统不仅是自由开关的，其透明开放的设计也是保证公信力的前提。毕竟已经有一些被质疑黑箱操作的机制简单的黑名单机器人作为前车之鉴：）

### 开发技术

得益于原生语言 Crystal 的优势，机器人实例能以极低的成本高效率执行。编译完成后的二进制只有区区 4.9MB 大小，内存占用不超过 10MB，在保持低资源占用的同时能处理超高并发量的消息。

不同于很多使用 Python 编写的将处理逻辑都集中于一个文件的简单机器人，此项目源码有清晰的文件结构和良好的消息处理单元抽象，具备很高的扩展性和可维护性。能在不侵入已有功能代码的情况下进行扩展和定制。

## 使用&部署

**相关说明已经全部迁移到官网首页**，请访问[这里](https://policr.bluerain.io)。

## 加入我们

- [POLICR · 中文社区](https://policr.bluerain.io/community)
- [POLICR · 更新通知](https://t.me/policr_changelog)
