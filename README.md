ovpay=0
sum=0
for i in range(1,11):
         print("Enter Working Hours of Emp ",i,":")
         h=int(input())
         if(h>40):
                 extra=h-40
                 ovpay=extra*12
                 print("Over time pay of emp ",i,"is ",ovpay)
                 sum=sum+ovpay
         else:
                 print("No Overtime Pay")

print("Total Overtime Pay of all employees : ", sum)

OUTPUT:
Enter Working Hours of Emp  1 :
25
No Overtime Pay
Enter Working Hours of Emp  2 :
26
No Overtime Pay
Enter Working Hours of Emp  3 :
47
Over time pay of emp  3 is  84
Enter Working Hours of Emp  4 :
45
Over time pay of emp  4 is  60
Enter Working Hours of Emp  5 :
43
Over time pay of emp  5 is  36
Enter Working Hours of Emp  6 :
42
Over time pay of emp  6 is  24
Enter Working Hours of Emp  7 :
49
Over time pay of emp  7 is  108
Enter Working Hours of Emp  8 :
23
No Overtime Pay
Enter Working Hours of Emp  9 :
56
Over time pay of emp  9 is  192
Enter Working Hours of Emp  10 :
46
Over time pay of emp  10 is  72
Total Overtime Pay of all employees :  576
