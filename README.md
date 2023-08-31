# Reverse-Swap-Function

def reverse_swap(sentence):
    words = sentence.split()
    reversed_sentence = ' '.join(reversed(words))
    return reversed_sentence

sentence = input()
result = reverse_swap(sentence)
print(result)



