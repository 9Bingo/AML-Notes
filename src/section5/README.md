# 中文课程讲义 LaTeX 模板

主文件是 `aml_notes.tex`，建议使用 XeLaTeX 编译：

```powershell
xelatex aml_notes.tex
xelatex aml_notes.tex
```

第二次编译用于生成完整目录和交叉引用。图片可以放在 `figures/` 或 `images/` 目录中，然后用 `\includegraphics` 插入。

常用修改位置：

- 课程信息：修改 `\coursename`、`\semester`、`\teacher`、`\school`。
- 新增章节：使用 `\chapter{章节标题}`。
- 新增小节：使用 `\section{小节标题}` 或 `\subsection{小节标题}`。
- 插入表格：参考模板中的 `table` 和 `longtable` 示例。
- 插入图片：把图片放入 `figures/`，参考模板中的 `figure` 示例。

如果使用 Overleaf，也请选择 XeLaTeX 作为编译器。
