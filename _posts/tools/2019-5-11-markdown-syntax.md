---
layout: post
permalink: markdown-syntax.html
---

It's very easy to make some words **bold** and other words *italic* with markdown. You can even [link to Baidu!](http://www.baidu.com)

```
It's very easy to make some words **bold** and other words *italic* with markdown. You can even [link to Baidu!](http://www.baidu.com)
```

---

Sometimes you want numbered lists:

1. Item 1
    1. one
    2. two
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b

Sometimes you want bullet points:

* one
    - one
    - two
* two

```
Sometimes you want numbered lists:

1. Item 1
    1. one
    2. two
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b

Sometimes you want bullet points:

* one
    - one
    - two
* two

```
---

If you want to embed images, this is how you do it:

![Image of yakatocat](https://octodex.github.com/images/yaktocat.png)

```
![Image of yakatocat](https://octodex.github.com/images/yaktocat.png)
```
---

# first-tier heading

## second-tier heading

### This is a third-tier heading

You can use one `#` all the way up to `######` six for different heading sizes.

If you'd like to quote someone, use the > character before the line:

> I love Python and Java

```
# first-tier heading

## second-tier heading

### This is a third-tier heading

You can use one `#` all the way up to `######` six for different heading sizes.

If you'd like to quote someone, use the > character before the line:

> I love Python and Java
```
---

# Mention
@luke-cao

```
@luke-cao
```
---
# Task lists
- [x] This is a complete item
- [ ] This is an incomplete item

```
- [x] This is a complete item
- [ ] This is an incomplete item
```
---

# Code Snippets
There are many different ways to style code with GitHub's markdown. If you have inline code blocks, wrap them in backticks: `var example = true`.  If you've got a longer block of code, you can indent with four spaces:

    if (isAwesome){
      return true
    }

or use triple backticks without spaces

```python
import numpy as np

x = np.array([1, 2, 3, 4])
```

```
There are many different ways to style code with GitHub's markdown. If you have inline code blocks, wrap them in backticks: `var example = true`.  If you've got a longer block of code, you can indent with four spaces:

    if (isAwesome){
      return true
    }

or use triple backticks without spaces

triple backticks
import numpy as np

x = np.array([1, 2, 3, 4])
triple backticks
```
