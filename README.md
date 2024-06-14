def fibonacci(n):
    fib_sequence = [0, 1]
    while len(fib_sequence) < n:
        next_value = fib_sequence[-1] + fib_sequence[-2]
        fib_sequence.append(next_value)
    return fib_sequence

# Generate the Fibonacci sequence up to the 67th term
n = 67
fib_sequence = fibonacci(n)

# Print the Fibonacci sequence
for index, value in enumerate(fib_sequence):
    print(f"F({index}) = {value}")# TASKS-AI-MyCap-24
