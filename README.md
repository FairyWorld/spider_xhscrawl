## 简介
小红书的api都有加密，主要就是x-s。本项目是用python逆向小红书x-s，小红书会定期更新加密的js，本项目会持续更新，欢迎star。


## changelog

| 版本     | 日期       | 其他                                   |
| ------ | -------- | ------------------------------------ |
| v00.01 | 2023.7.5 |                                      |
| v00.02 | 2023.8.1 | - 增加从cookie自动获取a1参<br/>  <br/>- 封装函数 |
|        |  2023.8.3 | - 增加一些工具函数                  |
|  v00.03      |  2023.8.9 | - 增加[发送评论](https://github.com/wang-zhiyang/xhscrawl/blob/main/service/comment.md)                   |
|  v00.04      |  2023.8.9 | - 增加[获取笔记详情](https://github.com/wang-zhiyang/xhscrawl/blob/main/service/note_detail.md)                   |
|        |  2023.8.10 | - 评论支持中文和@其他人                  |
|   v00.05     |  2023.8.10 | - 增加[笔记搜索](https://github.com/submato/xhscrawl/blob/main/service/search.md)                  |
|   v00.06     |  2023.9.2 | - 增加[获取笔记评论](https://github.com/submato/xhscrawl/blob/main/service/get_comment.md)                   |
|   v00.07     |  2023.9.14 | - 增加[收藏笔记](https://github.com/submato/xhscrawl/blob/main/service/collect_note.md) 、[给笔记点赞](https://github.com/submato/xhscrawl/blob/main/service/like_note.md)            |
| v01.00 | 2023.9.14 | - 代码重构、模块化、解耦  |

|    vXXX   |  正在开发中 | - 增加[自动发布笔记](https://github.com/submato/xhscrawl/blob/main/service/creat_note.md)                   |
|    vXXX    |  0000-00-00 | 如果没有你需要的接口,联系作者有偿定制开发                 |

## how to run
- python环境
  - execjs包
  - py_mini_racer 包
- java环境
- node js环境
- 找到demo/xhs.py，将自己需要的api、参数、cookie进行手动替换运行即可

## 效果
![image](https://github.com/wang-zhiyang/xhscrawl/assets/55040284/45c9d9cb-4017-4c47-81a5-2e896ca65ed7)

## 寻求帮助
  1. 联系作者，1v1有偿提供帮助：QQ ：1162466610
  2. 作者提供逆向单个api的源码，代码以最简单朴素的方式编写，每一个参数都有说明，保证能够跑起来
  3. 如果没有你需要的接口,联系作者有偿定制开发

## 提供的源码

| 名称    | 
| ------------------------------------ |
|[发送评论](https://github.com/wang-zhiyang/xhscrawl/blob/main/service/comment.md)                   |
| [获取笔记详情](https://github.com/wang-zhiyang/xhscrawl/blob/main/service/note_detail.md)    |
| [笔记搜索](https://github.com/submato/xhscrawl/blob/main/service/search.md)                  |
| [获取笔记评论](https://github.com/submato/xhscrawl/blob/main/service/get_comment.md)                  |
| [收藏笔记](https://github.com/submato/xhscrawl/blob/main/service/collect_note.md)                |
| [给笔记点赞](https://github.com/submato/xhscrawl/blob/main/service/like_note.md)               |



## 请作者喝咖啡吧
如果作者的仓库对你有帮助的话，请作者喝杯咖啡支持一下作者吧

<img title="" src="https://github.com/wang-zhiyang/xhscrawl/assets/55040284/89bb6534-5e74-44bb-b728-dc771fe9f2b1" alt="WechatIMG106" width="300">
