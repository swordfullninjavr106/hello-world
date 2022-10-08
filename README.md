#Program in python for fibonacci series
num=int(input("Enter the number="))
a=0
b=1
count=0
if(num<0):
    print("Please enter correct input.")
else:
    print("Fibonacci series of the number",num,"is")
    while(count<num+1):
        print(a)
        c=a+b
        a=b
        b=c
        count+=1
