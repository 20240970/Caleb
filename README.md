# Caleb
This is IT5016 work created by Caleb

-------------------------------------
#date
import datetime 
import random
date = datetime.datetime.now()

#staff members first & last name
first_name = input('enter first name here: ')
last_name = input('enter last name here: ')
name = first_name + " " + last_name

#staff ID
staff_id = input('enter your staff id: ')

#resquisiton ID
import random
resquisiton_id =(random.randrange(10000, 99999))

#staff info
staff_info = name + " " + staff_id

# calculation of all items
def calculator(cof, pap, pen):
    total = cof + pap + pen  

#calculation of all items
def calculator(cof, pap, pen):
    total = cof + pap + pen  
    return total

#prices of items
cof = int(input('enter the price of coffee: '))
pap = int(input('enter the price of paper: '))
pen = int(input('enter the price of pen: '))

#total requisition
requisition_total = calculator(cof, pap, pen)

#requisition total
print(f'total requisition amount: {requisition_total}')

#total display
print(f'staff information:')
print(f' date: {date}')
print(f' reference number: {resquisiton_id}')
print(f' staff ID: {staff_id}')
print(f' staff name: {name}')
print(f' total: {requisition_total} ')
print(f' status: {"approved" if requisition_total <= 500 else "pending"}')
print(f' requisition ID: {resquisiton_id}')

