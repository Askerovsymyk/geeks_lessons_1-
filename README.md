# geeks_lessons_1-

                       # HomWork №1

try:
    Monday = int(input("введите расходы на понидельник: "))
    Tuesday = int(input("введите расходы на втроник: "))
    Wednesday = int(input("введите расходы на среду: "))
    Thursday = int(input("введите расходы на четверг: "))
    Friday = int(input("введите расходы на пятницу: "))
    Saturday = int(input("введите расходы на субботу: "))
    Sunday = int(input("введите расходы на воскресение: "))

    total_expenses = round(Monday + Tuesday + Wednesday + Thursday + \
                           Friday + Sunday + Sunday / 7, 1)

    print(f"ваш расходы составляет: {total_expenses}")

except ValueError:
    print("введен не правильный данный")
