# probable-parakeet
# password generator
import random
pass_len=int(input("Enter the length of the password : "))
pass_data="qwertyuiopasdfghjklzxcvbnm1234567890[];',./!@#$%^&*()_+:<>?"
password="".join(random.sample(pass_data,pass_len))
print(password)
