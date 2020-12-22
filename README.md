# game-message-protocol

游戏消息协议的 proto 定义文件

## 文件命名方式

用于传输的消息体存在的定义文件命名方式如下:

    game-{modelname}-message.proto;
    
为了保证文件结构可读性更好,
消息引用的其它结构体和常量数据定义文件命名方式:

    game-{modelname}-model.proto;

## 消息内容

1. [公共消息: game-common-message.proto](game-common-message.proto)

    包含一些全局结构和枚举,  业务状态定义

2. [玩家消息: game-player-message.proto](game-player-message.proto)

    包含玩家相关的操作消息和结构定义
    
3. [游戏消息: game-mahjong-message.proto](game-mahjong-message.proto)

    和游戏操作相关的消息, 目前主要是麻将
