## 感兴趣的一些接口
波动率
宏观杠杆率
社会融资规模增量统计
m2
新增信贷数据
公募基金
A股市盈率和市净率
交易日历
**A股龙虎榜**
社会消费品零售总额
FR007历史数据
**上海融资融券汇总
**深圳融资融券
乘联会 新能源
股东户数
指数估值 hist_funddb
*同花顺技术选股 创新高 创新低
财新指数 pmi
东财 个股人气榜
中国宏观 手机出货量 费城半导体
雪球 股票热度
东方财富-新股
A+H股票字典（股票名称和代码）
东财 新增投资者
沪深总市值
赚钱效应分析
**金十数据4小时新闻
**指定个股新闻

## 具体接口应用
### 股票市场总貌 上海&深圳
需要的是：
1. 总市值
2. 上市股票数量

`stock_sse_summary_df = ak.stock.sse_summary()`
`stock_szse_summary_df = ak.stock_szse_summary(date="20220610")`

### 沪深300 市盈率
