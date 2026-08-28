# Overleaf 使用说明

本文件夹可整体上传到 Overleaf，包含：

- 21 个可独立编译的 `figure-*.tex`
- `figure_preamble.tex`：文档类、中文支持及 TikZ/PGFPlots 依赖
- `figure_style.tex`：统一浅蓝色绘图样式

## 编译设置

在 Overleaf 的 **Menu / Settings** 中将编译器设置为 **XeLaTeX**。

需要编译某一幅图时，将对应的 `figure-*.tex` 设置为主文档。例如：

```text
figure-autoencoder.tex
```

所有文件必须保持在同一目录，因为每幅图通过以下命令载入公共配置：

```latex
\input{figure_preamble.tex}
```

而 `figure_preamble.tex` 会继续载入：

```latex
\input{figure_style.tex}
```
