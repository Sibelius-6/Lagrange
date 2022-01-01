---
title: Nicematrix
tags: [basic]
author: Cameron
---

One can use nice matrix to draw annotated matrix with ease:

```latex
\[ 
    P=\begin{bNiceArray}{cccc|cccc}[first-row,first-col]
        & 0              & 1 & \cdots & M-1 & M              & M+1 & \cdots & N \\
        0 & \Block{4-4}{Q} &   &        &     & \Block{4-4}{R}                    \\
        1                                                                         \\
        \vdots                                                                    \\
        M-1                                                                       \\
        \midrule
        M & \Block{4-4}{0} &   &        &     & \Block{4-4}{I}                    \\
        M+1                                                                       \\
        \vdots                                                                    \\
        N
    \end{bNiceArray}, 
\]
```

The result

![](/attach/nicematrix.png)

Credit to [Cameron](https://hextical.github.io/)