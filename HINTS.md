# Hints

## Task 1: Unit Testing a Stack Class

### Hints for Implementation:

1. **Stack Class**: Create a `Stack` class that uses an `ArrayList` or an array to store the elements. Implement methods like `push`, `pop`, and `peek`.

2. **Exception Handling**: Consider what should happen when someone tries to pop an element from an empty stack.

3. **Generics**: Optionally, use Java Generics to allow the stack to hold different types of elements.

### Hints for Testing:

1. **Test Cases**: Think about different scenarios: pushing elements, popping elements, and peeking at the top element.

2. **Exception Scenarios**: Write a test that ensures an exception is thrown when you try to pop from an empty stack.

## Task 2: Advanced Unit Testing

### Hints for Implementation:

1. **Sorting Algorithm**: Choose a sorting algorithm that you're comfortable with. It could be Bubble Sort, Quick Sort, etc.

2. **Method Signature**: Design your sorting method. Will it sort in-place or return a new array?

### Hints for Testing:

1. **Parameterized Tests**: Use `@ParameterizedTest` and `@MethodSource` or `@CsvSource` to feed multiple sets of data into your tests.

2. **Test Scenarios**: Consider different scenarios like already sorted arrays, reverse-sorted arrays, arrays with duplicate elements, and empty arrays.