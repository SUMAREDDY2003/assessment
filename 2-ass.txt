book1=int(input("Introduction to Python Programming :"))
book2=int(input("Python Libraries Cookbook :"))
book3=int(input("Data Science in Python : "))
price=(float(book1*499+book2*855+book3*645))
gst_3books=(12/100)*price
Delivery_Charges=float(250)
total_invoice=price+gst_3books+Delivery_Charges
print("Total invoice amount is:",total_invoice)



s=input("enter a string:")
a=s.lower()
l=[]
for i in a:
	if i not in l:
		l.append(i)
b=",".join(l)
print("uniqueLetters = ",b)