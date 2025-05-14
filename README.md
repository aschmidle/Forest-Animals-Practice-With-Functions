# Forest-Animals-Practice-With-Functions
# This is a simple practice of functions using a mystic forest theme.

"""
greet_animal(animal_name) Function: Create a function that takes an animal’s name (string) as input and returns a friendly greeting. For example:

greet_animal("Squirrel") should return "Hello, Squirrel! Welcome to the forest!".
greet_animal("Bear") should return "Hello, Bear! Welcome to the forest!"
count_mushrooms(mushroom_type, quantity) Function: Create a function that takes a mushroom type (string) and a quantity (integer) as input. The function should return a string that describes how many mushrooms of that type were found. For example:

count_mushrooms("Red Cap", 5) should return "I found 5 Red Cap mushrooms!"
count_mushrooms("Blue Foot", 12) should return "I found 12 Blue Foot mushrooms!"
animal_sound(animal, sound) Function: Create a function that takes an animal’s name (string) and a sound (string) as input and returns a string with the sound that the animal makes. For example:

animal_sound("Fox", "Woof") should return "The Fox says Woof!"
animal_sound("Owl", "Hoo") should return "The Owl says Hoo!"
"""




def greet_animal(animal_name):
    return f"Hello {animal_name}! Welcome to the forest!"

def count_mushrooms(mushroom_type, quantity):
    return f"I found {quantity} {mushroom_type}!"

def animal_sounds(animal, sound):
    return f"The {animal} says {sound}!"

print greet_animal(("Squirrel"))
print greet_animal(("Shark"))
print greet_animal(("Tiger"))

print count_mushrooms(("red", 5))
print count_mushrooms(("blue", 6))
print count_mushrooms(("green", 7))

print animal_sounds(("cow", "moo"))
print animal_sounds(("pig", "oink"))
print animal_sounds(("duck", "quack"))
