# zadanie_4.2

def palindrome(word):
    word = word.lower()
    drow = "".join(reversed(word))
    print(word == drow)

if "word".isalnum() == True:
    print("True")
elif "word".isalnum() == False:
    print("False")
