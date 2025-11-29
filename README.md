Code of the calculator:
while True:
    num1 = int(input("Введите число:"))
    num2 = int(input("Введите второе число:"))
    print("""Выберите операцию " \
    Сложить:+
    Вычесть: - 
    Умножить: *
    Поделить: *
    Квадрат числа: ^2
    Куб числа: ^3
    Корень числа: √
    """)
    operand = input()

    if operand == '+' :
        print(f'{num1} + {num2} = {num1 + num2}\n')
    if operand == '-':
        print(f'{num1} - {num2} = {num1 - num2}\n')
    if operand == '/':
        print(f"{num1} / {num2} = {num1 / num2}\n")
    if operand == '*':
        print(f'{num1} * {num2} = {num1 * num2}\n')
    if operand == '^2':
        print(f"The square of this number: {num1 ** 2}\n")
    if operand  == '^3':
        print(f"The  cube of this number: {num1 ** 3}\n")
    if operand == '√':
        print(f'Here is the square root of your number: {num1 ** 0.5}')
