# Fibonacci-Sequence-
# Generate Fibonacci sequence up to 50
a, b = 0, 1
while a <= 50:
    print(a, end=" ")
    a, b = b, a + b
