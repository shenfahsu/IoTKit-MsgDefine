# 预定义消息概述

## 一、全局配置类定义 RID_BEGIN_CFG = 0

|id     |描述                  |数据类型    |  
|-------|-------------------|----------|
| +1     | RelayServer配置      | string     |
| +2     | MsgServer配置        | string     | 
| +3     | CidOSSConfig配置     | string     | 
| +4     | ClientOSSConfig配置  | string     | 



## 二、局域网消息定义 RID_BEGIN_UDP = 100


## 三、开放功能定义表格 RID_BEGIN_OPEN = 200

| id     |描述       |是否唯一   |数据类型    |APP可见    |显示/控制     |是否有返回值   | 是否展示图表    | APP多终端是否需要同步 | 是否推送消息到APP端 |
|-------|----------|----------|----------|----------|------------ |---------|---------|------|------|
| +1     | 网络类型  | 否        | string     | 是        | 显示         | 无      |无       | 否 | 是 |
| +2     | MAC地址   | 是        | string     | 是        | 显示         | 无      |无       | 否 | 否 |
| +3     | SD卡信息  | 否        | string     | 是        | 显示         | 无      |无       | 否 | 是 |
| +4     | 剩余电量  | 否        | int        | 是        | 显示         | 无      |无       | 否 | 是 |
| +5     | 版本号    | 否        | string     | 是        | 显示         | 无      |无       | 否 | 是 |
| +6     | 系统版本号| 否        | string     | 是        | 显示         | 无      |无       | 否 | 是 |
| +7     | 报警配置  | 否        | string     | 是        | 控制         | 是     |无       | 是 | 否 |
| +8     | 报警消息  | 否        | string     | 是        | 显示         | 无      |有       | 否 | 是 |
| +9     | 控制设备麦克风 | 否   | bool       | 是        | 控制         | 无      |无       | 否 | 否 |
| +10    | 控制设备喇叭   | 否   | bool       | 是        | 控制         | 无      |无       | 否 | 否 |
| +11    | 设备画面翻转   | 否   | int        | 是        | 控制         | 无      |无       | 否 | 否 |
| +12    | 门铃呼叫状态   | 否   | string     | 是        | 显示         | 无      |有       | 否 | 否 |
| +13    | 设备上报日志消息 | 否 | string     | 否        | 控制         | 无      |无       | 否 | 否 |
| +14    | 开机时间         | 否 | int        | 是        | 显示         | 无      |无       | 否 | 否 |
| +15    | 设置设备名称     | 否 | string      | 是        | 显示         | 有      |无       | 是 | 否 |
| +16    | 提交WIFI信息     | 否 | string     | 否        | 显示         | 无      |无       | 否 | 否 |
| +17    | 门铃留言设置     | 否 | string     | 是        | 控制         | 有      |无       | 是 | 否 |
| +18    | 延迟摄影设置     | 否 | string     | 是        | 控制         | 有      |无       | 是 | 否 |
| +19    | 摄像头待机设置   | 否 | bool        | 是        | 控制         | 有      |无       | 是 | 否 |
| +20    | 门磁消息通知开关设置| 否 | bool      | 是        | 控制         | 有      |无       | 是 | 否 |
| +21    | 每日精彩消息     | 否 | string     | 是        | 显示         | 无      |无       | 否 | 否 |
| +22    | 好友备注         | 否 | string     | 是        | 显示         | 有      |无       | 是 | 否 |


