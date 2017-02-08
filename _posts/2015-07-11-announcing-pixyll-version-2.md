---
layout:     post
title:      Announcing Version 2.0
date:       2015-07-11
summary:    Now, Pixyll is lighter weight and more customizable than before.
categories: jekyll pixyll
---

In an effort to make Pixyll easier to customize and more aesthetically pleasing, we've release version `2.0`.
Here is an example $$ x_1^2 = 4 $$
<div> 
$$
\begin{align*}
  & \phi(x,y) = \phi \left(\sum_{i=1}^n x_ie_i, \sum_{j=1}^n y_je_j \right)
  = \sum_{i=1}^n \sum_{j=1}^n x_i y_j \phi(e_i, e_j) = \\
  & (x_1, \ldots, x_n) \left( \begin{array}{ccc}
      \phi(e_1, e_1) & \cdots & \phi(e_1, e_n) \\
      \vdots & \ddots & \vdots \\
      \phi(e_n, e_1) & \cdots & \phi(e_n, e_n)
    \end{array} \right)
  \left( \begin{array}{c}
      y_1 \\
      \vdots \\
      y_n
    \end{array} \right)
\end{align*}
$$ 
</div>  

Pixyll now features:

* Line anchors in code blocks and new syntax highlighting
* A customizable variables file
* Modular, and lighter weight CSS
* No more `max-width` media queries
