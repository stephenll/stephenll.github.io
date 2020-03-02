# Notes on the Julia Programming Language

This looks interesting.

```julia
N = 10
r = rand(N,N)
x = [1,2,3,4,5]
```

$$\frac{\alpha}{\beta} = \gamma$$

Another code blockz.

```julia
function hypot(x,y)
    x = abs(x)
    y = abs(y)
    if x > y
        r = y/x
        return x*sqrt(1+r*r)
    end
    if y == 0
        return zero(x)
    end
    r = x/y
    return y*sqrt(1+r*r)
end
```
