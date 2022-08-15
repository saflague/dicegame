# dicegame
# dice game
number_dice = input('Enter number of dice:')
Enter number of dice:2
number_dice = int(number_dice)
ready = input('Ready to start? Hit any key to continue')
Ready to start? Hit any key to continuej
import random
def roll_dice(n):
    dice = [] #start with empty list of dice
    #add random numbers between 1 to6 to the list
    for i in range(n):
        dice.append(random.randint(1,6))
        return dice
    #step 2 in main function area - roll dice
    #user turn to roll
    user_rolls = roll_dice(number_dice)
    print('User first roll: ', user_rolls)
    #computers turn to roll
 print('Computers turn ')
    computer_rolls = roll_dice(number_dice)
    print('Computer first roll: ', computer_rolls)
    def find_winner(cdice_list, udice_list):
        computer_total = sum(cdice_list)
        user_total = sum(udice_list)
        print('Computer total' , computer_total)
        print('User total' , user_total )
        if user_total > computer_total:
            print('User wins')
	       elif user_total < computer_total:
                
if user_total < computer_total:
    print('Computer wins')
    else:
        print(‘It is a tie!’)

#step 4 - get user choices
user_choices = input('Enter - to hold or r to \ to roll again :')
                    
Enter - to hold or r to \ to roll again :r
while len(user_choices) != number_dice:
   print('you must enter', number_dice, \'choices')
user_choices = input('Enter - to hold or r \ to rollagain :')
              
Enter - to hold or r \ to rollagain :
