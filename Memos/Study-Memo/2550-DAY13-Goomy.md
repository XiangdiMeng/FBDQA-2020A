量化策略的研发关键环节

策略建模->追溯测试->调试修正

体系化研发的关键环节

策略逻辑
模型构建
模型调试
交易执行
策略调试层面：逻辑是否可靠

纠正心理偏差
缓跌：自我确认偏差；避免深套
缓涨：保守偏差；避免错失机会
急涨：损失厌恶偏差；避免后悔偏差；避免持股不牢
急跌：心锚，固定和调整偏差，代表性偏差；避免抢反弹
案例

买入
KD金叉
RSI在(40,70)
K线上穿10日均线
卖出条件
K线下穿20日均线
仓位：总资金80%
标的：50ETF
量化策略的迭代式开发

信号系统
退出方式
资金管理
分散化
峰谷交易系统

正态性检验

金融模型要求对数收益率呈正态分布，正态性检验

图形化方法：频率直方图；分位图；分位数图
定量：偏度；峰度；假设检验
投资组合优化-寻找收益和风险的平衡点

偏度：检验了对称的程度
峰度：表现了尖锐的程度
计算收益，风险，夏普比率
MPT理论：投资组合理论
投资组合理论——有效边界的获取
有效边界：给定风险水平下最大化收益的投资组合构成的集合
约束最优化问题 scipy.optimize
最大化夏普；最小化方差；给定收益下最小化方差
加入无风险资产
资本市场线