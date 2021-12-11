---
title: "Test File"
subtitle: "this is a subtitle"
date: \today
numbersections: true
abstract: |
    This is the abstract. It consists the basic overview of the document and as far this document this concerned, I am trying to create a single markdown document containing all the possible tools or stuff that I might need to create a basic academic document in the future. I still feel more comfortable in LaTeX. But I think, if I write two or three documents, then I might become more comfortable in it. I do realise that it will be sensible and perhaps more efficient to create CV and also beamer presentations in markdown rather than using LaTeX. Also I clearly don't need RMarkdown as vanilla Markdown is in itself pretty good and there is no real need to get RMarkdown whose only real advantage according to me is that it has a built in tool to build the PDF for you, but I don't need that as I have Pandoc. xD
bibliography: "references.bib"
nocite: '@*'
link-citations: true
urlcolor: "blue"
csl: "https://raw.githubusercontent.com/citation-style-language/styles/master/american-meteorological-society.csl"
---

# Introduction

Neque aliquid perspiciatis cumque nam qui molestiae. Sit quia voluptatem est. Eaque facere impedit assumenda atque est ut maxime ut. Dolores et omnis vitae quis dicta deserunt. Distinctio eius ut error. Ut dolores explicabo voluptatem eligendi.

Omnis ut mollitia ex ipsa. Nihil fuga aspernatur molestias debitis est voluptates esse dolore. Rerum neque est quis voluptatibus voluptatem accusantium sint. Et voluptatem nobis ea. Laborum ea vel sint modi.

Et voluptatum ut illo cum enim reiciendis ab totam. Nulla repudiandae quia ea tempora amet ea. Expedita ut voluptates perferendis. Qui est sapiente iure. Dolores iste placeat neque illum omnis. Quis veritatis temporibus quis aut vel optio labore.

# Image
![Description \label{fig:1}](http://via.placeholder.com/800x400){height=300px width=300px}

Seen in figure \ref{fig:1}, lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. [@online]

# Equation
Cauchy's integral formula [@dixon1971brief]

$$
f(a)=\frac{1}{2\pi i}\oint_γ\frac{f(z)}{z-a}\,dz.
\tag{1}
\label{eq:1}
$$

As seen in equation $\eqref{eq:1}$, duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

# Source Code
Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

```python
def foo():
    return "bar"
```

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

# Table

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

Table: Table styles. \label{tab:1}

Seen in table \ref{tab:1}, Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

# References
