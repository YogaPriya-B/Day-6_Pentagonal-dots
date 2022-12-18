# Day-6_Pentagonal-dots

n=int(input())

sum1=1 

if(n==1):

    print(1)

else:

    for i in range(1,n):

      dot=i*5

      sum1=sum1+dot


    print(sum1)
