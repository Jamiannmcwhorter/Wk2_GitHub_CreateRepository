# Wk2_GitHub_CreateRepository
#This is my Repository for Daen 500 01
#I am taking a Data Science Master's Program and trying to learn how to use GitHub to manage changes to code in an organized way


lemon_juice_cups = float(input('Enter amount of lemon juice (in cups):\n'))


water_cups = float(input('Enter amount of water (in cups):\n'))

agave_cups = float(input('Enter amount of agave nectar (in cups):\n'))

servings = float(input('How many servings does this make?\n'))
print("")


print('Lemonade ingredients - yields', '{:.2f}'.format(servings), 'servings')
print('{:.2f}'.format(lemon_juice_cups), 'cup(s) lemon juice')
print('{:.2f}'.format(water_cups), 'cup(s) water')
print('{:.2f}'.format(agave_cups), 'cup(s) agave nectar')
print("")

servingslike = int(input('How many servings would you like to make?\n'))
print("")
print('Lemonade ingredients - yields','{:.2f}'.format(servingslike),'servings')
cups_lmn_needed= (servingslike) / 3
cups_wtr_needed= float(servingslike*2.66666)
cups_agv_needed= float(servingslike /2.4)

print('{:.2f}'.format(cups_lmn_needed), 'cup(s) lemon juice')
print('{:.2f}'.format(cups_wtr_needed), 'cup(s) water')
print('{:.2f}'.format(cups_agv_needed), 'cup(s) agave nectar')
print("")
print('Lemonade ingredients - yields','{:.2f}'.format(servingslike),'servings')
gal_lmn_needed= (cups_lmn_needed /16)
gal_wtr_needed= (cups_wtr_needed /16)
gal_agv_needed= (cups_agv_needed /16)
print('{:.2f}'.format(gal_lmn_needed), 'gallon(s) lemon juice')
print('{:.2f}'.format(gal_wtr_needed), 'gallon(s) water')
print('{:.2f}'.format(gal_agv_needed), 'gallon(s) agave nectar')

# FIXME (1): Finish reading other items into variables, then output the three ingrdients
   
# FIXME (2): Prompt user for desired number of servings. Convert and output the ingredients

# FIXME (3): Convert and output the ingredients from (2) to gallons
   
#(1) Prompt the user for the number of cups of lemon juice, water, 
#and agave nectar needed to make lemonade. Prompt the user to specify the number of servings the recipe yields. 
#Output the ingredients and serving size. (Submit for 2 points).
