secretword= "eren"
guess= ""
guess_count = 0
guess_limit = 3
out_of_limit = False

while guess != secretword and not(out_of_limit):
    if guess_count < guess_limit:
        guess=input("Your Guess : ")
        guess_count += 1
    else:
        out_of_limit = True

if (out_of_limit):
    print("You Are Out Of Limit, You Lose:(")
else:
    print("You Win")


