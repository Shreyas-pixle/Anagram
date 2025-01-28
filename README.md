def anagram(str1,str2):
    str1.replace(" ","").upper
    str2.replace(" ","").upper

    return sorted(str1)==sorted(str2)
    

str1=input("Enter the first string:")
str2=input("Enter the second string:")

if not str1.isdigit() or str2.isdigit():
    print("Invalid,It cant be digit")
else:
    if anagram(str1,str2):
        print("It is Anagram")
    else:
        print("It is not Anagram")
