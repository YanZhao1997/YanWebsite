---
date: "2019-03-20"
description: Katex support demo
katex: true
series:
- Theme
- Hugo
title: Render LaTeX using KaTeX
---

Enable katex by adding `katex = "true"` to the [front matter](https://gohugo.io/content-management/front-matter/)  

```toml
+++
katex = "true"
+++
```

It's almost a dropin alternative to the mathjax solution,you should just choose one of them.  

Inline math looks like this  

```tex
This is text with inline math $\sum_{n=1}^{\infty} 2^{-n} = 1$
```

This is text with inline math $\sum_{n=1}^{\infty} 2^{-n} = 1$  
and with math blocks:  

```tex
$$
\sum_{n=1}^{\infty} 2^{-n} = 1
$$
```

$$
\sum_{n=1}^{\infty} 2^{-n} = 1
$$