# Reverse-Swap-Function
#Implement a function that takes a string consisting of words separated by single spaces and returns a string containing all those words but in the reverse order and such that all 
cases of letters in the original string are swapped, i.e. lowercase letters become uppercase and uppercase letters become lowercase.


def reverse_swap(sentence):
    words = sentence.split()
    reversed_sentence = ' '.join(reversed(words))
    return reversed_sentence

sentence = input()
result = reverse_swap(sentence)
print(result)
