# CMPS 2200 Recitation 06
## Answers

**Name:**____Noelle_____
**Name:**______Mohini_____


Place all written answers from `recitation-07.md` here for easier grading.



- **2)**
The base case: W(O) = W(1) = 1
The recursive case:
W(n)= W(n-1) + W(n-2) +1
Solved:
W(n) = theta(2^n)

- **3)**
Base case:
S(O) = S(1) = 1
Recursive case:
S(n) = max(S(n-1), S(n-2)) +1
Solved:
  S(n) = theta(n)

- **4)**
- An intresting pattern that I found in the counts list is that the function values follow a Fibonacci-like pattern. The counts[i] value shows how many times fib_recursive(i, counts) is called while calculating fib_recursive(n, counts). These values show a tree of overlapping subproblems, many valuws are recalculated numerous different times. 

- **6)**
  - Maximum number of times fib_top_down(i) will be called for any i: once (because the function uses memoization)
  - Work(n) = O(n)
  - Span(n) = O(n)

- **8)**
  - Maximum number of times Fi will be ready for any value i: twice (because of this line fibs[i] = fibs[i - 1] + fibs[i - 2])
  - Work(n) = O(n)
  - Span(n) = O(1)
