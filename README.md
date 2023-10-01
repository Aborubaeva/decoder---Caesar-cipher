# decoder---Caesar-cipher
n = int(input())
s = input()
s2 = ""
for i in range(len(s)):
    if ord(s[i]) - n < 97:
        s1 = chr(ord(s[i]) - n + 26)
    else:
        s1 = chr(ord(s[i]) - n)      
    s2 += s1
print(s2)
