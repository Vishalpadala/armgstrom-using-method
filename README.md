# armgstrom-using-method
def arg(n):     num=n     r=0     while n>0:         rem=n%10         r=r+rem*rem*rem         n=n//10     if num==r:         print("armstrong number")     else:         print("not armstrong number")  n=int(input()) arg(n)
