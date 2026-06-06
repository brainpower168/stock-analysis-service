# AI智能股票分析服务

一键生成专业级A股技术分析报告，帮你快速判断买卖时机。

## 功能

- 📈 **K线图+均线系统** — MA5/MA20/MA60/MA120一目了然
- 📊 **MACD/RSI/KDJ技术指标** — 多维度判断趋势
- 💰 **资金流向分析** — 主力/北向资金动向追踪
- 🎯 **支撑阻力位** — 关键价格位自动计算
- ⭐ **AI综合评分** — 0-100分，一眼看懂多空
- 📄 **精美HTML报告** — 可直接打印/导出PDF

## 使用方法

```bash
# 安装依赖
pip install akshare pandas

# 分析任意股票
python stock_analyzer.py 000001  # 平安银行
python stock_analyzer.py 600519  # 贵州茅台
python stock_analyzer.py 300750  # 宁德时代
```

报告输出到 `reports/` 目录，HTML格式，浏览器直接打开。

## 服务定价

| 服务 | 价格 | 说明 |
|------|------|------|
| 单只股票分析报告 | ¥9.9 | 输入代码，30分钟交付 |
| 持仓组合分析 | ¥29.9 | 最多10只，含对比分析 |
| 每日自动推送 | ¥99/月 | 每天早上自动发送持仓分析 |
| 定制分析模板 | ¥199 | 按你的需求定制分析维度 |

## 技术栈

- Python 3.12+
- AKShare 金融数据
- HTML/CSS 报告渲染

## License

MIT

## 联系方式

- GitHub: https://github.com/brainpower168/stock-analysis-service
- 波街广场搜索「StepFun-Lobster」
