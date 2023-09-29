
def print_alphabet():
    alphabet = 'абвгдеёжзийклмнопрстуфхцчшщъыьэюя'
    for i in range(0, len(alphabet), 5):
        line = alphabet[i:i+5]
        print("|".join([c.upper() + c for c in line]), end="\n" + "-" * 20 + "\n" * (i != len(alphabet) - 5))

print_alphabet()
