## Modern JaveScript Cheatsheet

# Notions

- `Variable declaration: var, const, let -are 3 different keywords available to declair a variable. Though const and let are prefered`

  -`const variable cannot be reassigned.`

  - `let and var variables can` -`It is often recommended to declair a variable with a const as default` - `Although using let is best if it is a variable that you need to mutate or reassign later`

- `The scope of a variable roughly means "where is this variable available in the code".`

- `var declared variables are function scoped, meaning that when a variable is created in a function, everything in that function can access that variable.`

- `var and let are about the same, but let declared variables...` -`are block scoped`

  - `are not accessible before they are assigned`
  - `can't be re-declared in the same scope`

- `const declared variables behave like let variables, but also they can't be reassigned....` -`To sum it up, const variables:`
  - `are block scoped`
  - `are not accessible before being assigned`
  - `can't be re-declared in the same scope`
  - `can't be reassigned`
