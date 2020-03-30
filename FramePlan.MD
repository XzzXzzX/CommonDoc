# 自习计划  

1. 网络模块
    - 各个回调  
        - 连接 onConnect
            - 重联
        - 连接错误 onConnectError
            - 重联
        - 连接中断 onDisconnect
            - 重联
        - 消息处理 onMessage
            - 分帧处理回调，每帧处理N条消息

    - 重联处理， 尝试N次连接，都没有连接上，则放弃连接，无法连接服务器。

    - 添加、删除消息监听

    - 消息发送

2. ui管理
    - ui分层
        - tips
        - top
        -
    - 显示、关闭界面
