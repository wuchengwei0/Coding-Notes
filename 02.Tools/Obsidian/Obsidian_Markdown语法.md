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

> [!QUESTION]+ 为什么在阅读视图中多次按下回车键不会产生更多换行符？
> 在 Markdown 中，单个 Enter 键会被忽略，连续多次按下 Enter 键只会生成一个新的段落。这种行为符合 Markdown 的软换行规则，即多余的空行不会生成额外的换行符或段落，而是会被合并成一个段落分隔符。这是 Markdown 默认的文本处理方式，确保段落自然流畅，避免出现意外的断行。
> > [!QUESTION]+ 启用严格换行符(默认开启)
> > 1. 打开 `Setting`
> > 2. `编辑器` -> `严格换行`(开启后，根据Markdown标准，单个换行符在预览模式下不在生效)
> > 3. 打开 `Enable` 开关  
> > 
> > 在 Obsidian 中启用<font color=red>“严格换行”</font>后，换行符会根据换行方式的不同而呈现三种不同的行为：  
> > 1. **单回车符（无空格）**：渲染时，单回车符（无尾随空格）会将两行合并为一行。  
> > ```markdown
> > line one
> > 
> > line two
> > ```
> > 渲染结果如下：  
> > line one
> > line two    
> > 2. **单回车后跟两个或多个空格**：如果在第一行末尾添加两个或多个空格后再按 Enter 键，这两行仍然属于同一个段落，但会被换行符（HTML `<br>` 元素）分隔开。在本例中，我们将使用两个下划线来代替空格。
> > ```markdown
> > line three__  
> > line four
> > ```
> > 渲染结果如下：  
> > line three__  
> > line four  
> > 3. **双回车（带或不带尾随空格）**：按两次（或更多次）回车键会将行分隔成两个不同的段落（HTML `<p>` 元素），无论是否在第一行末尾添加空格。
> > ```markdown
> > line five
> > 1
> > 
> > ```
> 


## 31
123
123