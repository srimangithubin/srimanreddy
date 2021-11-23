# srimanreddy
# TABLES



|S.NO|RANKING|COMPANIES|PLAYERNAMES|
|----|-------|---------|-----------|
|1|1|MERCEDIES BENZ|HAMILTON|
|2|2|REDBULL|MAXX VESTRAPPEN|
|3|3|FERRARI|ALFONSO|
# LISTS
# ordered lists
1. LAMBORGINI GALLARDO
2. MC LAREN
3. AUDI
4. BMW
# UNORDERED LISTS
* CARS
* BIKES
* MOVIES
* FOOD
## ****pyton code****
num1 = int(input("Enter First Number: "))
num2 = int(input("Enter Second Number: "))

print("Enter which operation would you like to perform?")
ch = input("Enter any of these char for specific operation +,-,*,/: ")

result = 0
if ch == '+':
    result = num1 + num2
elif ch == '-':
    result = num1 - num2
elif ch == '*':
    result = num1 * num2
elif ch == '/':
    result = num1 / num2
else:
    print("Input character is not recognized!")

print(num1, ch , num2, ":", result)
 

