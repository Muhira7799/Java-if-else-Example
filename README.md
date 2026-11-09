# Java `if / else` Example

A minimal Java program that demonstrates an `if / else` statement. It prints one of two messages depending on the value of a number.

## What It Demonstrates

```java
int i = 2;
if (i > 4) {
    System.out.println("value of i = " + i);
} else {
    System.out.println("Come to class");
}
```

If the condition is true, the `if` block runs. Otherwise, the `else` block runs. Exactly one of the two blocks always runs.

## How It Works

1. `i` is set to `2`.
2. The condition `i > 4` is checked. `2 > 4` is false.
3. The `if` block is skipped and the `else` block runs.

## Output

```
Come to class
```

## Results for Different Values of `i`

| `i` | Condition `i > 4` | Output |
|-----|-------------------|--------|
| 2 | false | Come to class |
| 4 | false | Come to class |
| 5 | true | value of i = 5 |
| 10 | true | value of i = 10 |

## Requirements

- Java Development Kit (JDK) 8 or higher

## Getting Started

### Clone the repository

```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
```

### Compile

```bash
javac Xxyz.java
```

### Run

```bash
java Xxyz
```

## Try It Yourself

Change the value of `i` to `7`, then compile and run again:

```java
int i = 7;
```

Output:

```
value of i = 7
```

## Project Structure

```
.
├── Xxyz.java
└── README.md
```

## Next Steps

- Add an `else if` branch for more conditions
- Read `i` from the user with `Scanner`
- Compare with a `switch` statement
