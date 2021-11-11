# Assignment---10-02-Covid-19-Risk-with-If-Statements-

age = input("Are you a cigarette addict older than 75 years old?").title().strip() == 'yes'
chronic = input("Do you have a severe chronic disease?").title().strip() == 'yes'
immune = input("Is your immune system too weak?").title().strip() == 'yes'
risk = age and (chronic or immune)

if risk:
    print('You are in risky group')
else:
    print('You are not in risky group')
