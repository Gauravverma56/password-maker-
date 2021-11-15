# password-maker-
import random
lower = "abcdefghijklmnopqwxyz"
upper = "ABCDEFGHIJKLMNOPQXYZ"
numbers = "123456789"
symbol = "(){}[]*;._-"

all = lower + upper + numbers + symbol
lenght = 9
password = "".join(random.sample(all, lenght))
print("the password u garanted is ;", password)
