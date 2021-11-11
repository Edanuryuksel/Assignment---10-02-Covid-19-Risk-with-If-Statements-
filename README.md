# Assignment---10-02-Covid-19-Risk-with-If-Statements-

age = bool(input("Are you a cigarette addict older than 75 years old? : "))
chronic = bool(input("Do you have a severe chronic disease? : "))
immune = bool(input("Is your immune system too weak? : "))


if age or chronic or immune == True :
   print("You are in risky group")
else :
   print("You are not in risky group")
