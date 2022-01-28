
# 1

# promt user to enter their weight and then they can choose whether it's L(pounds) or k(Kg):

weight = int(input("what is your weight? : "))

unit = str(input("bs(L) or K(kg) : "))

if unit.upper() == "L":
    converted = weight * 0.45
    print(f"You are {converted} kilos")
else:
    converted = weight / 0.45
    print(f"You are {converted} pounds")

# 2
# guessing game script
secret_number = 23
guess_count = 0 # it is best practice to name variables clearly for code review, working with colleagues
guess_limit = 3
while guess_count < guess_limit:
    guess = int(input("guess: "))
    guess_count += 1
    if guess == secret_number:
        print("You won")
        break
else:
    print("Sorry, You failed")
