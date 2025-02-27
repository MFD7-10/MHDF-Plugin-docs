---
description: 了解梦之工具中的命令与权限
---

# 命令
| 命令          | 权限                               | 默认持有 | 介绍                   |
| ------------- | ---------------------------------- | -------- | ---------------------- |
| crash         | mhdftools.commands.crash           | op       | 崩溃玩家客户端         |
| knockback(kb) | mhdftools.commands.knockback       | op       | 击退玩家               |
| list          | mhdftools.commands.list            | op       | 查看在线列表           |
| fly           | mhdtools.commands.fly              | op       | 飞行                   |
| -             | mhdtools.commands.fly.infinite     | op       | 无限时长飞行           |
| -             | mhdtools.commands.fly.give         | op       | 给予飞行               |
| flytime       | mhdtools.commands.flytime          | op       | 限时飞行               |
| vanish        | mhdtools.commands.vanish           | op       | 隐身                   |
| -             | mhdtools.commands.vanish.give      | op       | 给予隐身               |
| stop          | mhdtools.commandsstop              | op       | 更好的关服             |
| tpa           | mhdtools.commands.tpa              | 玩家     | 传送到玩家             |
| tpahere       | mhdtools.commands.tpahere          | 玩家     | 传送玩家过来           |
| menu          | mhdtools.commands.menu             | op       | 打开自定义菜单         |
| home          | mhdtools.commands.home             | 玩家     | 返回家                 |
| sethome       | mhdtools.commands.sethome          | 玩家     | 设置家                 |
| -             | mhdftools.commands.home.max.<数量> | 无       | 设置最大家数量为<数量> |
| delhome       | mhdtools.commands.delhome          | 玩家     | 删除家                 |
| back          | mhdtools.commands.back             | 玩家     | 返回死亡点             |
| tpback        | mhdtools.commands.tpback           | 玩家     | 返回传送前的位置       |
| spawn         | mhdtools.commands.spawn            | 玩家     | 返回出生点             |
| setspawn      | mhdtools.commands.setspawn         | op       | 设置出生点             |
| nick          | mhdtools.commands.nick             | op       | 设置匿名               |
| ip(ipinfo)    | mhdtools.commands.ip               | op       | 查询IP信息             |
| gamemode(gm)  | mhdtools.commands.gamemode         | op       | 设置自己的游戏模式     |
| -             | mhdtools.commands.gamemode.give    | op       | 设置其他人的游戏模式   |
| bed           | mhdtools.commands.bed              | 玩家     | 回到床的位置           |
| suicide       | mhdtools.commands.suicide          | op       | 自杀                   |
| hat           | mhdtools.commands.hat              | 玩家     | 帽子                   |
| warp          | mhdtools.commands.warp             | 玩家     | 返回传送点             |
| setwarp       | mhdtools.commands.setwarp          | op       | 设置传送点             |
| delwarp       | mhdtools.commands.delwarp          | op       | 删除传送点             |
| money         | mhdtools.commands.money            | 玩家     | 查询自己余额           |
| -             | mhdtools.commands.money.other      | op       | 查询别人余额           |
| moneyadmin    | mhdtools.commands.moneyadmin       | op       | 经济管理               |
| pay           | mhdtools.commands.pay              | 玩家     | 转账                   |
| -             | mhdftools.group.chatcolor.<组ID>   | 无       | 使用<组>的颜色符号     |
| -             | mhdftools.group.joinmessage.<组ID> | 无       | 使用<组>的进服消息     |
| -             | mhdftools.group.quitmessage.<组ID> | 无       | 使用<组>的退服消息     |