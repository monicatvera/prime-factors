# Kata prime factors 
Decompose a natural number into its prime factors. To do this, we will create a function primeFactors, to which we pass the number we want to decompose and it will return an array with the prime factors, ordered from smallest to largest.

Development with TDD and applying the premise of transformation priority, without being strict in the steps, but in the order. To achieve success in progressive generalization, it is essential to choose the right examples in the appropriate order.

Examples to work on in the tests:

```
- 2 ⇒ [2]
- 2 * 2 ⇒ [2,2]
- 2 * 2 * 2 ⇒ [2,2,2]
- 3 ⇒ [3]
- 3 * 3 ⇒ [3,3]
- 3 * 2 ⇒ [2,3]
- 5 * 5 ⇒ [5,5]
- 5 * 7 * 11 * 3 ⇒ [3,5,7,11]
```

## Test list
List of possible tests that we want to do based on their difficulty:
- [ ] **{} ⇒ nil**: if there is no code to return null..
- [ ] **nil ⇒ constant**: from null to returning a literal value.
- [ ] **constant ⇒ constant+**: from a simple literal value to a more complex one.
- [ ] **constant ⇒ scalar**: from a literal value to a variable.
- [ ] **statement ⇒ statements**: add more lines of code without conditionals.
- [ ] **unconditional ⇒ if**: introduce a conditional.
- [ ] **scalar ⇒ array**: from simple variable to collection.
- [ ] **array ⇒ container**: from collection to container.
- [ ] **statement ⇒ recursion**: introduce recursion.
- [ ] **if ⇒ while**: convert conditional to loop.
- [ ] **expression ⇒ function**: replace expression with function call.
- [ ] **variable ⇒ assignment**: mutate the value of a variable.