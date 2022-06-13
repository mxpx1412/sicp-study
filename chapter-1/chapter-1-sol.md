# Intro
[Test File](./test.rkt "Test File")

# Chapter 1.1
## Exercise 1.1
Sequence of expressions and associated output.
    10
    > 10
    (+ 5 3 4)
    (- 9 1)
    (/ 6 2)
    (+ (* 2 4) (- 4 6))
    (define a 3)
    (define b (+ a 1))
    (+ a b (* a b))
    (= a b)
    (if (and (> b a) (< b (* a b)))
        b
        a)
    (cond ((= a 4) 6)
          ((= b 4) (+ 6 7 a))
          (else 25))
    (+ 2 (if (> b a) b a))
    (* (cond ((> a b) a)
             ((< a b) b)
             (else -1))
       (+ a 1))

[Exercise 1.1](./1-1.rkt "Exercise 1.1")

## Exercise 1.2
[Exercise 1.2](./1-2.rkt "Exercise 1.2")
