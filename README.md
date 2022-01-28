# Python scripting practice 1
# weight_to_Kg

# promt user to enter their weight and then they can choose whether it's L(pounds) or k(Kg):

weight = int(input("what is your weight? : "))

unit = str(input("bs(L) or K(kg) : "))

if unit.upper() == "L":
    converted = weight * 0.45
    print(f"You are {converted} kilos")
else:
    converted = weight / 0.45
    print(f"You are {converted} pounds")
