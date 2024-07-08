---
title: Using LaTeX to Write Mathematical Equations
description: A sample file to show how to use LaTeX in CaC.
---

LaTeX is a high-quality typesetting system; it includes features designed for the production of technical and scientific documentation. LaTeX is the de facto standard for the communication and publication of scientific documents. LaTeX is available as free software.

## LaTeX in CaC

You can use LaTeX to write mathematical equations in CaC, here is some examples of how it works and how is can be used in CaC, you can also read more about [LaTeX].

### Math Mode

To enter math mode or to write mathematical equations you need to use the following syntax:

```latex
$ \text{Inline Equation} $
$$ \text{Display Equation} $$

$$ \begin{equation} \text{Numbered Equation} \end{equation} $$
```

$ \text{Inline Equation} $  
$$ \text{Display Equation} $$

$$ \begin{equation} \text{Numbered Equation} \end{equation} $$

### Quotes

```latex
$$ \text{``This is a quote''} $$
```

$$ \text{``This is a quote''} $$

### Basic Equations

```latex
$ x + x^2 - 3 = 0 $
```

$ x + x^2 - 3 = 0 $

### Fractions

```latex
$ \frac{a}{b} \times \frac{c}{d} = \frac{a \times b}{c \times d}$
```

$ \frac{a}{b} \times \frac{c}{d} = \frac{a \times b}{c \times d}$

### Roots

```latex
$ \sqrt{a} \sqrt[3]{a} $
```

$ \sqrt{a} \sqrt[3]{a} $

### Greek Letters

```latex
$ \alpha, \beta, \theta, \lambda, \pi, \omega $
```

$ \alpha, \beta, \theta, \lambda, \pi, \omega $

### Relations

```latex
$ \times \div \pm + -$
```

$ \times \div \pm + -$

### Arrows

```latex
$ \leftarrow \rightarrow \uparrow \downarrow \leftrightarrow \Leftarrow \Rightarrow \Uparrow \Downarrow \Leftrightarrow$
```

$ \leftarrow \rightarrow \uparrow \downarrow \leftrightarrow \Leftarrow \Rightarrow \Uparrow \Downarrow \Leftrightarrow$

### Tables

```latex
$$
\begin{array}{|c|c|c|}
\hline
\text{Column 1} & \text{Column 2} & \text{Column 3} \\ \hline
\text{Row 1} & \text{Row 1} & \text{Row 1} \\ \hline
\text{Row 2} & \text{Row 2} & \text{Row 2} \\ \hline
\text{Row 3} & \text{Row 3} & \text{Row 3} \\ \hline
\end{array}
$$
```

$$
\begin{array}{|c|c|c|}
\hline
\text{Column 1} & \text{Column 2} & \text{Column 3} \\ \hline
\text{Row 1} & \text{Row 1} & \text{Row 1} \\ \hline
\text{Row 2} & \text{Row 2} & \text{Row 2} \\ \hline
\text{Row 3} & \text{Row 3} & \text{Row 3} \\ \hline
\end{array}
$$

### Matrix

```latex
$$
\begin{bmatrix}
a & b \\[0.3em]
c & d
\end{bmatrix}
$$
```

$$
\begin{bmatrix}
a & b \\[0.3em]
c & d
\end{bmatrix}
$$

### Some Complex Equations Example

```latex
$$ \begin{equation} \frac{d}{dx} \sqrt{x} = \frac{1}{2 \sqrt{x}} \end{equation} $$

$$ \begin{equation} x^2 + 2x + 1 = 0 \end{equation} $$

$$ \begin{equation} \frac{1}{2} \times \frac{1}{2} = \frac{1}{4} \end{equation}$$

$$ \begin{equation} \mathbb{N} = \{ a \in \mathbb{Z} : a > 0 \} \end{equation}$$

$$
\begin{equation}
M =
\begin{bmatrix}
\frac{5}{6} & \frac{1}{6} & 0 \\[0.3em]
\frac{5}{6} & 0 & \frac{1}{6} \\[0.3em]
0 & \frac{5}{6} & \frac{1}{6}
\end{bmatrix}
\end{equation}
$$
```

$$ \begin{equation} \frac{d}{dx} \sqrt{x} = \frac{1}{2 \sqrt{x}} \end{equation} $$

$$ \begin{equation} x^2 + 2x + 1 = 0 \end{equation} $$

$$ \begin{equation} \frac{1}{2} \times \frac{1}{2} = \frac{1}{4} \end{equation}$$

$$ \begin{equation} \mathbb{N} = \{ a \in \mathbb{Z} : a > 0 \} \end{equation}$$

$$
\begin{equation}
M =
\begin{bmatrix}
\frac{5}{6} & \frac{1}{6} & 0 \\[0.3em]
\frac{5}{6} & 0 & \frac{1}{6} \\[0.3em]
0 & \frac{5}{6} & \frac{1}{6}
\end{bmatrix}
\end{equation}
$$

[latex]: https://ashki23.github.io/markdown-latex.html#latex-equations
