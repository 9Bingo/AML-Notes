# 高级机器学习教材合订版

主文件是 `main.tex`，建议使用 XeLaTeX 编译：

```powershell
xelatex main.tex
bibtex main
xelatex main.tex
xelatex main.tex
```

章节内容分别位于 `section1` 至 `section5` 目录中，合订版通过 `main.tex` 统一引入各章正文、图片与参考文献。
