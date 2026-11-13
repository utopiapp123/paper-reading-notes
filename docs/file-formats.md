# 文件格式与数学公式

[返回阅读首页](../README.md) · [书籍专区](../books/README.md)

**日常笔记用 `.md`；需要保留完整版式时，另附一份 PDF。** 两份文件可以并存：Markdown 便于检索、修改和链接，PDF 用于阅读与打印。

## 按用途选择

| 文件 | GitHub 中的阅读方式 | 适合保存什么 |
| --- | --- | --- |
| Markdown `.md` | 渲染标题、列表、表格、图片和数学公式 | 日常论文与书籍笔记，推荐作为主文件 |
| PDF `.pdf` | 文件页面可预览 | 固定字体、分页、页边距和复杂公式版式的成稿 |
| Jupyter `.ipynb` | 静态显示文字、代码及已保存的输出 | 带计算、数值实验和绘图的笔记；交互控件不会运行 |
| Word `.docx`、LaTeX `.tex` | 保留编辑源文件；另导出 PDF 作为阅读入口 | 需要继续在原编辑器中排版的源稿 |

GitHub 的 [Markdown 公式支持](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)使用 MathJax。PDF 和 Notebook 的预览方式参见[非代码文件说明](https://docs.github.com/en/repositories/working-with-files/using-files/working-with-non-code-files)。

## 可以直接复制的公式写法

行内公式的源文本：

```markdown
贝尔态的归一化系数是 $1/\sqrt{2}$。
```

渲染效果：贝尔态的归一化系数是 $1/\sqrt{2}$。

独立公式的源文本：

```markdown
$$
|\Phi^+\rangle=\frac{|00\rangle+|11\rangle}{\sqrt{2}}
$$
```

渲染效果：

$$
|\Phi^+\rangle=\frac{|00\rangle+|11\rangle}{\sqrt{2}}
$$

也可以使用 `math` 代码块：

````markdown
```math
E = mc^2
```
````

正文段落之间保留空行，独立公式上下也留空行。将公式保留为文本，后续更容易修改与检索。

## 怎样保留排版

Markdown 按 GitHub 的页面样式显示，适合清楚、统一的阅读笔记。自定义字体、字号、页边距或精确分页，应由排版工具导出到 PDF；GitHub 会清理 Markdown 中的自定义样式，参见 [GitHub Markup 的渲染流程](https://github.com/github/markup#github-markup)。

GitHub 的 PDF 预览目前会忽略 PDF 内部链接，因此关键原文和章节定位链接仍放在 Markdown 中。

## 在本仓库怎么放

```text
books/
  book-slug/
    README.md
    chapters/
      01-introduction.md
    assets/
      figure-01.png
exports/
  books/
    book-slug/
      reading-notes.pdf
```

以上是命名示例。实际新增书籍时再创建对应目录、章节和图片。

当前可直接上传和维护 `.md`。排版后的个人笔记 PDF 放到 `exports/`；该目录已允许提交 PDF。图片使用 PNG、JPG 或静态 SVG，并在笔记中通过相对路径引用。
