"""
1! = 1*1!
2! = 2*1!
3! = 3*2!
4! = 4*3!

10! = 10*9!

for_(n-1)!
"""


def fact_rec(n):
    if n == 0 or n == 1:
       return 1
    else:
      return n* fact_ rec(n-1)


number= int(input ("Enter a value:"))
res = fact_rec(number)
print(" the factorial of{} is{}.".farmat(number,res))
