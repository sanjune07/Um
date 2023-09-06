# epidemiological calculator
#prevalence
population = int(input("Population: "))
existingcases = int(input("Existing Cases: "))
prevalence = existingcases / population
print (prevalence)

population: 1780000
existing cases: 99
print(prevalence * 100000)
# incidence
newcases = int(input("New Cases: "))
incidence = newcases / population
print(incidence)
print(incidence * 100000)
New Case: 19
1.0674157303370787e - 05
# mortality rate
dead = int(input("Number of people who died: "))
segment = int(input("Number of those who had the disease: "))
mortalityrate = dead / segment
print(mortalityrate)
print(mortalityrate * 100000)
number of those who died: 2
number of those who had the disease: 99
0.020202020202020204
2020.2020202020203
# years of potentisl life lost
lifeexpectancy = 77
age = [64, 74]
print(lifeexpectancy - ages[0])
print(lifeexpectancy - ages[1])

13
3
lifelost = [13, 3]
yppl = sum(lifelost) / len(lifelost)
print(yypl)

8.0
