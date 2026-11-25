# 20261125红旗小学四年级计算测试

试卷共 13 题，题目版和答案版各为 A4 单页。答案版包含竖式、脱式计算及带 ※ 题的验算。两道除法的验算分别列出乘法竖式和加法竖式。

| 内容 | PDF | LaTeX 源码 |
| --- | --- | --- |
| 题目版 | [打印版](四年级计算-题目版.pdf) | [源码](四年级计算-题目版.tex) |
| 答案版 | [打印版](四年级计算-答案版.pdf) | [源码](四年级计算-答案版.tex) |

[原始题目照片](原始题目照片.jpg)

## 编译

安装 XeLaTeX、思源宋体简体版（Noto Serif CJK SC）及 Latin Modern 字体。TeX 需要 `geometry`、`amsmath`、`fontspec`、`unicode-math` 和 `pgf`（TikZ）。

```sh
xelatex -interaction=nonstopmode -halt-on-error 四年级计算-题目版.tex
xelatex -interaction=nonstopmode -halt-on-error 四年级计算-答案版.tex
```
