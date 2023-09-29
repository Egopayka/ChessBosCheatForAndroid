def print_rectangle(m, n):
    if m <= 0 or n <= 0:
        print("Введите положительные значения для длины и ширины прямоугольника.")
        return
    
    rectangle = [" " + "A" * m] + ["A" + " "*(m-2) + "A"]*(n-2) + [" " + "A" * m]
    print("\n".join(rectangle))

length = int(input("Введите длину прямоугольника: "))
width = int(input("Введите ширину прямоугольника: "))
print_rectangle(length, width)

