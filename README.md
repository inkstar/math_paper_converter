# 数学试卷格式转换器

这是一个自动将高中数学试卷转换为格式优美的 Markdown、LaTeX 和 PDF 格式的工具。

## 功能特点

- 支持多种输入格式（PDF、Word、图片）
- 自动识别数学公式和特殊符号
- 输出格式优美的 Markdown 文件
- 输出专业的 LaTeX 文件
- 生成高质量的 PDF 文档
- 支持自定义模板

## 安装要求

1. Python 3.8 或更高版本
2. 安装 Tesseract OCR 引擎：
   - macOS: `brew install tesseract`
   - Linux: `sudo apt-get install tesseract-ocr`
3. 安装 LaTeX 环境：
   - macOS: 安装 MacTeX
   - Linux: 安装 TexLive

## 安装步骤

1. 克隆仓库：
   ```bash
   git clone [repository-url]
   cd math_paper_converter
   ```

2. 安装依赖：
   ```bash
   pip install -r requirements.txt
   ```

## 使用方法

1. 将需要转换的试卷文件放入 `input` 目录
2. 运行转换脚本：
   ```bash
   python src/converter.py
   ```
3. 转换后的文件将保存在 `output` 目录中

## 目录结构

```
math_paper_converter/
├── src/           # 源代码
├── input/         # 输入文件目录
├── output/        # 输出文件目录
├── templates/     # 模板文件
└── requirements.txt
```

## 自定义模板

您可以在 `templates` 目录中创建自定义的 Markdown 和 LaTeX 模板。

## 许可证

MIT License 