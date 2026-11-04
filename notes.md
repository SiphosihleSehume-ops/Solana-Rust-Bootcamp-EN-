## What is usize? 

- an `unsigned integer` type used primarily for sizes, lengths, and indexing collections.

Think of it  as Rust's natural way for working with the size of data structures.

# Example 

```bash
let numbers = [1, 2, 3, 4, 5];

let length: usize = numbers.len();

```

- `numbers.len()` return a usize.

- usize: usigned integer for the `target architecture`. Generally used for collection lengths, indexes, and counting elements. 

- u64: used for balances, token amounts and lamports.

## What is deferencing and ownership?

# Example

```bash
let number: u64 = 50;

let reference = &number;

let actual_value = *reference;
```

`What does &number mean?`

- It means: Give me a reference to the value stored in `number`, rather than giving me the value itself. The reference lets you access the original value. 

Actual value contains `50`. 