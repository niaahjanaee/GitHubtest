# GitHubtest
def fibonacci(n):
for i in range(2, n + 1):
    fib.append(fib[-1] + fib[-2])
return fib

terms = [100, 50000, 100000]
for term in terms:
    fib_sequence = fibonacci(term)
    print("The termth term of the Fibonaaci sequence is: {fib_sequence[-1]})