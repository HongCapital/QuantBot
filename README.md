# QuantBot
This is a crypto monitor & Quantitative Decision Trading bot

# ToDo List

Version 1.0
    实现对Binance的数据采集(存储到mysql 中),数据类型为:trade, aggtrade, depth, kline (btcusdt, ethusdt 交易对)
    实现简单的分析,R值统计, 大单成交提醒
    实现 telegram bot 的消息发送接收，消息推送，
        telegram bot commond:
            /start, /help, /subscribe, /unsubscribe, /list

Version 1.1
    增加交易对的选择，增加对多个交易对的监控
    着重交易策略的开发(统计策略)
    优化 telegram bot的消息发送,实现交易策略订阅


Version 1.2
    增加对huobi,okex,xeggex 等交易所的监控
    着重交易策略的开发(AI策略)

Version 2
    代码重构（解耦），将代码分为多个模块，分别为：数据存储，数据分析，消息发送，交易策略
    增加API 交易


Version 3
    增加对opense,blur 等nft 交易所监控    

