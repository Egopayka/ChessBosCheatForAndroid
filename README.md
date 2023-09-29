alphabet = 'абвгдеёжзийклмнопрстуфхцчшщъыьэюя'
result = [f"{c.upper()}{c}" for c in alphabet]
_ = [print("|".join(result[i:i+5]), "\n" + "-"*20) for i in range(0, len(result), 5)]

