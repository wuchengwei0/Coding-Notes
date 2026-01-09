# Markdown语法
## 1 段落
在 Markdown 中创建段落时，使用空行分隔文本块。每个用空行分隔的文本块都被视为一个独立的段落。
```markdown
This is a paragraph.

This is another paragraph.
```
This is a paragraph.

This is another paragraph.

在文本行之间添加空行会创建不同的段落。这是 Markdown 的默认行为。
> [!IMPORTANT]- 多个空白处(空格/回车)
> 段落内和段落之间的多个相邻空白会合并成一个空白
> ```markdown
> Multiple          adjacent          spaces
>
>
>
> and multiple newlines between paragraphs.
>```
>Multiple          adjacent          spaces
>
>
>
> and multiple newlines between paragraphs.
> <font color=red>如果想防止空格重叠或添加多个空格，可以使用 &nbsp;（不间断空格）或 `<br>`（换行符）HTML 标签</font>
## 2 换行
在 Markdown 中，默认情况下，按一次 Enter 键会在笔记中创建新行，但在渲染输出中，这会被视为同一段落的延续。要在段落内插入换行符而不另起一段，可以：
- 在按 Enter 键之前，在行尾添加两个空格

> [!QUESTION] 
> Contents


  
74

为什么在阅读视图中多次按下回车键不会产生更多换行符？