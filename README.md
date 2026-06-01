# -CIS567-integrated-lab-2
Lab @
user_input = input().split(' ', 1)

char = user_input[0]
phrase = user_input[1]

count = phrase.count(char)

if count == 1:
    print(f"{count} {char}")
else:
    print(f"{count} {char}'s")
