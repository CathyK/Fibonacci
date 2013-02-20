Fibonacci
=========
def fib_iterative(n)
  fib_counts = [0, 1]
  (n-1).times do 
    fib_counts << fib_counts[-1] + fib_counts[-2]
  end

  return fib_counts.last
end

fib_iterative(5)

def fib_recursive(n)
