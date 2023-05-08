# strings2
primeiro='Ruud Gullit'
segundo='Marco van Basten'
goal_0=32
goal_1=54
report=f"{primeiro} scored in the {goal_0}nd minute" f"\n{segundo} scored in the {goal_1}th minute"
print(report)
scorers=primeiro + ' ' +str(goal_0) + segundo + ' ' + str(goal_1)
player='Jan Wouters'
space= player.find(' ')
first_name=player[0:space]

print(first_name)
last_name_len=len('Wouters')

name_short=player[0].find('Wouters')
for chant in range(3):
    chant='Jan!'
    print(chant)
good_chant=2!=3
print(good_chant)
