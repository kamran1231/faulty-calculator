# faulty-calculator#faulty calculator
#BLL
def add(a,b):
   return a + b

def sub(a,b):
    return a - b

def mul(a,b):
    return a * b

def div(a,b):
    return a/b







#PL
print('welcome to my Calculator')
print('1. ADD NUMBER \n 2. SUB NUMBER \n 3. MUL NUMBER \n 4. DIV NUMBER')  #choices for the user

ch = input('enter your choice: ')  #enter the choice number
num1 = int(input('enter the first number: '))
num2 = int(input('enter the second number: '))

if ch == '1':
    if num1 == 56 and num2 == 9:
        print('the add of two number is: 77')
    else:
        print('the add of two number is:',add(num1,num2))


elif ch == '2':
    print('the subtraction of two number is:',sub(num1,num2))

elif ch == '3':
    if (num1 == 45 and num2 == 3):
        print('the multiply of two number is: 555')
    else:
        print('the multiply of two number is:',mul(num1,num2))


elif ch == '4':
    if num1 == 56 and num2 == 6:
        print('the division of two number is: 4')
    else:
        print('the division of two number is:',div(num1,num2)
