# 高级机器学习教材合订版

主文件是 `aml-notes.tex`，建议使用 XeLaTeX 编译：

```powershell
xelatex aml-notes.tex
bibtex aml-notes
xelatex aml-notes.tex
xelatex aml-notes.tex
```

章节内容分别位于 `section1` 至 `section5` 目录中，合订版通过 `aml-notes.tex` 统一引入各章正文、图片与参考文献。
