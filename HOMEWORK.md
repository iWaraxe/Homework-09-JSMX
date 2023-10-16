## Homework

### Task 1: Unit Testing a Stack Class (2 minutes)

For your first assignment, you will be implementing a Stack class and writing unit tests to verify its functionality. A Stack is a data structure that follows the Last-In-First-Out (LIFO) principle.

**Requirements:**

1. Implement `push`, `pop`, and `peek` methods.
2. Write unit tests for these methods.

**Code Example for What Your Stack Class Might Look Like:**

```java
public class Stack {
    // Your implementation
}
```

**Code Example for Unit Tests:**

```java
import org.junit.jupiter.api.Test;
import static org.junit.jupiter.api.Assertions.assertEquals;

public class StackTest {
    // Your tests here
}
```

Your tests should cover typical use-cases such as pushing elements onto the stack, popping elements off the stack, and peeking at the top element without removing it.

### Task 2: Advanced Unit Testing (3 minutes)

Your second assignment is a bit more advanced. You are to write parameterized tests for a sorting algorithm of your choice. You can pick any sorting algorithm you like: Bubble Sort, Quick Sort, Merge Sort, etc.

**Requirements:**

1. Implement the sorting algorithm.
2. Write parameterized tests to validate that the algorithm sorts arrays correctly.

**Code Example for What Your Sorting Class Might Look Like:**

```java
public class SortingAlgorithm {
    // Your sorting algorithm here
}
```

**Code Example for Parameterized Tests:**

```java
import org.junit.jupiter.params.ParameterizedTest;
import org.junit.jupiter.params.provider.MethodSource;
import static org.junit.jupiter.api.Assertions.assertArrayEquals;

public class SortingAlgorithmTest {
    // Your parameterized tests here
}
```

Your tests should cover a variety of scenarios, including but not limited to: sorted arrays, reverse-sorted arrays, arrays with duplicate elements, and empty arrays.

---

These homework assignments will allow you to apply the concepts we've covered, reinforcing your understanding of both basic and advanced unit testing techniques. 
Please complete these tasks before our next session. I look forward to seeing your solutions.