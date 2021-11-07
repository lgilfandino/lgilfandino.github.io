---
layout: post
title: "Markdown explanation"
date: 2021-10-11
summary: "Many features of the markdown syntax are showcased here."
---



# Big title


Hello!! you can write emojis :rocket:. Also *italic text*, or even **bold text**. What about ***both at the same time??***. As Einstein once said,

> Don't believe any quote from the internet :angry:



## Smaller title

Details, like a list:

* This
* That


Or a numbered list:

1. One
2. Two

### Even smaller:

Also checkboxes:

- [x] Task 1
- [x] Task 2
- [ ] Task 3


---

# New Chapter


Code:

```python
def test(a, b):
return a+b
```


Links to webpages: [some link](https://www.google.com)


Also tables:

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |


Even $\LaTeX$ formulas! Check this out:

\\[
\begin{align}
a_n^{k+1} := &a_n^{k} - \alpha_k b_n^k, \forall n \in \mathbb{Q}^{\mathbb{C}}\newline
a_{k+1}^{k+1} := &\alpha_k = \frac{\langle R_kf, x_{k+1} \rangle}{\lVert \gamma_k \rVert_2^2}\newline
X \sim &\mathcal{N}(0, 1)
\end{align}
\\]

Inline math is also possible with $\frac{1}{\sum_{i=0}^{10} x_i * e^i}$. You can add images from the `static` folder as follows:

<img class="img-responsive" src="/static/yellowstone.jpg">



And you can add also PDF files:

* Check out [this PDF](/static/markdown_cheatsheet.pdf)


Embedding youtube videos is a bit trickier, but can be done as follows:


{% include embed_video.html url="https://youtube.com/embed/7OMxBlK46wY" %}

---

This language is called `Markdown`. Check below for more info:
* [basic markdown syntax](https://www.markdownguide.org/basic-syntax/#emphasis)

