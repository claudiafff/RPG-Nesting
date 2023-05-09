# RPG-Nesting
This code will be creating dictionaries and nested information about the characters for my text-based game. 

#The dictionary for "yourname"
yn={'inventory': 'portable cutlery',                               #For eating
    'location':' in Picked location',                              #Location that you pick in the game
    'Personality':['sweet', 'funny', 'psychotic', 'cool'],         #Personality on top
    }
#The dictionary for Pitbull   
Pitbull={'inventory':'hair gel',                                   #To look good 
    'location':'With Y/N',                                         #He's clingy
    'Personality':'Worldwide',                                     #Icon personality
    }
#The dictionary for John Cena 
Johncena={'inventory':'WWE belt',                                  #To show off
    'location':'With Y/N',                                         #He's also clingy
    'Personality': 'Boxer',                                        #Have to stay proffessional
    }
#The dictionary for Gordon Ramsay
Gordonramsay={'inventory':'rat',                                   #To help him cook
    'location': ' at his restaraunt',                              #He is at his restaraunt duhhh
    'Personality': 'Hot headed',                                   #We all know this
    }

#Nesting the characters dictionaries into a list
characters={'Date':['Pitbull','John Cena'], 'Main Character': 'yn', 'Background character': 'Gordon Ramsay',}

#Looping for every key value pair within the characters dictionaries
for key, value in characters.items():
    print(f"{value} is a {key}.")                                               #Who the character is within the stories context
    
    print(f"{value} has an inventory containing: {value['inventory']}.")        #Saying what the inventory is
    print(f"{value} is located {value['location']}.")                           #Saying where they are located
    print(f"{value} has a personality that is {value['Personality']}.")         #Explaining their personality a little
    print("\n")                                                                 #Line break to make it easier to read.
