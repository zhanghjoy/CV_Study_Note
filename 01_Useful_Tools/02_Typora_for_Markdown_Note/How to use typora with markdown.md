# Markdown Study Note

## 1.多级标题

```cc
//1.选中文本 Ctrl+1/2/3/4/5/6......
//2.#空格加标题文本 n个#代表n级别标题
# Markdown Study Note
## 1.多级标题
```

## 2.字体样式

> Note:主要涉及对字体的加粗、斜体、删除线、字号、字体、颜色和背景色

*文本* 

_文本_  

**文本**

***文本***

\*文本\*

``` c
*文本* //一个*斜体
_文本_
**文本**//两个*粗体
***文本*** //三个* 粗斜体
~~文本~~ //删除线
#符号与文本之间无空格 若要区分则用转义符反斜杠 \ + 需要转义的符号
\*文本*\
```

---

> 设置文本“Text”字体为 Times New Roman 颜色为绿色 文本大小6（1~7）

* 字体类型直接令  **face=' Times New Roman'** 即可

- 颜色可以直接输对应的英文或者输入16进制的RGB代码 所有绿色可以是green或者\#008000 **color=green/\#008000**
- 

[RGB颜色对照表](https://www.pctools.cc/zh-cn/rgb_color)

![rgb](https://raw.githubusercontent.com/Zhanghjoy/Typora_Note_Photo/main/202410120829131.png)

- 字体大小为**size=6**

```html
<font face='Times New Roman' color=green size=5>Text_Test</font>
```

<font face='Times New Roman' color=green size=6>Text_Test</font>

```html
#常见格式代码
#1英文文本/red/black
<font face='Times New Roman' color=green size=5>Text_Test</font>
#1中文文本 宋体/黑体
<font face='楷体' color=green size=5>Text_Test</font>
```







