---
title: First post, Experiments
---

When I started this blog, I wrote this first post just to experiment
with various features of Hakyll. I will not delete this post, and possibly use
it later to perform more experiments as the site evolves.

Syntax highlighting of python code:
```python
def f(x):
  return x + 1
```

Check the latex typesetting.

\begin{equation}
\sin^2\theta + \cos^2\theta =1
\end{equation}

Let us try another equation

\begin{equation}
\frac{x^2} {x^3 +1}
\end{equation}

Let us end with C++ code
```c++
int f(int n) {
  std::vector<int> v(n);
  for (int i=0; i < n; i++>) {
    v[i] = i;
  }
}
```

and Fibonacci numbers in Haskell.

```haskell
fib = 1 : 1 : zipWith (+) fib (drop 1 fib)
```
