---
title:  "My first notebook"
author: "nosferatu"
date:   "1.10.19"
output:
  html_document:
    toc: true
    toc_float:
      collapsed: true
---

# Hello world {#header1}

Hola

**Here's some fat text**

*Here's some tilted text*

^superscript^ text here

~subscript~ text down here

`code` text here

~~strikethrough~~ deleted?

## Useful links {#header2}

[useful Rmarkdown files](http://rpubs.com/AM66/534228)

### Lists {#header3}
1. Collect underpants
    a. Blue ones (Note FOUR spaces exactly!!)
    b. Green ones
    c. Other colours
2. ...
3. Profit

* Uno
* Dos
* Tres

<!-- do not show this stuff on the report -->

# IMAGES

<!-- This is linking to images using HTML-->
<img src="img/ggplot2-violin-plot.png" width=200 />

<!-- This is linking to images in Rmarkdown-->
![This is the figure caption](img/ggplot2-violin-plot.png)

# Tables
| Column 1 | Column 2 |
|----------|----------|
| Boaty    | McBoatFace |

#### Other stuff {#header4}

you can find more information under [links](#header1)

blablablabla [^1]

[^1]: This is footer number one!! A little bit cumbersome.

# BLOCKS

```
print("Hello world")
x <- 1+ 2
```

# Unused

Hello, Website!

For more information about simple R Markdown websites, please read the documentation at https://bookdown.org/yihui/rmarkdown/rmarkdown-site.html.

Please also note that simple R Markdown sites are _not_ based on **blogdown**. They are probably good for websites with only a few Rmd documents. For larger-scale and more sophisticated websites (such as blogs), you may want to use **blogdown** instead: https://github.com/rstudio/blogdown.
