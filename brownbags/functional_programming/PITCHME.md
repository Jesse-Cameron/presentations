<!-- https://gitpitch.com/jesse-cameron/presentations/functional-programming?p=brownbags/functional_programming#/ -->

# Functional Programming

---

#### What even is Functional Programming (FP)?

- FP has been around since like the _50's..._
- Languages like Haskell, Clojure, Erlang
- FP is _really_ hot right now because of JS
    - But is JS even a functional language?

+++

What makes up a Functional Language:s

@ul[arrow]
- monads
- functors
- applicatives
@ulend

+++

**Nah,** miss me with that **BS**. </br>
Let's get look at _real, practical_ functional prorgamming.

---

There are two major principles that we are going to go over:

@ol[alpha]
- reducing side effects / using pure side effect
- immutable data structures 
@olend

+++

The goals :

@ul
- readability
- testability
- together we get: confidence
@ulend

Note:

As a software engineer, having confidence in your software is paramount.

---

#### what do we want to know?

Chances are: a lot of us are using a lot of functional programming concepts in our apps/apis/sdks already.

@ul
- map/filter/reduce
- Object Spread
@ulend

---

#### What are side effect?

When people talk about functional programming, you'll hear constantly:
_No Side Effects_

But what the heck even is that? 
Is it like a medicine?

Note:

Insert casual dig a OO programming.


