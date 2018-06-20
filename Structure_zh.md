# 先打个草稿

## OJ结构

我们希望这个OJ有超常的扩展性，于是决定将OJ分为若干个部分，并且将每部分列举如下。

| repository     | 功能           |
| -------------- | ------------- |
| WebApplication | 前端静态网站部分 |
| AppController  | 主要逻辑控制部分 |
| TaskReceiver   | 评测任务处理部分 |
| JudgeCore      | 实际代码评测部分 |

并且我们决定使用消息队列分离每个Repo。

<简体中文>
