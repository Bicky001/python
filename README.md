# python
def find_anagram(word, anagram):
    # [assignment] Add your code here

     string1 = input("enter the word:")
     string2 = input("enter the word:")
     string1_word =sorted(string1)
     string2_word = sorted(string2)
    
  
     if string1_word == string2_word:
          print("the strings are anagram")
     else:
          print ("the string is not an anagram")

find_anagram("tab", "atb")
