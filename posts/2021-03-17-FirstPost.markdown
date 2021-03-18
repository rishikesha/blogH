---
title: This is an example post
---

When i started this blog, I wrote this first post just to experiment
with various features of Hakyll. I will not delete this post. and possibly use
it later to perform more experiments as the site evolves.


```python
def f(x):
  return x + 1
```

Check the latex typesetting.

\begin{equation}
\sin^2 + \cos^2 =1
\end{equation}

Let us try another equation

\begin{equation}
\frac{x^2} {x^3 +1}
\end{equation}

Let us end with a C++ code
```c++
int f(int n) {
  std::vector<int> v(n);
  for (int i=0; i < n; i++>) {
    v[i] = i;
  }
}
```

and Fibonacci number in haskell

```haskell
fib = 1 : 1 : zipWith (+) fib (drop 1 fib)
```
