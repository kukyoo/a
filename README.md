# hi i am a begginer with python and i wanted to ans if that script si correct and if not please let me know i will be more than thankfull


number = float(input("enter number: "))  

for i in range(52):  
    additional_number = float(input(f"Do you want to add some number in the loop? {i+1}? (if not, enter 0): "))
    number += (number * 0.1243) + additional_number 

print(f"result: {number}") 
