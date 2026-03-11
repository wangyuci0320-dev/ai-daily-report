#ai-daily-report/
├── .github/workflows/daily-report.yml  # 定时工作流
├── src/
│   ├── collectors/
│   │   ├── stock_collector.py          # A股数据
│   │   ├── global_collector.py         # 全球市场
│   │   └── news_collector.py           # 新闻资讯
│   ├── generators/
│   │   └── report_generator.py         # HTML生成
│   ├── templates/
│   │   └── daily_report.html           # 卡片式模板
│   └── main.py                         # 主程序
├── config.yml                          # 配置文件
├── requirements.txt                    # 依赖
└── README.md
