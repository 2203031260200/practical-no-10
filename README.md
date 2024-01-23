fh=open("output 10.txt",'w')
a= input("enter the binary number")
from_base =2
answer=int(a,from_base)
fh.write( "\nthe answer is:"+str(answer))
b=int(input("\nenter the decimal :"))
answer=bin(b)
fh.write("\n the ansewr is :"+str(answer [2:]))
fh.close
