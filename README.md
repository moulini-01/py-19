# py-19
prints vowels using python
def count_vowels(s):
    vow="AEIOUaeiou"
    count=0
    for i in s:
        if i in vow:
            count+=1
    return count
print(count_vowels("HELLO"))
