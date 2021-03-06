# 功能列表（web 模式）

::: tip

功能表会随版本变化，请以自己机器人的帮助页面为准（发送“帮助”获取）

:::

此页指令不需要 at 机器人  
(权)标记表示功能需要权限  
(自动)标记表示无需触发词，机器人主动推送  
(后台)标记表示这个功能只能在后台使用  
方括号表示参数可以省略

## 系统类

| 关键词  | 说明              |
| ------- | ----------------- |
| 登录    | 登录进入 Web 模式 |
| 重置密码 | 随机重置一个新密码 |
| 更新    | (权)更新机器人    |
| 重启    | (权)重新启动机器人 |
| 退出此群 | (权)命令机器人退出当前群聊 |
| version | 查看机器人版本    |
| 帮助    | 查看帮助          |

## 公会战类

| 关键词                 | 说明                                                     |
| ---------------------- | -------------------------------------------------------- |
| 手册                   | 查看公会战使用手册                                         |
| 面板                   | 进入公会战面板                                           |
| 创建日服公会           |                                                          |
| 加入公会 \[@某人\]     | 加入到公会名单，如果有 at 则为加入他人                   |
| 加入全部成员           |                                                          |
| 报刀2000000 \[@某人\] \[昨日\] \[:留言\] | 对boss造成伤害但未击败时用，记录伤害，可以使用 200w/200万/2000k 等，如果有at则为代报，如果有“昨日”则将记录添加到前一天 |
| 尾刀 \[@某人\] \[昨日\] \[:留言\] | 对 boss 造成伤害并击败时用，记录伤害，如果有 at 则为代报，如果有“昨日”则将记录添加到前一天 |
| SL \[？\]              | 挑战 boss 强制取消后用，记录本日 SL，用“？”查询今日是否已 SL  |
| 撤销                   | 撤销上一次报刀（非管理员只能撤销自己的记录）             |
| 状态                   | 显示 boss 状态                                           |
| 预约1 \[:留言\]        | 预约 boss，当 boss 出现时通知                            |
| 挂树 \[:留言\]          | 挂树，当 boss 被击败时通知                               |
| 查1 / 查树             | 查询预约 boss 的成员，查询挂树的成员                     |
| 取消预约1 / 取消1       | 取消预约                                                 |
| 申请出刀                | 锁定 boss，提醒后面的人有人正在挑战 boss                |
| 锁定:留言               | 锁定 boss，提醒后面的人暂停出刀，冒号后为留言           |
| 解锁                   | 解锁 boss，其他人可以继续申请                           |
| (后台：出刀表)          | 查看所有成员当时出刀情况与SL情况，也可以查看过去的出刀信息 |
| (后台：催刀)           | at并提醒所有未完成出刀的成员                              |
| (后台：尾刀信息)        | 查看所有有剩余刀的成员的上一次尾刀信息                      |
| (后台：修改boss状态)    | boss数据与实际情况不一致时进行修改                       |
| (后台：重置数据)        | 两次公会战之间使用，删除所有出刀、预约数据                 |

## 查询类

| 关键词                            | 说明           |
| --------------------------------- | -------------- |
| jjc查询 +5个角色名空格分隔         | 查找竞技场解法，指定区服可改用“jjc国服/jjc台服/jjc日服” |
| (自动：新闻推送)                  | 推送最新的新闻 |
| 日程(今日/明日/x月x日)(可自动)     | 查看活动日程   |
| 日程表                            | 查看一周日程   |
| 挖矿计算 +当前名次                 | 计算剩余可获得的奖励钻石 |

## 娱乐类

| 关键词                          | 说明                                     |
| ------------------------------- | ---------------------------------------- |
| 十连                            | 模拟抽卡                                 |
| 仓库\[@某人\[@某人\[…\]\]\]     | 查看抽到过的所有角色查看他人抽到过的角色 |
| 在线十连                        | 在线抽卡，不扰民                        |
| 人偶                            | (权:主人)人偶功能                         |
