# Intro
[Test File](./test.rkt "Test File")

# Chapter 1.1

## Exercise 1.1
[Exercise 1.1](./1-1.rkt "Exercise 1.1")
Sequence of expressions and associated output.
```scheme
> 10
10
> (+ 5 3 4)
12
> (- 9 1)
8
> (/ 6 2)
3
> (+ (* 2 4) (- 4 6))
6
> (define a 3)
> (define b (+ a 1))
> (+ a b (* a b))
19
> (= a b)
#f
> (if (and (> b a) (< b (* a b)))
      b
      a)
4
> (cond ((= a 4) 6)
        ((= b 4) (+ 6 7 a))
        (else 25))
16
> (+ 2 (if (> b a) b a))
6
> (* (cond ((> a b) a)
           ((< a b) b)
           (else -1))
     (+ a 1))
16
```

## Exercise 1.2
[Exercise 1.2](./1-2.rkt "Exercise 1.2")
$$\frac{5 + 4 + (2 - (3 - (6 + \frac{4}{3})))}{3(6-2)(2-7)}$$
