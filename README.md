# novel2video 小说分析系统

这是一个基于大语言模型的小说分析系统，提供小说文本的章节提取、人物关系分析、故事时间线生成等功能。通过交互式Gradio界面，用户可以直接上传小说文本或使用示例，对文本进行分析和可视化。

## 功能特性

- **章节识别与提取**：自动识别并提取小说的章节结构
- **章节模式管理**：添加、测试和验证章节标题模式
- **人物关系分析**：分析小说中的人物关系并可视化
- **故事时间线**：生成小说的关键事件时间线
- **交互式界面**：基于Gradio的用户友好界面

## 项目结构

```
.
├── gradio_app.py        # Gradio界面主程序
├── novel_processor.py   # 小说处理核心逻辑
├── text_analyzer.py     # 文本分析功能
├── pattern_validator.py # 模式验证工具
├── chapter_splitter.py  # 章节拆分工具
├── config.py            # 配置文件
├── .env                 # 环境变量配置
├── requirements.txt     # 项目依赖
├── patterns/            # 章节模式配置目录
│   └── chapter_patterns.json  # 章节模式配置文件
├── txt_books/           # 示例小说文本目录
│   └── 《小王子》.txt    # 示例小说
├── test_results/        # 分析结果输出目录
└── analysis_temp/       # 临时分析文件目录
```
