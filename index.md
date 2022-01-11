@def title = "My Franklin Sandbox"
@def hasmath = true
@def hascode = true

# Example Page

This is only a test. 

\toc

## Equations (Latex)

$$ a² + b² = c² $$
$$ \pi = \int_{-1}^1  \frac{dx}{\sqrt{1-x^2}} dx $$

## Julia Code

A Hello World example :)
```julia:./out1
println("Hello, World!")
```

\show{./out1}

Functions...

```julia:./out2
function add(x,y)
    x + y
end
```

with the output
\show{./out2}

And a fitting function call: 
```julia:./out3
add(5, 3)
```

\show{./out3}

One more test:

```julia:./out4
rand(5,5)
```
\show{./out4}


<!---
# Franklin syntax sandbox

This page is meant as a sandbox for Franklin Syntax so that you can quickly practice or experience things.

## Sandbox

Write whatever you want here to practice Franklin Syntax:

```julia:./ex1
using LinearAlgebra, Random
Random.seed!(135)
a, b = randn(50), randn(50)
println(dot(a, b))
println(sum(ai * bi for (ai, bi) ∈ zip(a, b)))
```

\output{./ex1}

(yet another example that floating point arithmetics can be complicated).

$$ \forall x \in \R:\quad \scal{x, x} \ge 0 $$

\newcommand{\E}{\mathbb E}

Surely some people remember the ordering, but I always forget:

$$ \varphi(\E[X]) \le \E[\varphi(X)] $$

for $\varphi$ convex.
-->
