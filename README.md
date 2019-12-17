# The Server part in Mahjong Game of OOAD Project

## 介绍
- 一个使用Python搭建的，利用Socket通讯，应用于课程面向对象设计基础Project麻将游戏的简易服务器
- 主要逻辑判断均在该服务器上进行，并且使用状态模式更新游戏进度
- 前端链接: [SUSTechMahjong](https://github.com/Pino444/SUSTechMahjong)

## 环境
- Python 3.7
- Windows/Linux/MacOS

## 运行
- 命令提示符/终端 输入 *python3 server.py* 即可运行

## 工程主体文件:
    [GitStates.py](https://github.com/DiogerChen/OOAD_Project/blob/master/GameStates.py)
    [Logic.py](https://github.com/DiogerChen/OOAD_Project/blob/master/Logic.py)
    [Room.py](https://github.com/DiogerChen/OOAD_Project/blob/master/Room.py)
    [server.py](https://github.com/DiogerChen/OOAD_Project/blob/master/server.py)
    [User.py](https://github.com/DiogerChen/OOAD_Project/blob/master/User.py)

## 服务器端实现清单
 - [x] 房间的创建，加入，以及房间内人员情况(准备，离开)的实时更新
 - [x] 导师选择环节
 - [x] 积分选课环节
 - [ ] 正常打牌环节(等待测试)
 - [x] 创建日志文件，记录服务器与客户端之间通讯内容以便于Debug
 - [ ] 优化代码结构
