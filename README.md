5.13
import random
num_two = 0
num_three = 0
num_four = 0
num_five = 0
num_sixes = 0
num_sevens = 0
num_eight = 0
num_nine = 0
num_ten = 0
num_eleven = 0
num_twelve = 0
num_rolls = int(input('Enter number of rolls:\n'))
while num_rolls >= 1:
    for i in range(num_rolls):
        die1 = random.randint(1,6)
        die2 = random.randint(1,6)
        roll_total = die1 + die2
        if roll_total == 2:
            num_two = num_two + 1
        if roll_total == 3:
            num_three = num_three + 1
        if roll_total == 4:
            num_four = num_four + 1
        if roll_total == 5:
            num_five = num_five + 1
        if roll_total == 6:
            num_sixes = num_sixes + 1
        if roll_total == 7:
            num_sevens = num_sevens + 1
        if roll_total == 8:
            num_eight = num_eight + 1
        if roll_total == 9:
            num_nine = num_nine + 1
        if roll_total == 10:
            num_ten = num_ten + 1
        if roll_total == 11:
            num_eleven = num_eleven + 1
        if roll_total == 12:
            num_twelve = num_twelve + 1
        print('Roll %d is %d (%d + %d)' % (i, roll_total, die1, die2))
        num_rolls = num_rolls - 1
    
    if num_rolls >= 1
        print('Dice roll histogram:')
        print()
        for i in range(num_twos)
            print('$', end=' ')
    if num_rolls >= 1
        print()
        for i in range(num_threes)
            print('$', end=' ')
    if num_rolls >= 1
        print()
        for i in range(num_fours)
            print('$', end=' ') 
    if num_rolls >= 1
        print()
        for i in range(num_fives)
            print('$', end=' ')
    if num_rolls >= 1
        print()
        for i in range(num_sixes)
            print('$', end=' ') 
    if num_rolls >= 1
        print()
        for i in range(num_sevens)
            print('$', end=' ')
    if num_rolls >= 1
         print()
         for i in range(num_eights)
            print('$', end=' ')
    if num_rolls >= 1
        print()
        for i in range(num_nines)
            print('$', end=' ')
    if num_rolls >= 1
        print()
        for i in range(num_tens)
            print('$', end=' ')
    if num_rolls >= 1
        print()
        for i in range(num_elevens)
            print('$', end=' ')
    if num_rolls >= 1
        print()
        for i in range(num_twelves)
            print('$', end=' ')
