# Match-Sequence
Match the number in the case and use of "if"
a = int(input("Enter the first number: "))
#this is match case exercise
match a:
    case 100 if a == 100:
                      print(a, "is equal than 100")
    case 200 if a < 100:
                      print(a, "is less than 100")
    case 300  if a != 100:
                      print(a, "is not equal to 100")
# So here we ends up with the match case excericse
#Thanks for checking my exercise
print(a)
