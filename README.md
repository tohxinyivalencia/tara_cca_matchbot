# -jasons_cca_matching_personality_bot
print("Title of program: What CCA is for you?")
print()
print("Welcome to DHS! Please answer the following questions truthfully and we'll suggest a CCA for you!")
print("Please respond with a number 1 - 5, where 1 is strongly disagree and 5 is strongly agree.")
print()

tech1 = input("I enjoy computers and technology.")

outdoor1 = input("I'll go crazy if I do not go out of the house for the whole day.")

music1 = input("Music connects to my soul.")

tech2 = input("I know how to build apps and websites.")

outdoor2 = input("I'm good with tying knots and ropes.")

music2 = input("I play a musical instrument well.")


tech_final = int(tech1) + int(tech2)
outdoor_final = int(outdoor1) + int(outdoor2)
music_final = int(music1)+ int(music2)

print()

if tech_final > outdoor_final and tech_final > music_final:
  print("You might be suitable for Infocomm club!")
elif outdoor_final > music_final:
  print("You might be stuiable for a Uniform Group!")
else:
  print("You might be suitable for Performing Arts!")
