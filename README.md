# pdf-text-cleaner
An AI-assisted PDF text cleaning tool for academic document processing.
# AI PDF Text Cleaner

一个面向学术论文场景的 PDF 文本净化工具，利用 AI 能力自动提取、清理和优化 PDF 文本，帮助用户快速获得结构清晰、可阅读、可进一步处理的纯文本内容。

## 项目背景

在阅读学术论文、研究报告等 PDF 文档时，直接复制文本往往会遇到大量格式噪音，例如：

* 页眉、页脚重复内容
* 页码干扰
* 多栏排版导致的文本错序
* 无意义的换行和空格
* PDF 转文本后的格式混乱

本项目希望通过自动化文本处理流程，提高论文阅读、整理和信息提取效率。

## 核心功能

### 1. PDF 文本提取

支持从 PDF 文件中提取原始文本内容，为后续处理提供基础数据。

### 2. 智能文本清理

自动识别并处理：

* 重复页眉页脚
* 多余空行
* 异常换行
* 无效字符
* 格式噪音

### 3. 文本结构优化

对清理后的文本进行重新组织，提高阅读体验，方便后续：

* 文献阅读
* 笔记整理
* AI 总结
* 知识管理

### 4. AI 辅助处理

结合大语言模型能力，对复杂文本场景进行进一步理解和优化。

## 技术栈

* Python
* PDF 文本解析工具
* Large Language Model (LLM)
* 文本处理算法

## 项目结构

```
AI-PDF-Text-Cleaner
│
├── app.py                  # 主程序
├── requirements.txt        # 项目依赖
├── README.md               # 项目说明
└── demo/                   # 示例文件或截图
```

## 使用方法

### 1. 安装依赖

```bash
pip install -r requirements.txt
```

### 2. 启动项目

```bash
python app.py
```

### 3. 上传 PDF 文件

选择需要处理的论文 PDF，系统将自动完成文本提取与清理。

## Demo

<img width="1065" height="787" alt="image" src="https://github.com/user-attachments/assets/0a35b5c1-5738-4ba9-a603-871b63201f7e" />
<img width="1019" height="771" alt="image" src="https://github.com/user-attachments/assets/56062479-e823-4efe-ad24-42b9219b0ad0" />


## 项目亮点

* 针对真实学术阅读场景设计，而非简单 PDF 转文本工具
* 将 AI 能力应用于文献处理流程，提高信息获取效率
* 关注用户体验，降低论文整理成本

## Future Improvements

未来计划增加：

* 自动生成论文摘要
* 论文知识图谱构建
* 多文档批量处理
* 文献引用关系分析

## Author

Created by [Dijing]
