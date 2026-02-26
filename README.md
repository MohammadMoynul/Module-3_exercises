# Module-3_exercises
# Answer to the Question no: 1
length = float(input("Enter the length of the zander in centimeters: "))
if length >= 42:
    print("The zander meets the size limit.")
else:
    difference = 42 - length
    print(f"Please release the fish back into the lake.")
    print(f"The fish is {difference:.1f} centimeters below the size limit.")
# Answer to the Question no: 2 
cabin_class = input("Enter the cabin class (LUX, A, B, C): ").upper()

if cabin_class == "LUX":
    print("LUX: upper-deck cabin with a balcony.")
elif cabin_class == "A":
    print("A: above the car deck, equipped with a window.")
elif cabin_class == "B":
    print("B: windowless cabin above the car deck.")
elif cabin_class == "C":
    print("C: windowless cabin below the car deck.")
else:
    print("Invalid cabin class.")
# Answer to the Question no: 4
year = int(input("Enter a year: "))

if (year % 4 == 0 and year % 100 != 0) or (year % 400 == 0):
    print(f"{year} is a leap year.")
else:
    print(f"{year} is not a leap year.")
