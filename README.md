
# define function fib: 'fibonacci'
def fib(n):
  # In fibonacci this is must reqd
  a, b = 0, 1
  # If elif else
  # In case someone only reqd one ouput
  if n == 1:
    print(a)
  # In case If someone given input in 0 or less
  elif n <= 0:
    print('not possible')
  # main block of code for fibonacci
  else:
   # For first two digits
    print(a)
    print(b)
   # For loop for the logic of fibonacci
    for i in range(2,n):
      c = a + b
      a, b = b, c
   # For printing less then or equals too of fib(n) input fib(10)
      if c <= n:
         print(c)
      else:
         break
# fibonacci and input()
fib(10)
